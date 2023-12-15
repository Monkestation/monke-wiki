---
title: Guide to Nanites
description: Old stuff made new again!
published: true
date: 2023-12-15T00:38:16.770Z
tags: guides, nanites, science
editor: markdown
dateCreated: 2023-09-23T02:02:17.725Z
---

# Guide to Nanites
Nanites are tiny nanomachines that live in a host's bloodstream, providing different functionalities depending on how they're programmed. The mob where the nanites reside is usually defined as their host. 

# Research

Nanite programs are unlocked by researching their relative techweb nodes in the R&D Console. Anything past Basic Nanite Programming, however, will require Nanite research points. These are gained simply by having active hosts with nanites implanted; the more the merrier. However, non-sentient, non-humanoid, or dead hosts will incur heavy penalties to their research gain.

The Military research node is only available if the Illegal Technology node is unlocked, therefore requiring syndicate tech to be scanned first.
Hazard Nanite Programming is similarly locked behind Alien Technology, which requires Abductor technology to be scanned to unlock.

# Implanting

Nanite implantation can be done through the Nanite Chamber. A second person must operate the chamber from outside and begin the implanting process, at the end of which a new swarm will take root in the host.
The nanite chamber can edit nanites' Cloud ID, modify the Safety Threshold, or alternatively remove all nanites from a host.

Another easier method is to build a Public Nanite Chamber Nanite chamber.gif. Use a multitool on the Public Nanite Chamber circuit board first to choose which backup cloud you want it synced to. If you don't multitool the board it will default to cloud 1. Build the chamber using a machine frame. The public nanite chamber will automatically implant nanites into anyone who enters it, without the need for a second person. 

# Nanite Tools

There are currently three handheld tools that can be used to manage nanites. You can print them from the science protolathe after researching some basic nanites.

## Nanite Scanner

Use this to scan implanted people. It will give you a readout with information about current nanite volume. If a nanite swarm contains the "Nanite Debugging" utility program you will also see a list of currently installed nanite programs and their active/inactive status.

## Nanite Remote Control

A remote used for sending signals to implanted nanites. Change its settings and then click anywhere or on a target to activate it. For example you can set the code to be the trigger code you gave the "Host Scan" program. Using this in hand will open a menu. Settings:

- Signal Code: Which code you want it to signal.
- Signal Mode: Choose between "off" (makes remote do nothing), "local" (only signals the user), "targeted" (signals whoever you click directly on), "area" (signals anyone within your line of sight) and "relay" (signals any existing nanite programs that have a chosen "relay code").
- Save Current Setting: Lets you save current setting to a list, with a name of choice. Not saved between rounds.
- Lock Interface: Locks the settings. Alt-click the remote to unlock.

## Nanite Communication Remote

A remote used for sending custom messages on the fly to message-based programs, like Forced Speech. The settings are very similar to those of the Nanite Remote Control. The difference is you set a Comm Code and Message instead of Signal Code and Relay. The programs installed must have the same Comm Code to be able to signal them with this remote. 

# Volume

If wearing a diagnostic HUD Diag glasses.png you will be able to see a bar next to implanted people, which is a nanite volume meter. Nanites generally expend a part of their volume while their programs are active. Luckily, modern technology allows them to integrate with the host's metabolism to replicate without interfering with biological processes, causing them to have a slow but steady growth rate of 0.5 per second. Researching Harmonic Nanite Programming grants an additional passive volume generation of +0.1 per second.

Nanites by default have a safety threshold where they'll stop using nanite-consuming programs. This threshold can be customized in an individual by entering a nanite chamber, and having a second person operate the connected nanite chamber control console.If the swarm reaches a population of 0, there's none left to replicate, and the nanites are completely removed.

Nanite chambers provide the host with 100 nanites. Hosts have a maximum volume of 500 nanites. 

# Programming

Nanite swarms can contain nanite programs. These programs can have a huge variety of effects, and are loaded into a nanite swarm in two main ways: uploading them manually with a nanite chamber or by syncing them with a Cloud Backup. Once loaded programs cannot be directly modified; instead, a copy of the same program with the desired programming must be uploaded again to overwrite the previous one. There is no limit to the amount of loaded programs, but using too many at once will usually rapidly deplete the nanite population. 

