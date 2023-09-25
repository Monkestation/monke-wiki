---
title: Guide to Telecommunications
description: New headset, who dis?
published: true
date: 2023-09-25T16:45:26.416Z
tags: engineering, guides
editor: markdown
dateCreated: 2023-09-25T16:45:26.416Z
---

# Guide to Telecommunications

# Easy Guide to Fixing Telecomms

The radio stopped working all of a sudden? Or did someone just blow up the tcomms again? Here's a quick checklist-guide to see what's wrong and how to fix it:

Has it been partly blown up?
- Ensure that the room APC has power.
- See which of these machine/machines are missing/blown up: Receiver, Bus, Processor, Broadcaster.
- Reset one of each machines, which are still functional, with a multitool (unlink and remove all frequencies).
- Go to Can We Fix It, build the missing machines and link them by following instructions.
            (For example, if everything except the SMES, APC, Receiver and Bus has been destroyed, you still need a Processor and a Broadcaster. Reset the Receiver and Bus, construct Processor and Broadcaster, link them to the Bus and voíla.)
Completely blown to shit or stolen and thrown into the singulo?
- Go to Can We Fix It and follow instructions.
Everything intact but machines are off (no pretty flashing lights on the machines)?
- Was there a Central Command Update for something like "Ionospheric anomalies detected. Temporary telec#MCi46:5.;@63-BZZZZT", if so, wait a few minutes and equipment will come back online automatically. Note that this can happen without sending you any kind of warning, so just wait 5 minutes if nothing else works to see if the machines come back alive on their own.
- Check APC: Main breaker and equipment should be on. If not, turn them back on.
- Check equipment with a multitool and see if Power is set to on? If no, turn back on.
Equipment is on, but still nothing heard through radio?
- Check Telecommunication Hub with a multitool.
- Network name set to tcommsat? If no, set it back to tcommsat and...
- Go down the Telecommunication Hub's menu until you see MULTITOOL BUFFER.
- Click [Add Machine], the Hub's info is now inside your multitool's memory.
- Use multitool on a Subspace Receiver (for example, you will have to do this for every machine anyway).
- Scroll down the menu and click [Link] to link the machine back to the Hub.
- Repeat this for every machine (except processors, smes, blackbox recorder, messaging server, and computers).
  Processor must be connected to the corresponding bus
Check other devices that they have power on and correct network name.
- Go to Telecommunications Traffic Control Console.
- Log in.
- Scan for servers.
- Click on a server.
- Go back to main menu and repeat steps for all servers.

# Quick Guide to Telecommunications

If you just want to know how to fix everything incredibly easy, skip to Can We Fix It?.

The room:

Full of supercooled gas. Don't breathe it, don't stand in it without internals. It has its own SMES and APC. If the APC is destroyed, replace it immediately. If the APC has power temporarily cut, look at the PDA server; if its light is red, the APC probably has a remote signaller in it, because killing APC power turns off the PDA messaging server indefinitely.

## The tools

All machines are accessed and controlled by a multitool. One is in telecomms at the round start. To link machines, you add a machine to the multitool buffer then use the multitool on the machine to link to and hit \[Link] at the bottom. Most telecomms machines will also have FILTERS to determine which frequencies are sent through which pieces of machinery. Additionally, each machine has an IDENTIFICATION STRING, which is just its unique name, and a NETWORK, defaulted to tcommsat, which allows it to link to machines on the same network name only. IF YOU CHANGE THE NETWORK NAME IT'LL UNLINK EVERYTHING. CHANGING THE HUB'S NETWORK NAME IS A COMMON METHOD OF GHETTO SABOTAGE. WATCH FOR IT. 

## The machines

- Subspace Receiver: Intakes ;Radio signals
- Subspace Broadcaster: Sends ;Radio signals
- Bus Mainframe: Regulates ;Radio signals
- Processor: Decodes ;Radio signals
- Servers: Log ;Radio signals
- Hub: Takes in ;Radio signals and sends them to appropriate machines.
- Relay: Connected to a Hub on another Z-level. Allows ;Radio signals on its Z level to be run through the telecomms infrastructure of its linked hub.

## Standard Structure

Each step is sent through the HUB typically

