---
title: Guide to Chemistry
description: Ho boy... be careful with this stuff or you might kill us all
published: true
date: 2023-09-24T07:09:09.234Z
tags: guides, medical, chemistry
editor: markdown
dateCreated: 2023-09-24T07:09:09.234Z
---

# Guide to Chemistry

This guide will primarily be useful for chemists but may come in handy to any player and especially traitors. See Chemical recipes for simplified step-by-step instructions on how to make complicated chemicals (sometimes outdated), and for info about using the dispenser's recipe recording function. For grenade making see Grenades. If you don't have a chem dispenser, see the Guide to Ghetto Chemistry. 

> Any discussion about purities or pH is not applicable as those features are disabled. Enjoy a chemistry experience that doesn't kill you as often. \:)
{.is-warning}


# Tools and Machinery

You have all sorts of chems here, and can make many things. You can make medicines, smoke, foam, flash powder, poisons, space lube, acid and much more. The limit on combinations is a limit that exists only in your creativity (and the game engine). Be sure to be careful though, as mixing the wrong chemicals can be bad for your health, and please make sure you know what a chemical does before you use it. Experiment at your own risk.

## Chemistry Dispensers

Chem dispensers can be upgraded to unlock more chemicals, allow for more precise macro usage, increased power recharge rate and higher power capacity. If you run out of power, you can disassemble the dispenser with screwdriver+crowbar and rebuild it by first putting the circuit board back, and then all other things but use a full power cell instead of the old one. Then screwdriver to finish. Or you can charge the machine with an inducer. 

## Reaction Chamber

The reaction chamber (previously known as the chem heater) provides all the tools needed to help you react your reactions. You can set your heat, dispense buffers and watch your reactions in real time. An unupgraded reaction chamber will let you know when a reaction is overheated by highlighting it in red. More buffer can be added to the chamber by putting in a beaker into the heater and pressing the draw all button next to the buffer volume display.

Some chemical reactions will require you to heat the reagents in a Reaction Chamber. Unless the recipes says otherwise, these reactions need you to heat the reagents above the required temperature in order to start the reaction. Some reactions can stop if they drop below their required temperature. Don't forget you can use droppers directly on reaction chambers to add/draw to/from as well! This machine will heat/cool a beaker to the desired temperature, slowing down the heating/cooling speed as it approaches the target temperature. If you don't risk making the chemical explode by overheating it (like with meth) you can just set it to a very high temperature to avoid this.

Due to a rounding bug you sometimes need to heat chems 1 degree higher than the recipe says.

## ChemMaster 3000

Separates, bottles, and makes pills/patches out of chemicals loaded inside. You can load pretty much any container - beakers, spray bottles, water bottles and so on.
Maximum size for dispensed bottles is 30u, patches 40u and pills 50u. Use a chemistry bag to quickly move large quantities of bottles, patches or pills.
Can be upgraded with bigger beakers to allow a bigger buffer. By default it contains two ordinary 50u beakers for a total buffer volume of 100u. 

## Portable Chemical Mixer

This item does NOT require an anomaly core anymore.

A portable device that fits into the belt slot, enabling you to store, mix and dispense chemicals on the go. Can be printed at the medical lathe.

CTRL + Left click will open or close the portable mixer. While open you can access it like any other bag, and fill it with up to 50 beakers and bottles. When closed you can do a simple Left click to open it's UI. While the portable mixer is closed it functions similar to a Chemistry Dispenser, allowing you to add and remove a single beaker which you can dispense into

### Tips for the Portable Chemical Mixer