# Cloud

Nanite swarms are usually set with a Cloud ID. If so, they will, every 30 seconds, copy the programming of the Cloud Backup with the same ID. Cloud backups are controlled by Cloud Control Consoles Nanite cloud controller.gif. They can create new backups (with codes from 1 to 100), as well as upload programs from a disk into the selected backup. Cloud control consoles also serve as storage, meaning that if they're destroyed all clouds connected to them will be destroyed, and the nanites will be unable to sync to them anymore. Cloud IDs are unique, meaning that if a console registers an ID, it cannot be used or accessed by other consoles until the original has been destroyed.

Nanites who aren't able to sync to a cloud will keep working, but they'll have a chance of encountering software errors every time they miss a synchronization, causing program deprogramming, deletion, or corruption into dangerous Glitch programs over time.

# Nanite Programs

Nanite programs determine what nanites do inside the host. They have different categories, and range from helpful to deadly.

## Obtaining programs

Programs are unlocked through techweb research. Once unlocked, they can be downloaded into Nanite Program Disks at a Nanite Program Hub Nanite program hub.png. 

## Customizing Programs

Programs have several parameters that can be customized with the use of a Nanite Programmer. Simply insert a program disk in the machine and set the parameters you prefer. Note that codes set to 0 are inactive and cannot be signaled.

- Activated: Determines if the program starts activated or not.
- Restart Timer: If set, automatically re-activates the program after X seconds whenever deactivated.
- Shutdown Timer: If set, automatically deactivates the program after X seconds whenever activated.
- Trigger Timer: (Only for triggered programs) If set, automatically triggers the program every X seconds, if possible.
- Trigger Delay: (Only for triggered programs) If set, delays trigger signals by X seconds.
- Activation Code: The code that must be signaled to activate the program.
- Deactivation Code: The code that must be signaled to deactivate the program.
- Trigger Code: If the program can be triggered, the code that must be signaled to trigger the program.
- Kill Code: The code that must be signaled to delete the program.

Some programs have a extra settings available for customization, like relay channels or signal codes.

## Signaling Programs

Nanite Remotes can send coded signals to nanites. When a nanite swarm receives a signal, all its programs react if they recognize the code.

Nanite Remotes can be set to four modes:

- Self targets the person who is holding the remote.
- Targeted targets only the mob that is being clicked on.
- Area targets all mobs in sight.
- Relay allows the user to choose a relay channel; the signal is then sent globally to all hosts which have a relay program set to that channel.

## Triggered Programs

Some programs do not have an effect over time, and instead must be triggered. To do so they can either receive a Trigger Code or set a Trigger Timer. Triggering a program generally has a cooldown as well as a cost in volume; if those requirements are not met the program won't trigger. If the program is not activated, it will also be unable to trigger, but activating the program is not the same as triggering it.

## Program Rules

Sensor programs can also be installed as Rules to other installed programs. When doing so, that program will only work or be triggered if it satisfies the conditions of the sensor program.

To install a Sensor program as a Rule, customize the sensor program in the Nanite Programmer, insert the disk in the Cloud Console, and press the Add Rule button on the program you want to install it on.

For example, installing a Health < 30% sensor to a Bio-Reconstruction program will allow you to only use that program when the host is severely harmed.

Note that rules are cumulative with Activation status: a Deactivated program will not work even if it satisfies the Rule condition, and an Activated program that does not meet the rule requirements won't work either.

## Data Corruption

Lack of constant cloud sync, as well as events like EMPs or shocks, can result in data corruption in nanite programs, which results in one of the following effects:

- Toggles the program, deactivating it if active and viceversa.
- Triggers the program, if it can be triggered
- Deletes the program completely
- Resets all the codes, preventing it from being signaled by remotes or signal programs.
- Converts the program into a corrupted version. The glitch program depends on the program that got corrupted.