- Signal goes from headset/intercom/etc
- to a RECEIVER
- Signal is sent to the appropriate BUS MAINFRAME
- Signal is sent to the bus's corresponding PROCESSOR. Note that THE PROCESSOR AND BUS MUST BE DIRECTLY CONNECTED
- Signal is returned to the BUS MAINFRAME
- Signal is logged at the SERVER and has scripts applied
- Signal is sent to the BROADCASTER
- Signal is sent to all appropriate radio devices


Parts that are not optional:

- Subspace Receiver
- Subspace Broadcaster
- Bus Mainframe


Parts that are functionally non-optional:

- Processor. Why? You get this otherwise:

\>/;v**r; \[145.9] says, "*ok at a;<th$>/e >$s>*v p*is#$*& ot**ng tr#nsl%/****"

Selene Avery says, "Look at all these massive penises not being translated."

# Can We Fix It?

**NOW TO IGNORE EVERYTHING ABOVE AND TELL YOU HOW TO FIX TELECOMMS INCREDIBLY EASILY NO MATTER WHAT'S DONE TO IT.**

Tools you need:

- Screwdriver
- Wrench
- Wirecutters
- Crowbar

**Total list of items you need (NOTE: most of these items can be found in the Technical Storage, but not enough to build everything from scratch, if you're doing exactly that, we suggest deconstructing any telecommunication-machines that are left over from the explosion or whatever, if that's not an option, go bug R&D to make you items):**

- 1x Subspace Receiver Board, 1x Bus Mainframe Board, 1x Processor Unit Board, 1x Subspace Broadcaster Board
- 1x Cable Coil
- 9x Micro Manipulators (only 4 in Tech Storage!)
- 1x Scanning Module (none in Tech Storage!)
- 3x High-Power Micro Laser
- 4x Hyperwave Filter
- 3x Subspace Ansible
- 1x Ansible Crystal
- 1x Subspace Wavelength Analyzer
- 1x Subspace Amplifier

Machines you need to build:

- Subspace Receiver
- Bus Mainframe
- Processor Unit
- Subspace Broadcaster

These can be done in any room/hallway with a powered APC, including a bombed-out telecomms room or anywhere else.

After building:

- Clear ANY frequency filters on the machines.
- Set network to tcommsat on every machine. This will unlink machines so do it before the next step.
- Add the Bus Mainframe to your multitool buffer (down on the list, click "Multitool Buffer")
- Link it to the Broadcaster, Processor, and Receiver (click "Add Machine").

That's it. You're done. It'll process all telecomms signals with very minor lag, but no static or other loss of functionality. Note that to receive and send messages across z-levels, you'll also need to have a hub and relays.

To add a hub and relays, first link the hub to all relays. Then, link the hub to the receiver, the bus, and the broadcaster. Now the miners can finally hear the station from lavaland.

# A More Elaborate Guide to Telecommunications
## The Central Compartment

A functional telecommunication central compartment (otherwise known as the "Server Room") contains several machines, each with its own isolated function. These machines make up a usually independent telecommunication network, with a pre-specified array of frequencies to process. Optionally, monitoring computers may be used to keep track of telecommunication activity and network integrity. It is important to notice that the machines, most dominantly the Processor Units, generate a significant amount of heat. The central compartment is generally kept at a very low temperature to prevent the damage of the hardware infrastructure, so maintenance is usually not done without proper protective equipment.

A central communications compartment is not necessary for a functional telecommunications network. In fact, it may be more efficient to separate the network into sub-nets. Nanotrasen Tech Department, however, strongly suggests the centralization of the machinery for easier maintenance and bookkeeping. While a strong central compartment may be easier to maintain, it is also easier to sabotage or blow up. The only thing worse than explosive concussion damage and massive atmospheric de-stabilization is a downed communication grid. A central compartment should be well-fortified and stable, and fortunately for the crew, Nanotrasen cannot pinch for pennies in this department. The station will either receive a robust Communications Satellite or inner-station Server Room. 

## The Machines

There are 5 different kinds of machines essential for a healthy telecommunication network. Without one or the other, the entire system would cease to function or would not function optimally. All telecommunication machines idle until they receive a signal, and all the machines are built with Hyperwave Filtering modules that allow for the scanning of signal's frequency regardless of intensity. This means each machine can selectively choose which signals to pay attention to, if there are any specified frequencies to tune into.