- Unlike the chemistry bag the portable chemical mixer does not combine beakers of the same type into one single icon when accessing its contents. This makes it a superior option for beaker storage.
- All containers with the same, main chemical inside them, are represented as a single button in the UI. (e.g. a small beaker with 50u Inacusiate and a big beaker with 100u Inacusiate, are represented as 150u Inacusiate (see image).
- A container with more than one chemical inside will be represented by the most dominant chemical in it. (Try to avoid adding beakers with more than one chemical in them, if you want to stay on the safe side)
- The portable chemical mixer is an excellent storage device for pure chemicals that you want to store until you need them in other recipes. Filling it with beakers of pure Oil, Phenol or Multiver means quick and easy access to them, whenever you need them in advanced chemicals.
- Tired of the floor in chemistry being littered with beakers? Put them in the portable chemical mixer.
- The botanist made you some Carpotoxin and filled it into condiment bottles? No need to carry them by hand, use the portable chemical mixer.
- The Janitor is too lazy to clean medbay? Put one beaker with Fluorosurfactant, one with Space Cleaner and one with Water in your portable chem mixer, position yourself and dispense them in equal amounts into a big beaker. Instant cleaner grenade action.
- The AI and bots are trying to kill you? Get some Uranium from the lathe, grind it, and put a beaker of it with a beaker of Iron into your portable chem mixer. Dispense both in equal amounts into a big beaker to cause an EMP.
- The doctors are too busy to help and the paramedic is too dead to help? Get yourself a health analyzer, fill your portable chem mixer with beakers of useful medicines (and/or cures and vaccines) and dispense the right dosages for people in need, anywhere on the station.

## High-performance liquid chromatography machine (HPLC)

Can detect impurity levels of reagents added to it, making it one of the best ways to detect purity of a reagent at roundstart.

The HPLC can also purify a reagent up to it's standard purity (usually 75%). This takes time and a bit of volume. Inverted reagents cannot be purified, though any reagent that is passed through the system will still cost time. While it's processing the Mass Spectroscopy cannot be used at the same time.

To use the HPLC left clicking will interact with the input beaker - so left clicking with a beaker will add it, alt click with a beaker in it will remove it. Right clicking with a beaker will add a beaker to the output slot, and alt right clicking will remove it. The machine needs both an input and output to purify - though can still analyse with just a single input.

The icon also indicates at what state it is at - a bar chart on the screen shows that it's analysing an input beaker, a sine wave shows that it's currently purifying and a blank screen indicates that it's input beaker is either empty or removed. 

## All-In-One Grinder

Grinds, crushes, liquefies and extracts reagents from materials placed into it.
If there is a significant reagent associated with the item, the Reagent grinder will distill a pure sample inside the collection beaker.
For example: Plasma/gold/uranium/metal sheets, donk pockets, fruits, dead mice. 

## Smoke Machine

Dispenses any chemical inside as a smoke cloud. Needs to be secured by wrenching first.
A great alternative to smoke grenades, but easily incites lynch mobs.
Can only be obtained through the circuit board being printed, and the required parts being assembled first.

## Plumbing

On some maps the chemists have access to a large empty area with plumbing tools. The available chemicals those can synthesize should be the same as with an unupgraded chem dispenser, but the workflow is more like a production line chem factory instead of instant dispensing. See the Guide to plumbing to learn more about this system. You may still have access to the pharmacy though, which has chem dispensers. 

# Metabolism

When a reagent enters a bloodstream it will start to "tick"(aka "cycle") about every 2 seconds. These are called "life ticks", and are not to be confused with server ticks/tickrate. When this happens the bloodstream is purged of an amount of every reagent usually equal to their listed metabolism rates. This is the rate at which the chemical disappears from your body. It doesn't matter how many chems you have in your body, as they are all metabolised separately. If you are hungry (sluggish), this will happen 20% slower, which makes chemicals have a bigger total effect since they last longer without being weaker per tick. Many mobs are "simplemobs" which means they don't have bloodstreams and thus cannot be poisoned, sedated or healed with medicine. Monkeys and most playable humanoids are the exceptions to this. 

# Addiction

Every time you metabolize a drug, you will gain addiction points in the category it belongs to. For every unit of drugs metabolized you receive addiction points. More extreme drugs and alcohol will give you more points. If you gain 600 points in addiction category, you will become addicted. By not taking said drugs you will lower the amount of addiction points. High sanity speeds up the process.

- You lose 0,5 points per tick with no withdrawal or stage 1 withdrawal.
- You lose 1 point per tick with stage 2 withdrawal.
- You lose 1,5 points per tick with stage 3 withdrawal.

When your mood is good you always lose 2 points per tick regardless of the stage. If you then fall below 400 points you stop being addicted. Taking more of the drug you're addicted to will temporarily suppress symptoms. Addiction stages advance from time in withdrawal. 

## Stimulants

Stimulant withdrawal makes you slow in a number of ways.

- At the first stage you get craving messages about feeling tired and needing a little pick me up. Your actions also become slower(action speed penalty).
- At the second stage you recieve a click cooldown penalty.
- At the third stage you get a movement speed penalty and more craving messages.
    
## Opiods

The main symptom of opiod withdrawal is nausea.

- At the first stage you get craving messages about feels aches in your body, chills and needing opioids. You start yawning intermittently.
- At the second stage your high blood pressure will increase rate of blood loss from any open wounds.
- At the third stage you will get hit by waves of nausea and vomiting.

## Alcohol

Alcohol withdrawal is easy to stave off due to the abundance of low alcohol content drinks available from the bar, but it is the only one that can be outright lethal.

- At the first stage you get craving messages about feeling thirsty, wondering if the bar is still open and needing a little Dutch courage. You also start to jitter.
- At the second stage you start to hallucinate.
- At the third stage you start to suffer intermittant seizures that paralyze you for 1-3 seconds and cause 10-30 brain damage depending on duration. Your seizures also cause heavy jittering. Seizures can be prevented by taking neurine or sodium thiopental.

## Hallucinogens

- At the first stage you get craving messages about feeling empty, spirtually detached and you start to wonder what the machine elves are up to.
- At the second stage you get visual disturbances.
- At the third stage you enter a hypnotic trance.

## Maintenance Drugs

- At the first stage you get craving messages, start growling intermittently and your health indicator will become unreliable.
- At the second stage you can only stomach GROSS food and you grow a scraggly beard if male.
- At the third stage you will become very dizzy and confused when exposed to light, but it also gives you night vision.

## Medicines

- You become unsure of your own health, are you aching, or is it just the down from the meds?
- You develop a fever.
- You organs begin to ache a bit too.

In general most pure medicines don't accrue addiction points – it’s instead the inverse or impure chems that will turn you into a hypochondriac. 

## Special

Some reagents have their own unique addiction type. Such as Nicotine.

# Active Pure Chemicals

A.K.A. what happens when you eat or splash these. Their metabolism rate is 0.4u per tick/cycle unless said otherwise. Unmentioned dispensable chemicals don't have any effects. Plasma and uranium require you to grind mineral sheets to acquire.

- Chlorine: Causes 1 brute damage per tick to a random body part.
- Copper: Can be splashed on metal sheets to create bronze sheets.
- Ethanol: A decent alcoholic "beverage", with a booze power of 65. Increases the speed of surgery procedures and flammability when applied externally. Metabolism rate 0.2.
- Fluorine: Causes 1 toxin damage per tick.
- Iron: Slowly restores blood volume.
- Lithium: Causes twitching, drooling, moaning and not being able to walk straight.
- Mercury: Causes 1 brain damage per tick, twitching, drooling, moaning and not being able to walk straight.
- Plasma: Causes 3 toxin damage per tick. Creates gas form plasma when spilled or heated to 323.15K (50°C). Not to be confused with Stable Plasma, which does nothing.
- Radium: Causes 2 toxin damage per tick. Creates glowing green goo on floor if more than 3u is spilled.
- Sugar: Gives nutrition. Causes hyperglycemic shock if overdosed (200u). Metabolism rate 0.8.
- Sulfuric Acid: Causes 1 toxin damage and some instant brute damage to one body part when ingested, and slightly more brute damage when injected. Destroys head-wear and causes burn damage when sprayed or splashed on someone. Counts as a toxin.
- Uranium: Causes 1 toxin damage per tick. Creates glowing green goo on floor if more than 3u is spilled.
- Water: Slightly generates blood volume. Additionally, freezes into ice below 274K.
- Welding Fuel: Causes 1 toxin damage per tick. Makes people flammable if splashed on. If splashed on the floor, makes a pool of fuel that can be ignited, which can ignite other pools around it.

## Catalysts

When a reagent in a recipe is marked "(catalyst)" it means it will not be consumed in the reaction. Some Catalysts are optional and are highlighted as such. These optional catalysts affect the ongoing reaction in certain ways. 

# Components

These are very basic chemicals that you'll use in a lot of other more complicated chems. They can still be toxic, though.

\[GUIDE SUSPENDED PENDING TABLES. THIS IS A HUGE PROBLEM.]