Cloud Syncing generally prevents data corruption from being dangerous. Remaining unlinked from the cloud console (either because the console is missing, or because of manual unlinking from the chamber) means that nanites are subject to decay, leading to the nanites becoming ineffective at best, and very dangerous at worst.

## Nanite Program Types

Programs are split in several categories.

### Utility Programs

Programs that interact with the nanites themselves, or have general utility purposes. 

| Program                    | Effect | Volume per second  | Trigger Cost  | Trigger Cooldown  | Required Techweb  | Corruptions          |
|----------------------------|--------|--------------------|---------------|-------------------|-------------------|----------------------|
| Metabolic Synthesis        | The nanites use the metabolic cycle of the host to speed up their  replication rate, using their extra nutrition as fuel. The host must be  at least well fed. | +0.5               | --            | --                | Smart             | Toxin Buildup        |
| Distributed Computing      | The nanites aid the research servers by performing a portion of its  calculations, increasing research point generation by a flat amount for  each host currently running this program. Non-sentient hosts generate  only 25% of the research gain. | 0.2                | --            | --                | Basic             | Toxin Buildup        |
| Neural Network             | The nanites aid the research servers by cross-referencing data from  all their active hosts. Gives a research boost that becomes more  powerful for each host currently running this program, overtaking  Distributed Computing at 12 hosts. Non-sentient hosts generate only 25%  of the research gain and efficiency boost.  | 0.3                | --            | --                | Basic             | Toxin Buildup        |
| Viral Replica              | The nanites constantly send encrypted signals attempting to  forcefully copy their own programming into other nanite clusters. This  program will also forcefully set their cloud ID to 0 (disabled) or a  customized ID. | 0.5                | --            | --                | Military          | Toxin Buildup        |
| Monitoring                 | The nanites monitor the host's vitals and location, sending them to  the suit sensor network. Additionally adds a nanite HUD icon to medHUDs  looking at the host. | 0                  | --            | --                | Basic             | Toxin Buildup        |
| Host Scan                  | The nanites display a detailed readout of a body scan to the host  when triggered. Can pick between medical, chemical, or nanite scan. | --                 | 3             | 5s                | Neural            | Toxin Buildup        |
| Stealth                    | The nanites hide their activity from superficial scans, making them invisible to Diagnostic HUDs and immune to Viral programs. | 0.2                | --            | --                | Smart             | Toxin Buildup        |
| Nanite Debugging           | Enables various high-cost diagnostics in the nanites, making them able to communicate their program list to nanite scanners. Doing so uses some power, slightly decreasing their replication speed. | 0.1                | --            | --                | Basic             | Toxin Buildup        |
| Subdermal ID               | The nanites store the host's ID access rights in a subdermal  magnetic strip. Updates when triggered, copying the access of the host's  worn or pulled ID. | --                 | 0             | 5s                | Basic             | Dermalysis           |
| Dermal Button              | The nanites form a button on the host's arm, allowing them to  manually send a signal to the nanites when pressed. The button will  display in the host's action bar, and can be customized in name, icon  shape, color, and of course sent signal. The button cannot be pressed  while the host is incapacitated.             | --                 | 0             | --                | Mesh              | Glitch               |
| Relay                      | The nanites receive and relay long-range nanite signals. Must be set with a relay channel beforehand. | --                 | --            | --                | Basic             | Toxin Buildup        |
| Signal Repeater            | When triggered, sends another signal to the host, optionally with a delay. Useful to set up multiple codes for the same program. | --                 | --            | --                | Basic             | Toxin Buildup        |
| Relay Signal Repeater      | When triggered, sends a signal via relay, optionally with a delay. | --                 | --            | --                | Basic             | Toxin Buildup        |
| Infective Exo-Locomotion   | The nanites gain the ability to survive for brief periods outside of  the human body, as well as the ability to start new colonies without an  integration process; resulting in an extremely infective strain of  nanites.                                                                                                    | 1.5                | --            | --                | Hazard            | Hypoxemia, Necrosis  |
| Nanite Sting               | When triggered stings a random non-host around the host with a  barely-visible cluster of nanites, making them a new host. The target  will feel it. If the cluster finds no valid targets, it returns to the  original host, "refunding" the trigger cost. | --                 | 5             | 10s               | Military          | Glitch, Toxic        |
| Mitosis                    | The nanites gain the ability to self-replicate, using bluespace to  power the process, instead of using the host's metabolism. This rapidly  speeds up the replication rate, but it causes occasional software errors  due to faulty copies, making it very dangerous when used without a  cloud connection.                   | +0.5 to +5         | --            | --                | Hazard            | Toxic                |
| Electromagnetic Resonance  | The nanites cause an elctromagnetic pulse around the host when triggered. Will corrupt other nanite programs! | 0                  | 10            | 5s                | Mesh              | Toxin Buildup        |