### Subspace Receivers

Subspace Receivers are essential to a subspace telecommunication network. They have a long-term subspace window open at all times, and create the subspace-equivalent of a gravity well in its warped version of space-time. FTL signals traveling in subspace are going too "fast" to be sucked into the gravity well, but a carbon copy of the signal is produced whenever a signal passes through the pocket. This signal is then converted into a real radio wave by the Subspace Receiver and passed onto either linked hubs or linked buses, with hubs having priority. In a typical scenario only the hub would receive the signal.

### Telecommunication Relays

Telecommunication Relays are very essential creating a full network. They allow the network to expand by being able to send signals past Z levels. Meaning that when saying something in the radio, after the message is received by the relay, it will be transmitted to all linked relays. It works by charging atoms for an almost faster than light signal. It then gets send to the hub (if the hub is linked to a receiver), the only combination of machines that can receive these almost-light speed signals, and then sends them to a Bus Mainframe.

### Telecommunication Hub

Telecommunication Hub is the main junction for the network. It is connected to many relays that are scattered along space, waiting to send and receive information to and from buses, relays, and broadcasters. It uses a high level technology of circuits to send information as efficiently and as fast as possible.

### Bus Mainframes

Bus Mainframes regulate and handle the transfer of massive quantities of data at near instantaneous speeds. They are not essential to a network, but are required to keep data transfer instant. They are necessary to transfer data back and forth between processor units and servers. If a Bus Mainframe is missing, network output may be unreliable or slow.

### Processor Units

Processor Units decrypt, clean and stretch hyper-compressed radio signals. Radio signals are sent into subspace using a preset encryption hash but random seed, which makes the process of encrypting and sending very light but unpacking and decrypting heavy due to the weird nature of subspace. Processor Units can instantly make signals readable by other machines. They are not essential to a subspace network but if one is missing, network output may not be understandable.

### Telecommunication Servers

Telecommunication Servers log network statistics and signal traffic for easy maintenance. Each server represents a "channel" in the Nanotrasen default settings. They can listen in to multiple channels, however. For each signal that is sent to a server, a database entry is created and the signal's information is stored. The servers also help by sorting the order in which signals are transferred to subspace broadcasters, which is vital for instantaneous signal transferring.

Additionally, Telecommunication Servers were capable of running user-written scripts (removed from /tg/-servers in 2015) through use of a Telecommunications Traffic Monitor. When a signal passes through a server (and the server is set to automatically execute code), the interpreter halts the signal until the code has finished executing, then releases the signal. During this time, the server's script interpreter can modify the signal's contents or flag it as a rejected signal, which will cause broadcasters to ignore it.

### Subspace Broadcasters

Subspace Broadcasters are impressive pieces of hardware that are capable of opening large enough subspace windows to transfer de-compressed data bursts, in encoded radio waves, through. They are necessary for any network that is expected to output information back to receiving radio devices. They operate by directing high-powered lasers into a small subspace window and fluctuating the amplitude of radio waves through subspace, allowing the large data packets easier entering and exiting of subspace.

### Messaging Servers

Messaging Servers process and route PDA and request console messages. Takes 15 minutes of calibration before it works if newly constructed.
Use a multitool to configure its settings and link it to the (tcommsat) network and hub. If there is no active messaging server, PDA and request console messages won't work.

### Blackbox Recorder

Only used for keeping The Blackbox theft objective.

## Maintenance Guide

Telecommunications machines are flexible and can adapt to structure changes, and they are otherwise immortal to mundane errors and crashes. However, in the event of a catastrophe such as an explosion, singularity, or anything of the like the default warranty becomes void and the machines will probably be destroyed or totaled. If one or more machines are destroyed, chances are the entire communication grid or at least part of it will be down. While intercoms and station bounced radios are capable of limited non-subspace communication it is most definitely not reliable. It should be maximum priority to get those machines up again.

If you suspect the machines aren't working properly (or at all), you should identify the cause first. Probably the most common issue is an exploded central compartment. Repair any structural damage and assess the machines. If they're still on (flashing/blinking lights, etc) then they are relatively functional. If there's been some atmospheric depressurization you're going to want to pump supercooled air into room; the machines need cold gas to survive or they will not be able to diffuse their heat into the environment, and will overheat.

