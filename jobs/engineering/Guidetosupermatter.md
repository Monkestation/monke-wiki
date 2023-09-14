---
title: Guide to Supermatter
description: Oohhhh shiny!
published: true
date: 2023-09-14T22:20:46.481Z
tags: engineering, guides
editor: markdown
dateCreated: 2023-09-12T02:34:07.729Z
---

# Guide to the Suermatter

|                             | ENGINEERING GUIDES                                                                                 |
|-----------------------|
|![sm_meta.png](/jobs/engineering/sm_meta.png) <br>Roundstart Meta SM | **Warning:** The Supermatter is a birght yellow crystal of slaughter and destruction. If you walk into it on roundstart you will be **banned**.

## Description 
The Supermatter is a unstable hyper-reactive crystal that when injected with energy, provides a great deal more back in the form of radiation and electric shocks.
Whats good about this new form of power over older engines is that it is alot harder to cause it to explode or "Delaminate." Which is the correct term.


## ![warningsign.png](/jobs/engineering/warningsign.png) The Setup
The SM is alot more complicated in setting up compared to the Tesla and Singularity. Steps should be taken to double check and secure the setup as there are many more points of failure.
### ![supermatter_shard.png](/jobs/engineering/supermatter_shard.png) The Crystal
The SM on roundstart should be in a fully enclosed space with more then 90% of the work done for you! This means its harder to fuck up right? **Wrong.** Once again you must pay close attention, while the SM can be started even within 1 minute of the shift starting you need to know how to make it work.
The basic workings of generating power from the SM is that while it will generate more energy then what was put in, it will generate alot of this energy as heat. The setup's job is to export this heat away from the SM as it is actively turning coolant gasses into very dangerous, different gasses. The guide will later show what gasses do what but the most common is N2->O2->Plasma. We all know what happens when heat, plasma, and O2 mix together.
## Time to handle this thing.

### material requirements
For Round start setup you will need
- 1 Pair of Meson goggles
- 1 RPD (Rapid Pipe Dispenser)
|                             | The Loop                                                                                 |
|-----------------------|
|![sm_meta.png](/jobs/engineering/sm_meta.png) <br>Our example. | Starting off notice how there are alot of pumps segmenting the loop? **This is bad. The Golden rule of the Supermatter is that pumps bad, pipes good.** The reason why is explained later, just for now the only pump you want is the gas filter between the red pipenet and blue pipenet.

 
### The Classic
This tutorial on how to tame the SM will use the most clasic setup using N2 or nitrogen gas to cool the SM
| The Classic Part 1
|-----------------------|
|![sm_part_1.png](/jobs/engineering/sm_part_1.png) <br> Pumps bad.| ![sm_part_2.png](/jobs/engineering/sm_part_2.png) <br> Pipes good! Remove the bypass entirely. 

 |The Classic Part 2|
||
|![sm_part_1.png](/jobs/engineering/sm_part_3.png) <br> Filters and Pumps bad.| ![sm_part_2.png](/jobs/engineering/sm_part_4.png) <br> Use layer connectors for upgrade potential. 
 |The Classic Part 3|
||
|![sm_part_1.png](/jobs/engineering/sm_part_5.png) <br> The pumps arent good either| ![sm_part_2.png](/jobs/engineering/sm_part_6.png) <br> So we replace with more pipes!
 |The Classic Part 4|
||
|![sm_part_1.png](/jobs/engineering/sm_part_7.png) <br> Wrench the N2 Tanks and turn on those pumps, they're good.| ![sm_part_2.png](/jobs/engineering/sm_part_8.png) <br> Go to the air alarm next to the SM. Vent controls should be like this.
 |The Classic Part 5|
||
|![sm_part_1.png](/jobs/engineering/sm_part_9.png) <br> Now set the scrubbers.| ![sm_part_2.png](/jobs/engineering/sm_part_10.png) <br> Finally after every other step is done, start the power generation!  

Good job! you just started a Supermatter! Now get the hell out of there as the SM has been started by the emitter fire and will produce radiation.