### Protocols

Special programs that enhance nanite behaviour in one particular sector. Only one protocol of each category can function at the same time in a nanite cloud. These are unlocked through B.E.P.I.S. research. 

| Program                      | Effect | Volume per second                | Trigger Cost  | Trigger Cooldown  | Category     | Required Techweb              | Corruptions  |
|------------------------------|--------|---------------|-------------------|--------------|-------------------------------|--------------|
| Kickstart Protocol           | The nanites focus on early growth, heavily boosting replication rate for a few minutes after the initial implantation. | +3.5(for the first 120 seconds)  | --            | --                | Replication  | Nanite Replication Protocols  | Necrosis     |
| Factory Protocol             | The nanites build a factory matrix within the host, gradually  increasing replication speed over time. The factory decays if the  protocol is not active, and can be damaged by shocks or EMPs. | --                               | --            | --                | Replication  | Nanite Replication Protocols  | Necrosis     |
| Pyramid Protocol             | The nanites implement an alternate cooperative replication protocol  that is more efficient as long as the saturation level is above 80%. | +1.2(if volume above 80%)        | --            | --                | Replication  | Nanite Replication Protocols  | Necrosis     |
| Offline Production Protocol  | While the host is asleep or otherwise unconcious, the nanites exploit the reduced interference to replicate much faster. | +3(if asleep)                    | --            | --                | Replication  | Nanite Replication Protocols  | Necrosis     |
| Hive Protocol                | The nanites use a more efficient grid arrangment for volume storage, increasing maximum volume in a host by 250. | --                               | --            | --                | Storage      | Nanite Storage Protocols      | Necrosis     |
| Zip Protocol                 | The nanites are disassembled and compacted when unused, increasing  the maximum volume while in a host by 500. However, the process slows  down the replication rate slightly. | 0.2                              | --            | --                | Storage      | Nanite Storage Protocols      | Necrosis     |
| Free Range Protocol          | The nanites discard their default storage protocols in favour of a  cheaper and more organic approach. Reduces maximum volume by 250, but  increases the replication rate.                                                                                 | +0.5                             | --            | --                | Storage      | Nanite Storage Protocols      | Necrosis     |
| S.L.O. Protocol              | 'S.L.O.P.', or Storage Level Override Protocol, completely disables  the safety measures normally present in nanites, allowing them to reach  much higher saturation levels (1500 extra volume), but at the risk of  causing internal damage to the host.  | --                               | --            | --                | Storage      | Nanite Storage Protocols      | Necrosis     |

### Augmentation Programs

Augmentation programs offer boosts and bonuses to the host. 

| Program                    | Effect | Volume per second  | Trigger Cost  | Trigger Cooldown  | Required Techweb  | Corruptions                    |
|----------------------------|--------|--------------------|---------------|-------------------|-------------------|--------------------------------|
| Nerve Support              | The nanites act as a secondary nervous system, reducing the amount of time the host is stunned by half. | 1.5                | --            | --                | Neural            | Nerve Decay                    |
| Dermal Hardening           | The nanites form a mesh under the host's skin, protecting them from melee and bullet impacts. Adds 25 melee and 20 bullet armor. | 0.5                | --            | --                | Mesh              | Dermalysis                     |
| Dermal Refractive Surface  | The nanites form a membrane above the host's skin, reducing the  effect of laser and energy impacts. Adds 25 laser and 20 energy armor. | 0.5                | --            | --                | Mesh              | Dermalysis                     |
| Vein Repressurization      | Reduces bleeding rate by 50%. | 0.2                | --            | --                | Biological        | Hypoxemia                      |
| Electric Conduction        | The nanites act as a grounding rod for electric shocks, protecting the host. Shocks can still damage the nanites themselves. | 0.2                | --            | --                | Mesh              | Nerve Decay                    |
| Mental Barrier             | The nanites form a protective membrane around the host's brain,  shielding them from abnormal influences like a mindshield implant while  they're active.  | 0.4                | --            | --                | Synaptic          | Neuro-Necrosis, Brain Misfire  |

