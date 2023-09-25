---
title: Guide to Gas Turbine
description: BIG JET ENGINE!
published: true
date: 2023-09-25T08:12:22.658Z
tags: engineering, guides
editor: markdown
dateCreated: 2023-09-25T08:12:22.658Z
---

# Gas Turbine

> Ported but *probably* out of date.
{.is-warning}


The gas turbine is an alternative way to produce power on the station, and is typically exclusive to Atmospheric Technicians. Unupgraded it is capable of producing upwards of 100 kW if set up correctly and may even produce more power with further upgrades and tinkering. Gas turbines require a lot of pressure to in order to run effectively. This can be accomplished by setting up a burn mix which will create a large amount of pressure when ignited. The burn chamber used for the gas turbine is also commonly used for creating fusion or bombs. 

# How To Set Up the Turbine

To make the gas turbine generate power, you need to create a burn mix and ignite it. This guide to is based on MetaStation on default setup Aug 2019 without changing any pipes. It's completely unoptimized and is only intended to produce power. This should work on any station with a pre-built turbine. 

## Tools you might need

- Rapid Pipe Dispenser or Pipe Dispenser
- Wrench
- Atmospheric Access
- Basic Atmospheric Knowledge
- A working crystallizer and crowbar if you plan on upgrading the turbine

# Preparing the burn mix
## What to do in atmospherics

Go to atmospherics.

- Max the O2 to Pure gas pump and turn it on.
- Max the Plasma to Pure gas pump and turn it on.
- Set the plasma mixer to node 1: 60%, and node 2: 40%. Max the output pressure and turn it on. This mixer should now be mixing 60% oxygen and 40% plasma (debatable mix, so feel free to experiment).
- Max all gas pumps that lead from the plasma mixer to the turbine. On MetaStation that's Pure to Ports, Port Mix to East Ports and Port to Fuel Pipe.

## What to do in incinerator room

Go to the incinerator room.

- Use the Incinerator Access Console to cycle to interior airlock. This will let you reach the two gas pumps in there.
- Max the two gas pumps leading into and out of the turbine burn chamber (the place with an igniter). Make sure they are on.
- Open up the air alarm on the wall. Click Scrubber Controls.
- You should see the settings for more than one scrubber. One of them is in the burn chamber, and the other is in the area you are standing in.
- To find out which one is in the burn chamber, hover with your mouse over the air scrubber in the burn chamber to see its name (probably Incinerator air scrubber #2 on MetaStation).
- In the air alarm, set that air scrubber to filter everything except oxygen, plasma and tritium. Set its range to Expanded.
- The output pipe leads to a gas filter. Turn it on. You can keep it on "nothing" unless you plan to harvest certain gases.
- Turn on the manual vault leading to space.

## Final preparations

Put on a hardsuit and go to space.

- Outside of the incinerator, max any gas pump (or better, replace with a straight pipe). Else it will clog and block the hot waste from entering space.
- Max the air injector in space, and make sure it's on.

Go back inside to the incinerator room.

- Use the gas turbine control computer. Click "on" to make power generation possible.
- Make sure any blast doors are closed, or they might vent the burn mix.
- Max the Fuel Pipe to Incinerator gas pump, and turn it on. The burn chamber should now start filling with plasma and oxygen.
- Click the combustion chamber ignition switch. The console should now show it generate power.
- Use the SMES. Max its target input. Output can either be maxed or set to slightly under input.

# Power Output

Without upgrades, the turbine should soon spin up to the max of 125000 RPM and generate power over 100kW. To get more power, you'll need to pry out the parts of the incinerator (Screwdriver + right click each part of the incinerator with a crowbar), then apply materials to upgrade each part by clicking on them with the materials in hand.

| Tier  | Compressor Part               | Rotor Part  | Stator Part               |
|-------|-------------------------------|-------------|---------------------------|
| 2     | 10 Plasteel Sheets each       |             | 15 Titanium Sheets        |
| 3     | 10 Titanium Sheets each       |             | 15 Metal Hydrogen Sheets  |
| 4     | 5 Metal Hydrogen Sheets each  |             | 10 Zaukerite Crystals     |

Then, print a bluespace RPED and stock parts from the engineering protolathe and use it to upgrade the SMES. At tier 4, it should now be able to produce around 800 kW power, until the oxygen or plasma runs out.

# The Duke Themselves
<iframe src="https://player.twitch.tv/?channel=thedukeofook&parent=wiki.monkestation.com" frameborder="0" allowfullscreen="true" scrolling="no" height="378" width="620"></iframe>