## Gas interactions
The supermatter will influence and get influenced by the various gases in the SM, the reason roundstart uses N2 is because it does not boost the SM in any way and is decent at keeping it cool.
Here is every interacting gas and what it will do
| Gas    | Danger |Description |Notables |Effects |
|-|-|-|-|-|
| ![hyper_nob.png](/jobs/engineering/hyper_nob.png)  <br> Hyper-nobelium   | -100%       |Stops gas reactions (Like fires) when more then 5 moles are present per tile. Decreases waste output of SM and Increases power gen a bit. | - Effectively stops waste production <br> - 1 part of resonance cascade |- Power Transmission +30% <br> - Waste Multiplier -1400% <Br> - Heat Power Gen -100%|
| ![helium.png](/jobs/engineering/helium.png) <br> Helium  | -100%       |Completely non reactive gas to cool the SM |None |N/A |
| ![freon.png](/jobs/engineering/freon.png) <br> Freon  | -50%  | When the SM gasses become 30% freon power transmission will stop. This will cause the SM to rapidly cool, also has a higher heat capacity then plasma so great for absorbing heat. When very cool it will turn into hot ice which can cause a plasma fire if not handled with caution.|Great at cooling, can become disasterous if not managed |- Power Transmission -300% <br> - Waste Multiplier -900% <br> - Heat Powergain -100% |
| ![protonitr.png](/jobs/engineering/protonitr.png) <br> Proto-Nitrate  | -30%        | This gas is just a good worker. Increases power generation while adding heat resistance to the SM. It will also make more power at the higher heats you can now achive! |No Downsides. | - Power Transmission +150% <br> - Waste Multiplier -400% <br> - Heat Resistance +400% (You can have the SM on fire and be fine) <br> - Heat Powergain +100% |
| ![n2.png](/jobs/engineering/n2.png) <br> Nitrogen  | 0% (baseline)        | Nitrogen gas is your run of the mill safe gas for long term SM use. Even hampers plasma generation from the sm! | Abundant and safe! |- Waste Multiplier -250% <br> - Heat Powergain -100% |
| ![pluox.png](/jobs/engineering/pluox.png) <br> Pluoxium | 0%        | This gas while useful for internals mainly distrupts CO2 SMs by canceling out any benefits of CO2, then acts like Nitrogen. Get it out of your SM asap. | A worse Nitrogen |- Power transmission -50% <br> - Waste Multiplier -150% <br> - Heat Powergain -100% |
| ![n2o.png](/jobs/engineering/n2o.png) <br> Nitrous Oxide | 10%        |N~2~O is great at stopping a delamination from heat. Except that it decays at high heat into O2 and N2, Oxygen of course is bad for the SM and should be avoided. Use this to stop a heat delam in its tracks. | Great heat resistance |- Heat Resistance +500%|
| ![o2.png](/jobs/engineering/o2.png) <br> Oxygen  | 20%        |Oxygen is the first of the gases that can make a SM run better. Thanks to it being a very low level booster it doesnt have active downsides but can spell disaster for an unprepared engineer. The SM produces small amounts of plasma and high oxygen plasma fires trigger tritium production, Tritium fires are horifying on their own. Inside a sm? You better call the shuttle. | Doesnt technically have a downside |- Power Transmission +15% <br> - Heat powergain +100% |
| ![miasma.png](/jobs/engineering/miasma.png) <br> Miasma | 25%        |Consumed by the sm directly to produce more power. About 10Mev/Cm^3 per mole |Directly consumed by SM |- Heat Powergain +50% |
| ![healium.png](/jobs/engineering/healium.png) <br> Healium | 30%        |Healium is pretty bad in the SM, therfore do not waste it on the SM, the atmos techs and their HFR can use it alot more then you. Its benefits are very much weighed down by its penalties. |Much better uses outside SM |- Power Trasnmission +24% <br> - Waste Multiplier +300% <br> - Heat Powergain +100% |
| ![halon.png](/jobs/engineering/halon.png) <br> halon  | 50%        | Just like Healium this gas has much better uses outside the SM. But this gas provide **Nothing** to the SM, all it does is create much more dangerous gasses with less dangerous ones.| Turns O2 into CO2 |Nothing |
| ![co2.png](/jobs/engineering/co2.png) <br> Carbon Dioxide| 30%        |CO2 is what many engineers make their SM on if they need power. CO2 will greatly increase power generation but is very dangerous to run as it is quite easy to charge delam (Read: Tesloose). Make sure you have backup cooling systems and are ready to cut the emitters if using this gas. |Suprisingly little active downsides, Still dangerous |- Waste Multiplier +100% <br> - Heat Powergain +100% <br> - Power Decay Negation +100% |
| ![zauk.png](/jobs/engineering/zauk.png) <br> Zauker  | 40%        |Zauker is a much better CO2 but its downsides didnt scale as much. Only problem is finding this rare gas. |Extreme energy boost for downsides |- Power Transmission +200% <br> - Waste Multiplier +400% <br> - Heat Powergeneration +100% |
| ![bz.png](/jobs/engineering/bz.png) <br> BZ | 60%  (DANGER)   |Do you want to get bwoinked? Use this gas! It shoots fusion particles that penetrate radsuits and even the CE's Modsuit. It also drops power transmission. |Weaponizes the SM |- Power Transmission -20% <br> - Waste Multiplier +400% <br> - Heat Powergain + 100% |
| ![h2o.png](/jobs/engineering/h2o.png) <br> H~2~O  | 65% (DANGER)       |BZ gas but even angrier. Gets made in the SM during plasma fires. GET THIS OUT OF THE SM FAST. |Doesnt have the BZ fusion particles |- Power Transmission -25% <br> - Waste Multiplier +**1100%** <br> - Heat Power Generation +100%|
| ![plasma.png](/jobs/engineering/plasma.png) <br> Plasma  | 75% (DANGER)       |Whoe be apon ye, plasma is a roided version of O2 that also just injected maint pump-up. Just like the crazied tider it will bully and bash your SM setup truely putting it to the test. Fyi: Roundstart setup cannot handle this. You must make a full redesign. |Massive Waste multiplier|- Power Transmission +40% <br> - Waste Multiplier **+1400%** <br> - Heat Powergain +100%|
| ![trit.png](/jobs/engineering/trit.png) <br> Tritium | 90% (**DANGER!!**)        |You know how I mentioned tritium is bad earlier? Incase you didn't know, tritium is a radioactive gas then when lit on fire, goes hot enough to melt flooring into space, husk people in under a minute, and leaves the area radioactively contaiminated to point where seconds of exposouer lead to 20+ minutes in the medbay. This gas is a shitter that was handed a meteor gun and told they would be banned no matter what they did. | Great for power gen, you'll need it cause you wont have an SM soon. |- Power Transmission +300% <br> - Waste Multiplier +900% <br> - Heat Powergain +100%|
| ![hydrogen.png](/jobs/engineering/hydrogen.png)  <br> Hydrogen | 80% (**DANGER!!**)        | Hydrogen is a reformed version of tritium. For slightly less power generation it gets some heat resistance. Still extrodinarly dangerous. | safer? Tritium |- Power Transmission +250% <br> - Waste Multiplier +900% <br> - Heat resistance +100% <br> - Heat Powergain +100% |
| ![antinob.png](/jobs/engineering/antinob.png) <br> Anti-Nobelium  | 100% (May god have mercy apon your soul)  | 2 things are occuring if you see Anti-Nobelium in your SM. Reason 1: Your local engineer has had his ego inflated to be larger then the gods themselves. You have every right at that point to stop them in any way including murder, once command / Security knows why you will be forgiven. <br> Reason 2: If you also see Hyper Nobelium in the SM you should run away as a resonance cascade is about to occur, which will completely destroy the station. **Run away and alert all that can be alerted. You must escape the station.**| near 0 heat capacity, Makes the SM shit over the station | - Power Transmission -50% <br> - Waste Multiplier **+1400%** <br> - Heat Powergain +100%|
# The Duke Themselves
<iframe src="https://player.twitch.tv/?channel=thedukeofook&parent=wiki.monkestation.com" frameborder="0" allowfullscreen="true" scrolling="no" height="378" width="620"></iframe>