### Healing Programs

Healing programs fix a variety of damage and ailments that affect the host. They generally consume a lot of nanites, so it's advisable to activate them manually when necessary. 

| Program                       | Effect | Volume per second  | Trigger Cost  | Trigger Cooldown  | Required Techweb  | Corruptions                    |
|-------------------------------|--------|--------------------|---------------|-------------------|-------------------|--------------------------------|
| Accelerated Regeneration      | The nanites boost the host's natural regeneration, healing them slowly over time (0.5 brute and burn). Does not consume nanites while the host is undamaged. | 0.5                | --            | --                | Biological        | Necrosis                       |
| Temperature Adjustment        | The nanites adjust the host's internal temperature to an ideal  level. Does not consume nanites while the host is at an ideal  temperature. | 3.5                | --            | --                | Mesh              | Dermalysis                     |
| Blood Purification            | The nanites purge 1 toxin damage and 1u of all chemicals from the  host's bloodstream. Like most other programs it consumes nanites even if  it has no effect (change from Aug, 2020). | 1                  | --            | --                | Smart             | Hypoxemia, Necrosis            |
| Neural Regeneration           | The nanites fix neural connections in the host's brain, reversing  brain damage and minor traumas. Does not consume nanites if the host has  no brain damage. Heals 1 brain damage and has 10% chance to heal basic  level brain traumas. | 1.5                | --            | --                | Neural            | Neuro-Necrosis                 |
| Blood Regeneration            | The nanites stimulate and boost blood cell production in the host. Does not consume nanites if the host has enough blood. | 1                  | --            | --                | Biological        | Hypoxemia                      |
| Mechanical Repair             | The nanites fix damage in the host's mechanical limbs. Heals 1 brute  and burn spread across damaged limbs. Does not consume nanites if the  limbs are undamaged. | 0.5                | --            | --                | Basic             | Necrosis                       |
| Selective Blood Purification  | The nanites purge 1 toxin damage and 1u toxin  reagents from the host's bloodstream, while ignoring non-toxin  chemicals. The added processing power required to analyze the chemicals  severely increases the nanite consumption rate. | 2                  | --            | --                | Harmonic          | Hypoxemia, Necrosis            |
| Bio-Reconstruction            | The nanites manually repair and replace organic cells, acting much  faster than normal regeneration. However, this program cannot detect the  difference between harmed and unharmed, causing it to consume nanites  even if it has no effect. Heals 2 brute and burn damage. | 5.5                | --            | --                | Harmonic          | Hypoxemia, Necrosis            |
| Neural Reimaging              | The nanites are able to backup and restore the host's neural  connections, potentially replacing entire chunks of missing or damaged  brain matter. Heals 2 brain damage and has 10% chance to heal up to  lobotomy level brain traumas. | 3                  | --            | --                | Harmonic          | Neuro-Necrosis, Brain Misfire  |
| Defibrillation                | The nanites shock the host's heart when triggered, bringing them  back to life if the body can sustain it. The revive has the same  requirements to work as an ordinary defibrillation,  except the revive will not heal toxin or suffocation damage, and will  not deal any suffocation damage. This means the body must have under 180  total of all basic damage types + cellular. The ghost gets a message  and 8 seconds to re-enter their body after the trigger.  | --                 | 25            | 12s               | Harmonic          | Shocking                       |

### Glitch Programs

Defective programs caused by data corruption, and not otherwise obtainable. Generally range from mildly to moderately dangerous. Can stack. 

