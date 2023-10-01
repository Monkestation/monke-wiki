---
title: Guide to Circuits
description: Crazy Science Stuff
published: true
date: 2023-10-01T21:02:20.910Z
tags: guides, science, circuits
editor: markdown
dateCreated: 2023-10-01T21:02:20.910Z
---

# Guide to Circuits
Circuits are a way to automate different actions extensively and easily! You can make a circuit that opens a door when you say a secret code to it, or a circuit that follows anyone you want while yelling obscenities at them, or well, anything really! Before starting to code with circuits, you'll need a few things: 

# Necessary Items

## Integrated Circuit

The integrated circuit is the foundation for all circuits. Your entire build will we based around this little guy. However, it can't work by itself.

First and foremost, it requires power, which you can provide to it via a Power Cell. Once you're sure that the power cell you're gonna use is charged, just use it on the integrated circuit. If you ever want to change the power cell or take it out for charging, you may take out by using a Screwdriver tool.png Screwdriver on it. Some shells can be anchored. These shells will take power from nearby APCs instead of their power cells.

Power cells drain whenever a component activates. By clicking the little i on a component you can see how much power each activation uses. If you don't know what I'm talking about, keep reading.

You can interface with this circuit by simply using it in your hand, however, there is not much you can do with it. Once you have a powercell you may place your integrated circuit into a Shell. 

# Shell

The shell will make it possible for you to add components to the integrated circuit, it'll let you access the circuitry, and it'll add input options so that you can interface with your circuit.

Depending on the shell, you might need to use a Screwdriver on it to assemble it before you're able to use the Integrated Circuit on said shell to add it.

If you ever want to remove the Integrated Circuit from it, just use a Screwdriver tool.png Screwdriver on it.

Different shells have varying size. Size represents how many components you're able to place inside a shell. There are four sizes:

- Small: Allows up to 25 components
- Medium: Allows up to 50 components
- Large: Allows up to 100 components
- Very large: Allows up to 500 components

