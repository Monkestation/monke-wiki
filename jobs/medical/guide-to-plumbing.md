---
title: Guide to Plumbing
description: No short italians here... try another station!
published: true
date: 2023-09-24T07:46:51.192Z
tags: chemistry, guides, medical
editor: markdown
dateCreated: 2023-09-24T07:46:51.192Z
---

# Guide to Plumbing

This guide will primarily be useful for chemists, or someone else willing to play with pipes.

In summary: Plumbing is the creation of factories to automate chemical production, for bulk amounts of ~~methamphetamine~~ healing chemicals. 

# The Basics

Plumbing is a system for the creation of ~~piss and shit~~ chemical factories. Plumbing is also an inaccurate name, since you'll be making chemical factories and not toilets.

The plumbing system is made up of three basic parts: A supplier, a duct network and a demander. A supplier supplies chems through a network of fluid ducts to a machine that demands that reagent. Component machines have connectors that duct networks will automatically connect to; red is mean so red ports take, blue is nice so blue ports give. A machine can be both a supplier and a demander. Machines next to each other can be connected without having ducts between them.

The maximum transfer amount is 10 units per 2 seconds. 

## Fluid Ducts

These can be found in stacks in autolathes and in the chemical laboratorium. Simply click them on a tile to place them down. You can click it in-hand to change the color and layer, and different colors and layers will not connect to one another automatically. You can force two different colors to connect by click dragging them to each other while holding a wrench. You can connect two different layers by using a pluming layer mantifold.

To pick up a placed duct and turn it back into an item, use a wrench on it.

### Physics

Plumbing physics might not be entirely as you expect. Due to pressure technology, there will never be any leftover in ducts. Thus, reagents transfer instantly from supplier to demander.

If a machine holds 5 water, 5 sugar and 5 mannitol and a machine requests 5 units, the requesting machine will receive 5 water for the first request. Normal chemistry would get you 1.66... water, 1.66... sugar and 1.66... mannitol. This might seem illogical, but it's necessary for ~~Floating Point Errors~~ advanced factories.

# Machinery

Most of the basic plumbing machinery is available through a specialized plumbing RCD, which can be found in the chemical lab or medical techfab. These machines can be deconstructed by welding. The ducting layer can be changed by using a layer-mode plunger on it (click in-hand and use alt to cycle through layers).

Remember, just because they aren't in the plumbing RCD doesn't mean they don't take chems. The smoker is one of those machines. Have fun. 

## Synthesizer

These buggers create the chemicals, much like normal chem dispensers. You select an amount (from 1u to 5u) and a reagent, and they'll create that every five seconds. They need a valid output to keep going, since the synthesizer only stores one dose. 

## Reaction Chamber

An unmissable tool to ensure purity is achieved and reactions are kept precise. Simply enter the chemicals and their amounts, and the reaction chamber will draw all the chems in in the set volumes (starting at the top). Extremely useful and basically a must have because otherwise your factory is gonna be too huge to fit on the station.

The yellow port takes acid buffer via the second duct layer and the green port takes basic buffer through the fourth duct layer. When the pH goes above what you set at Acid Threshold, it'll apply buffer until it reaches the threshold again. Ditto for the basic buffer. Note that the machine starts without buffers. Reaction Chambers also have a reaction volume. It'll keep the reagents in stasis until this threshold is reached, and when it's done reacting it'll empty out into whoever can receive it.

## Automated bufferer

Basically a cooler reaction chamber, apart from the fact it requires an insane amount of space and is inferior in every other way (except it makes cool beeps)

Very often you'll want to react three chems, where two of the chems are easily synthesizable and the third is not. The bufferer will allow you to 'wait' till all reagents are present. Simply make sure they are next to each other and then screwdriver them. If succesful, all connected chambers will briefly flash yellow. You can also set a threshold to when a bufferer is marked as 'ready' by right clicking one. If a bufferer does not have enough reagents, it will flash red; if a bufferer has enough reagents, but the other chambers do not, it'll flash yellow; if all bufferers are ready, they will flash green and start emptying until one goes below the threshold again. 

## Acclimator

The automated brother of the chemical heater. You simply give it a temperature and it will heat or cool its contents. You should set Allowed Temperature Difference to something aswell. It wont empty till it reaches the target temperature, wich takes extremely long if you want it precise. Setting Allowed Temperature Difference to 4 and target temperature to 379 means it will heat to 379 but start the emptying phase at 375.

The acclimator will not empty until all of its contents reach the desired temperature, which can be painfully slow if it's drawing new chems as it works, or attempting to reach an extreme temperature. To alleviate this, the Allowed Temperature Difference setting will allow the acclimater to release its contents within a certain range of temperature. For example, if the target temperature is 300k, and the ATD is 5, chems will start to be released once the machine reaches 295k or 305k.

The acclimator's holding capacity can also be manually lowered, to avoid the buildup of leftover chems. If you're heating chemicals that are deposited in batches of 3u, consider setting the capacity to a number divisible by 3.

Just like the reaction chamber, the acclimator cannot fill and drain simultaneously, to avoid leftover contaminants. 

## Chemical Grinder

Sucks grind-able plants placed on its tile and extract their reagents. Use a conveyor belt on the same tile or empty a plant bag unto it.

