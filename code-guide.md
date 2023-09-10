---
title: Guide to Coding
description: brief guide on how to code, will be updated with modularization standards as they come
published: true
date: 2023-09-10T06:29:01.830Z
tags: 
editor: markdown
dateCreated: 2023-09-03T04:53:18.766Z
---

# Guide to Contributing

> I am tired of being told “When you code it"! - You, probably

# Tools 

1.  Dream Maker - comes installed with Byond. NOT RECOMMENDED!
2.  [Visual Studio Code](https://code.visualstudio.com/)  - Modern lightweight code editor. Recommended!
    -   Use in combination with extensions to improve experience. You'll be prompted to install recommended extensions - you 100% should do that. Also, check the extension marketplace!
    -   To compile, use Ctrl + Shift + P and type “build”.
    -   You can debug the project by running the “Launch Dreamseeker” command in the debug menu. This allows you to view variables while executing the code. You can place a breakpoint (forces the system to wait for you to resume it so you can inspect variables)
3.  [Git](https://git-scm.com/) - This is how professionals keep track of changes in code. I highly suggest you get familiar with the git command line, but there are also numerous applications you can use if you're intimidated. Popular applications in the community for interacting with git are Gitkraken, Github Desktop, and Tortoise Git. VS Code also has a pretty solid git client.
    -   Please! Read up on how git works. It's something you MUST work with if you want to contribute on your own. There are tons of resources for this. Here's a decent one I'm familiar with: [https://learngitbranching.js.org/.](https://learngitbranching.js.org/) If you're having issues with git, please check the [git docs](https://git-scm.com/docs) or [your choice](https://wiki.fulp.gg/en/google.com) of [god](https://stackoverflow.com/) for assistance.

4\. For sprites: [Aseprite](https://www.aseprite.org/download/), [Gimp](https://www.gimp.org/), or any other pixel art tool. You will need to convert the files from .dmi to .png if you are using something besides Dream Maker's built-in tool for sprites. Additionally, Aseprite is available for free [here](https://github.com/aseprite/aseprite) but requires more set up than buying it from the website or Steam.

# Getting Started

Now that you have the tools, there's a little more setup we need to do if you want to contribute to the repository.

If you haven't already, make a github account. Next, you'll want to make a fork of [github.com/monkestation/monkestation2.0](https://github.com/Monkestation/Monkestation2.0)(click the fork button in the top right).

Once your fork is ready, you need to pull the code down into your machine. Make a folder somewhere and clone the repo into it (if you're using git via commandline or gitbash, the syntax for this is `git clone github.com/<yourname>/` .  

To keep things clean, you should never make changes in your master branch. That's where you want to fork from, and your goal is to make merging code into the upstream as easy as possible. The best way to do this is to keep your master branch as close to the upstream master branch as possible. You'll want to make branches any time you make changes. 

Making a branch is easy. `git branch <name>` followed by `git checkout <name>` will make and change your active branch to <name>.   
Or you can use `git checkout -b <name>` . Same outcome. Git has a lot of nifty shortcuts and functions. Seriously, read the docs! 

# Code!

Byond, the game engine, uses Dream Maker, which is a language made custom for the engine. 

Dream Maker is object oriented. There is a clearly defined hierarchy. There are 5 main objects.

-   ATOM (You should never use this, forget I said it exists)
    -   Area - used to define groups of turfs
    -   Turf - represents a single cell on the map. Everything on the turf could be said to belong to the turf.
    -   Obj - used to define things that aren't turfs, areas, or mobs
    -   Mob - used to define mobile objects.

Everything in the game is derived from those 4 main objects. 

Here is an example from Fulp's Wiki page, its still relevant here as its general explanation:

Let's talk about some of my own code:

```plaintext
/obj/effect/spawner/random_mob
  icon = 'fulp_modules/mob_spawners/icons/landmark_static.dmi'
  icon_state = "exclamation"
  name = "custom mob spawner"
  var/list/valid_mobs

/obj/effect/spawner/random_mob/Initialize(mapload)
  ..()
  if(valid_mobs?.len)
    var/mobspawndata = pick_random_item_and_count(valid_mobs)
    if(mobspawndata)
      var/mobX = mobspawndata[1]
      for(var/i = 0, i < mobspawndata[2], i++)
        new mobX(loc)
  return INITIALIZE_HINT_QDEL

/obj/effect/spawner/random_mob/maintenance
  name = "maintenance mob spawner"
  valid_mobs = list(
      /mob/living/simple_animal/hostile/viscerator = list(1,2,4),
      /mob/living/simple_animal/cow = list(1,1,2),
      /mob/living/simple_animal/hostile/hivebot = list(1,1,3),
      /mob/living/simple_animal/hostile/skeleton = list(1,1,2),
      /mob/living/simple_animal/bot/medbot = list(1,1,1),
      /mob/living/simple_animal/crab = list(1,1,3),
      /mob/living/simple_animal/hostile/rat = list(1,1,2),
      /mob/living/simple_animal/chicken = list(1,1,3),
      /mob/living/simple_animal/hostile/killertomato = list(1,1,2)
    )
```

There's a lot going on here so lets take it one step at a time.

`/obj/effect/spawner/random_mob`  This means I am defining `random_mob`. It is a subtype of spawner, which is a subtype of effect, which is a subtype of object. This one line actually does a lot of work, because `random_mob` now has inherited the procedures and variables of its ancestors. In fact, lines 2-4 are actually just me overriding the defaults on the spawner object!  On line 8, `var/list/valid_mobs` , I am creating an empty list called valid mobs. I am leaving it empty on purpose because I wanted this object to be a skeleton that mostly defines variables and behaviors so that objects that inherit from it get access to those variables and behaviors. 

Lines 10-18 I am overriding the Initialize proc. This procedure gets called when something is made real in the game. What I defined on line one does not make it spawn - Initialize does that. 

`..()` is the king of overriding. This nifty 4 characters calls the proc of the same name on the parent object. In this case, it is calling the version of Initialize() defined in `spawner` . The engine will wait for that version to finish running before resuming. 

`    if(valid_mobs?.len)` . This basically means “If `valid_mobs`” exists and has a length (remember, `valid_mobs` is a list), we continue to the next line. If it does not exist, we skip to line 18. 

`        var/mobspawndata = pick_random_item_and_count(valid_mobs)` We define a variable called mobspawndata because we want to hold something for use later. var/mobspawndata is set to the return of `pick_random_item_and_count(valid_mobs)` , which is a proc that is defined elsewhere.  

Now is an excellent time to tell you my favorite feature of VS Code: Right click! By using Go To Definition, you can easily jump to where something is defined! This means you can view this weird proc and find out what it does yourself! So don't ask me. 

![Go to definition (F12)](https://wiki.fulp.gg/vscodegotodefinition.png)

De-spaghettify your life

I'm tired and don't feel like explaining the rest thoroughly so figure it out yourself. Basically the rest of the procedure is used to spawn X amount of Y monster which was picked by the proc. 

`/obj/effect/spawner/random_mob/maintenance` The definition of this object gives it a special name and a list. The list contains other mobs. Each mob in the list has its own list of 3 integers. Pick weight, minimum count, and maximum count. The proc randomly picks a single mob and an appropriate number for the mob.

Test often, commit often, and maybe you'll figure it out. Good luck.

Use git commit to tell git to hold onto your changes. Use git push to send them to github. Open github and open pull requests. ehhh thats all for today, figure it out lmao
        
# The Duke Themselves
<iframe src="https://player.twitch.tv/?channel=thedukeofook&parent=wiki.monkestation.com" frameborder="0" allowfullscreen="true" scrolling="no" height="378" width="620"></iframe>