| Program         | Effect | Volume per second  | Trigger Cost  | Trigger Cooldown  | Required Techweb  | Corruptions     |
|-----------------|--------|--------------------|---------------|-------------------|-------------------|-----------------|
| Glitch          | A heavy software corruption that causes nanites to gradually break down.                           | 1.5                | --            | --                | --                | None            |
| Necrosis        | The nanites attack internal tissues indiscriminately, causing widespread damage.                   | 0.75               | --            | --                | --                | Glitch          |
| Toxin Buildup   | The nanites cause a slow but constant toxin buildup inside the host.                               | 0.25               | --            | --                | --                | Glitch          |
| Hypoxemia       | The nanites prevent the host's blood from absorbing oxygen efficiently.                            | 0.75               | --            | --                | --                | Glitch          |
| Neuro-Necrosis  | The nanites seek and attack brain cells, causing extensive neural damage to the host.              | 0.75               | --            | --                | --                | Necrosis        |
| Brain Misfire   | The nanites interfere with neural pathways, causing minor psychological disturbances.              | 0.5                | --            | --                | --                | Neuro-Necrosis  |
| Dermalysis      | The nanites attack skin cells, causing irritation, rashes, and minor damage.                       | 0.25               | --            | --                | --                | Necrosis        |
| Nerve Decay     | The nanites attack the host's nerves, causing lack of coordination and short bursts of paralysis.  | 1                  | --            | --                | --                | Necrosis        |

### Weaponized Programs

Aggressive programs which use nanites as a military-grade weapon. Moderately to extremely dangerous to the host and/or their surroundings. 

| Program                 | Effect | Volume per second  | Trigger Cost  | Trigger Cooldown  | Required Techweb  | Corruptions                        |
|-------------------------|--------|--------------------|---------------|-------------------|-------------------|------------------------------------|
| Cellular Breakdown      | The nanites destroy cellular structures in the host's body, causing brute damage. | 1.5                | --            | --                | Biological        | Necrosis                           |
| Poisoning               | The nanites deliver poisonous chemicals to the host's internal organs, causing toxin damage and vomiting. | 1.5                | --            | --                | Biological        | Toxin Buildup                      |
| Memory Leak             | This program invades the memory space used by other programs, causing frequent corruptions and errors. | 0                  | --            | --                | Smart             | Toxin Buildup                      |
| Aggressive Replication  | Nanites will consume organic matter to improve their replication rate, damaging the host. | -1                 | --            | --                | Harmonic          | Necrosis                           |
| Meltdown                | Causes an internal meltdown inside the nanites, causing internal  burns inside the host as well as rapidly destroying the nanite  population. Sets the nanites' safety threshold to 0 when activated.  | 10                 | --            | --                | Military          | Glitch                             |
| Chain Detonation        | Detonates all the nanites inside the host in a chain reaction when triggered. | 0                  | 25            | 10s               | Military          | Toxin Buildup                      |
| Cryogenic Treatment     | The nanites rapidly sink heat through the host's skin, lowering their temperature. | 1                  | --            | --                | Mesh              | Dermalysis, Sub-Dermal Combustion  |
| Sub-Dermal Combustion   | The nanites cause buildup of flammable fluids under the host's skin, then ignites them. | 4                  | --            | --                | Military          | Dermalysis, Cryogenic Treatment    |
| Mind Control            | The nanites imprint an absolute directive onto the host's brain for 60 seconds when triggered. Can be used with a Comm Remote. | --                 | 30            | 180s              | Hazard            | Neuro-Necrosis, Brain Misfire      |

### Suppression Programs

Programs with the goal of acting as a deterrent against the host. Generally nonlethal. 