## Filter

A simple filter. Give it one or two chemicals, and those chems will be rerouted to the filter's side, allowing everything else to pass straight through. 

## Splitter

Got 15 of a reagent and only want 10? This cheap machine allows you to do just that. Set it to a 10 to 5 ratio and it will send 10 through and 5 left. 

## Disposer

The simplest machine of all, the disposer breaks down any and all chemicals that enter it into nothing. Use it to dispose of any leftovers you don't want in the system.

Note that chemical reactions can occur inside the disposer. 

## Chemical Press

This is where the fun begins. Choose a setting and it'll constantly pump out either pills, patches or bottles with whatever it's supplied with.

## Chemical Bottler

Puts reagents into containers, like bottles and beakers. The bottler takes empty containers on the side opposite its input direction and dispenses them towards its input direction (where the red pipe is). 

## Chemical Fermenter

Plumbing version of the fermentation barrel. Turns plants into various types of booze. 

## Tank

Technically not a machine, the tank simply holds up to 400u of any chemicals. 

## Input

Accepts manual chemical input. Pour something into it from a container to add something new to the system. 

## Output

Accepts manual chemical output. Simply grab a beaker and fill it up with whatever's in the network. 

## Liquid Pump

Can be wrenched to geysers in-order to extract chemicals. Does not need to be powered. 

## Chemical Beacon

Essentially a plumbing teleporter. Chemical Beacons send their reagents to a Chemical Recipient they've been connected with. To connect: Hit the Chemical Recipient with a multitool and then all subsequent Chemical Beacons with that same multitool. Multiple Chemical Beacons can be used with one Chemical Recipient. Note that the Chemical Recipient is bluespace tech and needs to be printed from the medlathe and constructed. Chemical Beacons do not need power, but Chemical Recipients do. Ideal for transporting geyser chems. 

## Automated IV Drip

A modified IV drip with plumbing connects. Reagents received from the connect are injected directly into their bloodstream. Blood that is drawn goes to the internal storage and then into the ducting. Draws on red mode and injects on blue mode, similarly to an ordinary IV drip. 

# Equipment

In addition to the machines, there are a few pieces of equipment available for chemists wanting to be plumbers. Including these and probably a few more I forgot. 

## Plumbing Constructor

The magical plumbing RCD. It can construct the basic plumbing machinery; click on it in hand to select what to build. It can also deconstruct plumbing machinery (but not ducts) by whacking it. Alt click to change the machines main ducting layer.

The plumbing constructor requires matter units to function. If it runs dry, simply add more sheets of metal or glass. You can see how many matter units are left in the Plumbing Constructor my examining it.

Can also be constructed in a medical techfab. 

## Plunger

All of the basic plumbing machinery can be plungered to empty their contents on the floor; simply use the plunger on them to flush them clean. Can be very useful if you got some machines that need to be emptied quickly, or for solving clogs. Can be printed in the medical and engineering lathe.

You can use the plunger in-hand to toggle to layer mode. You can now select a layer with alt and turn machinery to that layer.

# Geysers

Scattered around lavaland are geysers, a limitless source of chemicals. Luckily miners can scan these for mining points, at which point they will become visible on a GPS and easily trackable for you.

Geysers are active by default, and you can give them a taste-test with a beaker if you so desire

Each geyser produces a single chemical. Current loot table: 
- Wittel geyser: 16% chance. Wittel doesn't do anything, but can make chems so powerful you can turn the station into uranium or make 400hp super zombies 
- Random geyser: 5% chance. Works like botanies strange seeds or the pills in maint. Can have anything, from beer to plasmaman mutation toxin 
- Plasma-oxide: 26% chance. Useful for certain stabilizers in bomb-making 
- Protozine: 26% chance. A weak variant of omnizine. Works in strange reagent crafting 
- Hollow water: 26% chance. Reacts with holy water to make more holy water (yes you can make infinite strange reagent with geysers).

# Tips for your Industrial Revolution

- Resist the urge to crank every single synthesizer to 5u. Many recipes require different amounts of each ingredient, such as a 1u/1u/3u mixture.
- Even if you aren't making reactions, reaction chambers are invaluable for being able to pull precise amounts of specific chems out of a network.
- If you're lazy, connecting a ton of tanks to one another from both ends can create an enormous buffer of basic chems that you can simply have reaction chambers pull from. Be careful of accidental reactions!
- A lazy way to avoid using buffers is to add a lot of chems to a reaction with the needed pH. If you've got a basic reaction that needs to be more acidic, just add a lot of hydrogen instead of acidic buffer. Useful for when making a buffer factory isn't worth it for small scale projects
- Plumbing constructions that make Atmospheric Chemical smoke like CO2 smoke, N2O smoke, Oxygen smoke or unstabilized phlogiston reactions can be used for making more valuable gasses with nothing but a box of iron walls with one reinforced Plasma-glass window or as a ghetto Gas Miner since atmos chemicals release trace amounts of gas when spilled, "spilling atmos chems" also includes making a Atmospheric Chemical foam or smoke factory.

# The Duke Themselves
<iframe src="https://player.twitch.tv/?channel=thedukeofook&parent=wiki.monkestation.com" frameborder="0" allowfullscreen="true" scrolling="no" height="378" width="620"></iframe>