There are many kinds of circuits, each with their special features: (If you're confused by what "output signals" or "entities" are, go down to Signal types)

| Name | Description | Size       | Required Research          | Requires assembly  |
|------|-------------|------------|----------------------------|--------------------|
| Compact Remote | The simplest handheld shell out there. Has one output signal that activates when you #### use it on your hand. | Small      | None | No |
| Assembly | A shell you can attach to components such as signalers, proximity  sensors, timers, valves, igniters, wires and more. To put it into attach mode, Right-Click it with a screwdriver. | Small | Advanced Shell Research    | Yes and No         |
| Bot | The simplest stationary shell. Has one output signal that activates when you use it. | Large      | Advanced Shell Research    | Yes                |
| Controller | Another handheld shell like the Compact Remote, but unlike the Compact Remote this one has multiple buttons: Use it on your hand to activate the primary button (Known as "Signal" in the circuit), Alt-Click it on your hand to activate the alternative button, and Right click it on your hand to activate the extra button. | Medium | Advanced Shell Research    | No |
| Dispenser | A stationary shell that is able to take and dispense items. Its  outputs signals tell you what Items it has in it as a list, what was the  last Item that was added, and two triggers for when an item is added  and removed. To dispense an item click the plus button on the top right  of the window, you'll see a "Vend" window pop up, from there you can  choose what entity you want to dispense, and when you trigger "Vend  Item" the item will be dispensed. To put items inside it just click it with the item in your hand. | Large      | Advanced Shell Research    | Yes |
| Airlock                  | A circuit-controllable airlock. To insert an integrated circuit.  Left-clicking people with an empty hand will Harm them if on, or Help them if off. Prevents you from switching places or being pushed when colliding with people is on or not.Left Click, to take it out simply use a # Screwdriver  on it. Has many input signals that let you open it, close it, bolt it,  and unbolt it. Also has output signals that notify you when said actions  are performed, plus two output numbers that return 1 or 0 if they're  closed/bolted depending on the output. Also returns the person who tried  to access the door as an entity. | Large      | Advanced Shell Research    | Yes                |
| Gun                      | A handheld shell that's actually a GUN. Has infinite bullets, and  returns both who shot the gun, what the bullet hit, and a trigger that  triggers when the gun is shot. | Medium     | Advanced Shell Research    | No                 |
| Money Bot                | Stationary like the Bot component, but allows taking and dispensing  credits! Has output signals that tell you when money has been inserted,  how much money has been inserted and how much money the machine has in  general. | Large      | Advanced Shell Research    | Yes                |
| Scanner Gate             | Very simple shell that returns any entity that walks through it. | Large      | Advanced Shell Research    | Yes                |
| Scanner                  | Another handheld shell. #### Use it on anything to output that thing as an entity. | Large      | Advanced Shell Research    | No                 |
| Brain-Computer Interface | Circuits, but in your BRAIN! For more information on Brain-Computer Interfaces (Also known as BCI), go here | Small      | Brain-Computer Interfaces  | Yes                |
| Drone                    | This little guy is able to move around just like you! Has many  signal inputs, with each representing each direction in which it can go. | Large      | Movable Shell Research     | Yes                |
| Server                   | Basically the same as the Bot shell, but bigger and better | Very large | Server Technology Research | Yes                |

You can also add circuits to a few items and use them as shells. These are:

| Name                                   | Description| Size   |
|----------------------------------------|---|--------|
| Camera                                 | Will let you take a picture by setting the target of the picture,  the coordinates of where the picture will be taken, and the size of the  picture.| Small  
| MOD Circuit Adapter module| A MOD suit module that lets you add circuits. To do so, you have to  add the circuit when the separated module is in your hand as if it were a  normal shell. To take it out use a screwdriver. Once its inside the MOD  suit, you cannot put components into the circuit, you can only put  components when you're holding the module on your hand. You can,  however, interface with the circuit by using the module from either the  MOD Interface Panel or the button in the top left. <br>When inserted into an active modsuit, it gives you a few options to  interact with it, like toggling the suit off and on, letting you change  the active module, tell you the active module, and return the wearer as  an entity output.   | Large  |
| Synthesizer, Headphones and Spacepods  | Let you choose an instrument, choose the sustain mode, insert a song  via a string (each item of the string being a new line), play the song,  stop the song, set how many times it should repeat, set the BPM, the  volume, the volume dropoff threshold, the note shift, the note sustain  value and the held note decay. <br>It also lets you know if its currently playing, when it starts playing and when it stops playing.  <br>You could use this to make a synchronized band of sorts.| |

Once you have a shell with an integrated circuit in it, you may access the circuit in it by using a Multitool on it, and you may also begin to add Circuit Components to your circuit. 

# Components
## Signal types

Every single thing in circuits revolves around these signal types. They send either information or triggers, which is the bases of circuits. There are 7 types of signals:

- Signal: Think of these as a pulse of electricity or a shockwave. They are NOT binary, when you activate one a chain reaction begins throughout the rest. Can easily be turned into numbers but you should only do so for checking whether its 0 or not, since the value itself makes no sense.
- Number: Any number your heart desires. Can also be used as a signal component, with any number above 0 activating a signal. You can also connect them to a string input.
- String: Any ascii character. If you try to write numbers in this, they will not be classified as numbers, so you can't do arithmetic equations with them.
- Entity: If you know DM, this is the equivalent to an atom. If you don't, then basically it can be any single item or living thing.
- List: Any of the above data types, joined into a single element. There different kinds of lists, each corresponding to each of the datatypes mentioned above. You access said data types by indexing the list. You cannot make a list of lists, that's what tables are for.
- Associative lists: In a normal list, the index can only be represented by a number, so Index 1 would be the first item. In an associative list, you can set a string of text as the index. So you could make a list with two items: one who's index is "Name" and it value is "Matt", and another who's index is "Last name" and who's value is "Damon". So if you use the Index Associative List component with the index set as "Name", it'll return "Matt".
- Table: A list of lists, usually used in databases such as the security arrests one. If a component provides a Table, you'll usually be able to see what each entry in said table is by clicking the information icon in the component.
- Any: Usually used in inputs, signifies that it can take any of the signal types above.
- Options: Changes what the component does, or what inputs it takes in. Can be changed with a string signal type.

## Variables

You might have noticed the cog icon on the top left of the Integrated Circuit window, this button will show a window on the bottom left of your screen that will let you change the variables from the circuit.

Variables are used to store data to use later in the circuit's programming. To add a variable simply choose an item from the list next to the plus icon, name it in the "Name" input field, then click the plus button. Clicking the button to the right of the plus button will simply add a list of the signal type selected.

Dragging from the pencil icon to the grid will create a variable setter wherever you let go of the mouse button, which will let you input data into the variable. You can't use setters on lists, there are special components for that (See List Add, List Clear, and List Remove below).

Dragging from the book icon to the grid will create a getter. You use this to retrieve the information stored in the variable. 

## Available Components

You might need to research specific things to unlock some of these components. 

| Name                      | Description |
|---------------------------|-------------|
| Access Checker            | Takes as an input the numerical list gotten from the Read ID Access  component. You can compare it with another numerical list via the  "Required Access" input, or by a more legible access chooser menu via  the card icon on the top right of the component. If you set the Check  Any input to 1, or if in the access chooser UI you change "Access  Required" to "One", it'll see if it has any of the accesses listed,  instead of making sure that it has all of them. |
| Arithmetic                | When triggered performs basic mathematical operations: Adding,  substracting, multiplying, getting the minimum and getting the maximum. |
| Binary Conversion         | Turns any number into a sequence of binary digits (which is a way of  represent numbers with only two digits- 1 and 0). For example, the  input "2" will output the following bits in the following order, from  top to bottom: "01000000". Good for obfuscating information or for usage  with AND, OR and XOR components. |
| Clock                     | When the input is any number above 0, it'll begin sending the output signal every 0.9 seconds. |
| Comparison                | When triggered checks two of the inputs to see if they're equal, not  equal, lesser than or bigger than the other. The Result output returns  either 0 or 1 depending on if the comparison is true or not. |
| Concatenation             | Combines up to four strings into one string. |
| Concatenate List          | Turns a list into a string by adding a specified separator between  the items. For example, we have a list that has two items, "Item1" and  "Item2". If we set the separator as "," then we get "Item1,Item2". If we  set the separator as " " (a space), we get "Item1 Item2". |
| Decimal Conversion        | Converts a binary sequence into a decimal number. For example: The  sequence of numbers "01000000" will return 2. Useful for translating  stuff made with the Binary Conversion component back into a normal  number. |
| Delay                     | When triggered, waits the specified amount of time in seconds, then triggers the output |
| Direction                 | When triggered, will output the direction towards the target entity  from the point of view of the shell as either a string or a signal. |
| Element Find              | When triggered, checks whether the inputted value is on the inputted list, and if so returns either true or false. |
| Filter List               | Loops through each item on the list, and if the "Next Index" output  signal connects to the "Accept Entry" input signal, then the value of  that element of the list will be saved to the "Filtered List" output.  The "Element" output string outputs the current element, "Index" outputs  the index of said element, "Next Index" is triggered when it's time to  check the next item in the list, "Filtered list" outputs the list with  the filtered items, "On Finished" triggers when the component has gone  through all the elements of the list and "On Failed" triggers when the  component fails. <br>Example: I have a list that has the following values:  "Item","Item","Clown","Item". I want to remove the "Clown" value from  the list while keeping the list format, so I use the Filter List  component. I set my string as the "List Input" value, and I connect the  "Element" output into a comparison component and I change the comparison  option to "=", and I type "Item" into the second input. I connect the  "Next Index" output into the "Compare" input, and the "True" output into  the "Accept Entry" input, then I trigger the "Trigger" input in the  Filter component. The component will then grab the first element in the  list, it being the word "Item", then send the "Next Index" component,  basically saying "I wanna go to the next item". Before it can move to  the next item, however, whatever's connected to "Next Index" must  finish, so the comparison input must do the comparison. We check whether  if the element is "Item", and yes, it is. So we send a "True" signal,  which connects to the "Accept Entry" signal input, which adds the  Element into the final Filtered List, then goes to the next element, it  being "Item" again, so the same thing will happen. When it gets to  "Clown", the Comparison component will return False, and because there's  nothing connected to the "False" output, the component ends there,  which means that "Accept Entry" is never triggered, so "Clown" is not  added to our final list. After all that we can check our output list,  and we'll see that it's "Item", "Item", "Item".   |
| For Each                  | Same as Filter List, but it does not output a list. Useful for  checking if a value is in a list if you do not know at what index that  value will be in. |
| Format List               | Takes in a list and a string, then takes said string and replaces  the set of characters "%n" with the respective number on the inputted  list (n being the position of the list item). <br>For example, let's say I have a string list that reads  "Bob","27","Unemployed". I set that as the list input, and in the string  input I write "Hello! My name is %1, I am %2 years old. I am currently  %3". When triggered, it'll output a string that will read "Hello! My  name is Bob, I am 27 years old. I am currently unemployed." |
| Format Associative List   | The same as the item above, but instead you have to use the names  linked with the different items in the list. For example: I have an  associative list that goes "\[Name, Bob], \[Age, 27], \[Job, Unemployed]". I  can in the string input type "%Name" and it'll return "Bob", or type  "%Age" and it'll return "27" and so on. |
| Get Column                | Gets the column of a table and returns it as a list. |
| GPS                       | When triggered, outputs the current position of the shell the Integrated Circuit is in |
| Health                    | When triggered, gets the health and damage amounts of the entity input. |
| Voice Activator           | Triggers itself whenever it can hear a message, may this message be  oral or through a radio. Returns information about said message and the  speaker. If the message comes from a radio, you wont be able to get who  said the original message. |
| ID Access reader          | If the entity input is an ID Card, returns all accesses on that ID  card as a list of numbers. To make sense of this list, use the Access  Checker component. |
| ID Getter                 | Takes an entity input. If said entity input has an ID card, it'll  output that ID card as the entity output.. The "Prioritize Hands" number  input can either be a 0 or a 1 for false or true. If True, it'll check  the ID the entity has in its hands first (if any) before checking  anywhere else. |
| ID Info Reader            | Takes an ID card as its entity input, and outputs all the info on said ID card. |
| Index                     | When triggered, indexes a list to get the value of an item in it.  For example, let's say you have a list with the following items: Item1,  Item2, Item3 and Item4. If you index the list by 1, you'll get "Item1"  as the output. |
| Index Associative List    | Indexes an associative list via the string index input. |
| Index Table               | When triggered, indexes a table to get the list located in the index you set as the input. |
| Length                    | When triggered, gets the length of an input. If the input is a list  or table, gets how many items it has. If it's a string, gets how many  characters it has. If it's a number, retunrs 0. |
| Light                     | Emits light. The "On" input will make the light turn on if the number is anything above 0, and it'll turn off if it is 0. |
| List Add                  | Adds an item to a list variable that you define from the circuit itself. |
| Associative List Literal  | Lets you create associative lists. Press the plus icon to add an  item to the list, and the minus icon to remove the last one in the list.  When triggered, joins the inputs into an associative list. |
| List Clear                | Removes every item from a list variable that you define from the circuit itself. |
| List Literal              | Lets you create lists. Press the plus icon to add an item to the  list, and the minus icon to remove the last one in the list. When  triggered, joins the inputs into a list. |
| List Remove               | Removes an item to a list variable that you define from the circuit itself. |
| Logic                     | When triggered, checks whether if: its inputs are all true (AND),  one of its inputs is true (OR), ONLY one of its inputs is true (XOR) |
| Material Scanner          | Takes any entity as its input and returns an associative list of the  amount of each material that the entity input is made out of. They are  indexed by the names of the material, so if you use it with an Index  Associative List component and you, for example, set the index as  "iron", it'll return how much iron is in the entity. For a list of  materials, check the materials section of the Guide to Construction. Make sure the index is all lower case. And "Metal" is referred to as "Iron". |
| MMI                       | Let's you add an MMI  to the Integrated Circuit. The "Message" and "Send Message" inputs let  you send the MMI inside the shell a message that only it can hear. The  outputs correspond to the keys in the player controlling the MMI's  brain's keyboard: North is Up/W, East is Right/D, South is Down/S, West  is Left/A, Attack is Left click and Secondary Attack is Right click. |
| Module                    | If you know programming, this is basically the equivalent of a  function. If you don't know programmming, think of it as an integrated  circuit inside an integrated circuit. Useful for making circuits look  way less messy. You can duplicate these using the Module Duplicator. |
| Multiplexer               | When triggered, checks to see if the number input is a number from 1  to 4, and if so, chooses the respective input of that number. For  example, If I type "Test1" in the "Input 1" Input, and "Test2" in the  "Input 2" Input, then change the value in the Input selector to 2, it'll  return "Test2". It's as confusing as it sounds. |
| Not                       | If it receives anything other than 0, outputs 0. If it receives exactly 0, outputs 1. |
| NTNet Receiver            | Recieves data sent through the NTNet network, if Tcomms is destroyed then tough luck. |
| NTNet Transmitter         | Transmits any kind of data through the NTNet network, if Tcomms is  destroyed then tough luck. Data can only be recieved by the NTNet  Receiver. |
| Proximity Pinpointer      | Returns the X, Y and Z co-ordinates of the entity input, but only if it's in view of the shell. |
| Pressure Sensor           | When triggered, outputs the atmospheric pressure of the exact tile in which the shell is at that time. |
| Printer                   | Prints a given string into a paper. It doesn't dispense the paper,  and it triggers once the input string is received. Once it has been  received you can get your paper by triggering the "Eject" input  signal.waw |
| Radio                     | Sends and receives frequencies from radios or other radio components. |
| Random                    | When triggered, outputs a random number between the minimum and maximum numbers you set as inputs. |
| Reagents Scanner          | Same thing as the Material Scanner, but for scanning the raegants inside beakers or other liquid containers. |
| Router                    | Copies the Input in the index you set in the Input Selector to the  output you set in the Output Selector. For example, If you put the Input  Selector to three, and the Output Selector to one, then you input a  string into "Input 3" that reads "Arse", then only "Output 1" will  output the string "Arse". |
| Select Query              | For use with USB cables. Gets you the table that matches the column  name and comparison input you provide it. For example: You connect it to  the security arrests console, and from the arrests database you want to  get the info of your friend, Mops-The-Floors. On the Input value, you  connect the database output. On the Column Name you type "Name", and on  the comparison input you type "Mops-The-Floors". It'll get you the table  who's "Name" value matches "Mops-The-Floors". From there you can index  it and get its arrest status, its crimes, etc. |
| Self                      | Returns the current shell as an entity. |
| Set Variable Trigger      | The same thing as the variable setter you get from the variable options tab, but it comes with input and output triggers. |
| Get species               | When triggered, returns the species of the entity input as a string. |
| Speech                    | When triggered, says what you inputted in the string input out loud. |
| Split                     | Splits a string by its separator, turning it into a list. For  example, you have a string that "Looks like this". By setting the string  input to that string, and its separator to a space (" "), you'll get a  list that "Looks", "like", "this" |
| String Contains           | When triggered, checks whether the string you set in the "needle"  input is in the string you set in the "haystack" input. For example, if  you put "in" as the needle, and "You are in my room" as the haystack,  it'll return true, since "in" is in the sentence "You are in my room". |
| Temperature Sensor        | When triggered, returns the current temperature in the tile the shell currently is in. |
| Textcase                  | When triggered, makes it so that its string input is either all in lowercase or all in UPPERCASE. |
| Timepiece                 | Outputs the current station time. "Time Format" will output the time  as XX:XX:XX, "Unit of Time" outputs time as specified in the "Unit of  time" input. For example, if the station time is 00:10:08, and you set  the unit of time input as "Minutes", then "Unit of Time"'s output will  be "10". |
| To Number                 | When triggered, converts a string that's only numbers into a number signal. |
| To String                 | When triggered, converts its output into a string component. If it's  output is an entity, it'll return the name of the entity. If the output  is a list or table, it'll return "/list". For actually turning a list  into a string, look at Concatenate List. |
| Trigonometry              | A component that has many trigonometric functions. That's as in-depth as I'll go since I hate math with a passion. |
| Typecast                  | If the input value is the Signal type you set in the options, returns the input value. If not, returns nothing. |
| Typecheck                 | When triggered, returns what Signal type the inputted signal is. |
| View Sensor               | When triggered, returns every single entity the shell can see as a list. Has a 1 second cooldown. |
| MOD Action                | Only compatible with the MOD Module Shell. When you use the mod  circuit adapter component with this component installed (whether via the  Mod Interface Panel or the icon on the top-left of your screen), you'll  see a radial menu with the icon you selected as the icon input as a  clickable button. Clicking this button triggers the output trigger. |
| Pathfinder                | When triggered, will calculate a path towards the X and Y  coordinates you set as inputs. Once calculated, will return a "step"  (aka where it has to go next to continue said path). If triggered again  when the shell arrived at the step, will output the next step, and so on  and so forth. If used with the Direction component, can be used to make  a Drone that moves by itself. |
| Pull                      | When triggered, will start pulling the entity input if its right besides it. Only works on Drone shells. |

# Machines and Items
## Machines
### Circuit Fabricator

Found on the Circuit Lab. Used for printing out Components, Integrated Circuits, Shells, USB-Cables, Circuit multitools and BCI Manipulation Chambers. If you left click the component printer with an integrated circuit, then you'll be able to directly add components to that integrated circuit by just pressing the "+" button on the top-left of your screen. Just drag and drop the components into your circuit. 

### Module duplicator

Duplicates both Module components and Integrated Circuits. Just name them (open the circuit/module, and on the top left you should see a "Name" input field), then left click the duplicator with either of those in your hand. After that click on the printer with an empty hand, and you'll be able to print the circuit/module.

## Items
### Circuit Multitool

Let's you mark entities, which can later be uploaded to entity inputs by clicking the arrow pointing up when you have a circuit multitool in your hand. Can also be used to see circuits by double clicking them with it, but a normal Multitool.png Multitool should do fine.
### USB Cables

Let's you connect a shell to a technological device. To do this, while you're grabbing the usb cable, click on the shell, then on the device you want to connect with. When you do this, you should get a new component on your shell. To disconnect, click the little "x" on the top right of the new component. You can only interface with a few select devices: 