If the machines have been overheated, you can fix them by simply reconstructing them. To do this, first unfasten the exterior bolts with a screwdriver. Next, dislodge the plating with a wrench. Next, remove the internal cables with some wirecutters. After that, you can use a crowbar to remove the internal components and circuit board. From there, you can either deconstruct the empty frame or simply rebuild it. If the machines have been completely destroyed, you're going to want to build more. You're going to have to bug R&D for some really high-tier circuit boards and stock parts, or salvage some parts from other toasted telecomm machines. Keep in mind, you don't have to reconstruct ALL the machines. At the very minimum you need 1 receiver, 1 processor, 1 bus, and 1 broadcaster. You might have to manually reconnect to relays if they are destroyed, this involves a long walk. 

# Telecommunication Polymorphism

The machines can be retrofitted manually to work with other machines that normally would not be very common or wise. In the case of an emergency, however, it can be a life-saver. You can use a multitool to interface with telecommunication machines, which will allow you to modify some of the machines' properties. You can also link together machines with this interface, which is possibly the most important function.

In order to link two machines, access one of them with your multitool. Select \[Add Machine] at the bottom of the window to store this machine in the buffer of the multitool. Now access the other machine with the same multitool. The machine previously buffered should still be in the buffer of the multitool. Select \[Link] to add the machine currently buffered to the list of machine links of the machine currently accessed. This will establish a link between these two machines. (Note that it is possible to link a machine to itself; this is both harmless and pointless.)

## Subspace Receiver

You can link Subspace Receivers to either Buses or Hubs. If you want to send signals across z-levels, you'll need to link it to a hub that's linked to a relay. Otherwise, you can link it to a bus with no loss of functionality.

### Bus Mainframes

While it is technically optional, if you do not link the bus to a Processor Unit, signals' readability will suffer substantially. Linking to a processor is all but necessary.

You can link Bus Mainframes to the hub or directly to Subspace Broadcasters if you are unable to link to a functional server. Note that if you link directly to the broadcaster, relays connected to the hub won't be used and other z-levels won't receive the signal. Otherwise, this will not have much of an effect besides a very minuscule performance decrease.

### Processor Units

According to the code, you can link Processor Units to Telecommunication Servers instead of Bus Mainframes. This will naturally have a significant performance cost. However, since processors must be linked to buses to receive the information in the first place, using this feature isn't actually possible.
Telecommunication Relay

Relays must be connected to a Hub in order to add information to the signal about the Z level it is in, and which will broadcast in. It cannot be linked to any other machine usefully.
Telecommunication Hub

This machine is essential when creating relays that allow you to send the same signal to different Z-levels. It is ordinarily connected to relays, receivers, buses, servers, and broadcasters. When it receives information from relays it sends it to linked receivers, and those receivers send it to the hub, and then the hub sends it to all linked buses. If the hub receives information from a machine that isn't a receiver (either the bus or a server), it assumes it's ready-to-transmit data and then sends it to all linked relays and broadcasters. Note that unlike receivers, you don't need a broadcaster to send data to relays on other z-levels.

### Telecommunication Servers

These can either be linked directly to a broadcaster or to a hub. They must be linked to the hub in order to broadcast information to relays on other z-levels, but otherwise there's no benefit. Servers are only needed to store logs and maintain sane bookkeeping.

### Subspace Broadcasters

Broadcasters are the output, there is nothing you can do with these in terms of polymorphism.

# Being An Ass

Now downing the radio may seem like something the captain does when he stubs his toe too hard, but downing the radios is something even the most clueless trouble maker can do, provided they have the tools. Here are some easy ways to make nobody hear the screams of the station's inhabitants.

- Destroy the sub-space broadcaster. Those screams will be uttered, But not heard.

- Deconstruct the processor. This makes the radio blast gibberish that nobody can comprehend.

- Deconstruct the server and it's bus. Depending on which ones you knock out you can disable most of the command channels and such.

- Add Filtered Frequencies to the Hub in order to only allow people to speak on those frequencies. You can do this on any machine and department channels will also suffer from not being able to pass the filter.

# The Duke Themselves
<iframe src="https://player.twitch.tv/?channel=thedukeofook&parent=wiki.monkestation.com" frameborder="0" allowfullscreen="true" scrolling="no" height="378" width="620"></iframe>