| Program               | Effect | Volume per second  | Trigger Cost  | Trigger Cooldown  | Required Techweb  | Corruptions                            |
|-----------------------|--------|--------------------|---------------|-------------------|-------------------|----------------------------------------|
| Electric Shock        | The nanites shock the host when triggered. This will still harm nanites, causing volume loss and potential program errors.  | --                 | 10            | 30s               | Mesh              | Toxin Buildup                          |
| Neural Shock          | The nanites pulse the host's nerves when triggered, inapacitating them for a short period. | --                 | 4             | 30s               | Neural            | Electric Shock, Nerve Decay            |
| Sleep Induction       | The nanites cause rapid (but not instant) narcolepsy when triggered. | --                 | 15            | 120s              | Synaptic          | Neuro-Necrosis, Brain Misfire          |
| Paralysis             | The nanites actively suppress nervous pulses, effectively paralyzing the host while active. | 3                  | --            | --                | Neural            | Nerve Decay                            |
| Happiness Enhancer    | The nanites synthesize serotonin inside the host's brain, creating an artificial sense of happiness. | 0.1                | --            | --                | Neural            | Neuro-Necrosis                         |
| Happiness Suppressor  | The nanites suppress the production of serotonin inside the host's brain, creating an artificial state of depression.       | 0.1                | --            | --                | Neural            | Neuro-Necrosis                         |
| Death Simulation      | The nanites induce a death-like coma into the host, able to fool most medical scans. | 3.5                | --            | --                | Harmonic          | Necrosis, Nerve Decay, Neuro-Necrosis  |
| Pacification          | The nanites suppress the aggression center of the brain, preventing the host from causing direct harm to others.            | 1                  | --            | --                | Synaptic          | Neuro-Necrosis, Brain Misfire          |
| Blindness             | The nanites suppress the host's ocular nerves, blinding them while they're active. | 1.5                | --            | --                | Synaptic          | Nerve Decay                            |
| Mute                  | The nanites suppress the host's speech, making them mute while they're active. | 0.75               | --            | --                | Synaptic          | Neuro-Necrosis, Brain Misfire          |
| Forced Speech         | The nanites force the host to say a pre-programmed sentence when triggered. | --                 | 3             | 2s                | Synaptic          | Neuro-Necrosis, Brain Misfire          |
| Skull Echo            | The nanites echo a synthesized message inside the host's skull. | --                 | 1             | 2s                | Smart             | Neuro-Necrosis, Brain Misfire          |
| Hallucination         | The nanites make the host hallucinate something when triggered. | --                 | 4             | 8s                | Synaptic          | Brain Misfire                          |

### Sensor Programs

Programs that will self-pulse a given code when their condition is met. 

| Program                 | Effect | Volume per second  | Trigger Cost  | Trigger Cooldown  | Required Techweb  | Corruptions  |
|-------------------------|--------|--------------------|---------------|-------------------|-------------------|--------------|
| Health Sensor           | The nanites receive a signal when the host is above/below a certain percentage of health, with crit being 0. | 0                  | --            | --                | Biological        | Glitch       |
| Critical Health Sensor  | The nanites receive a signal when the host first reaches critical health. | 0                  | --            | --                | Biological        | Glitch       |
| Death Sensor            | The nanites receive a signal when they detect the host is dead. | 0                  | --            | --                | Biological        | Glitch       |
| Nanite Volume Sensor    | The nanites receive a signal when the nanite supply is above/below a  certain percentage, with the safety threshold being 0%. If safety  threshold is higher, it will skew the percentage. For example, with  threshold 50, 100 volume will count as 50 available volume, which means  10% instead of 20%, and the full 500 volume will count as 90%.  | 0                  | --            | --                | Basic             | Glitch       |
| Damage Sensor           | The nanites receive a signal when a host's specific damage type is above/below a target value. | 0                  | --            | --                | Biological        | Glitch       |
| Voice Sensor            | Sends a signal when the nanites hear a determined word or sentence. | 0                  | --            | --                | Smart             | Glitch       |
| Species Sensor          | When triggered, the nanites scan the host and output a signal if the  host's species matches the one set in the program's settings. The  options include "Human", "Lizard", "Moth", "Ethereal", "Pod", "Fly", "Jelly" and "Other". Secondary toggle is either "Is" or "Is  Not".                                                           | --                 | --            | --                | Biological        | Glitch       |

# The Duke Themselves
<iframe src="https://player.twitch.tv/?channel=thedukeofook&parent=wiki.monkestation.com" frameborder="0" allowfullscreen="true" scrolling="no" height="378" width="620"></iframe>