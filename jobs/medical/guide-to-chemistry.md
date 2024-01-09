---
title: Guide to Chemistry
description: Ho boy... be careful with this stuff or you might kill us all
published: true
date: 2024-01-09T04:50:55.906Z
tags: chemistry, guides, medical
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

# Master Index Table

> Table generated by hand using information from REAGENT SEARCH of applicable things for Chemistry. Not all things listed, will receive further expansion later.
{.is-warning}

| Name | Formula | Reaction Conditions | Description |
|---|---|---|---|
| Acetaldehyde | 1u Acetone, 1u Formaldehyde, 1u Water | 450k+ exothermic | Similar to plastic. Tastes like dead people., metabolizes 0.1u/s |
| Acetone | 1u Oil, 1u Welding Fuel, 1u Oxygen | any | A slick, slightly carcinogenic liquid. Has a multitude of mundane uses in everyday life. Metabolizes 0.1u/s |
| Acetone Oxide | 2u Acetone, 1u Oxygen, 1u Hydrogen Peroxide | any | Enslaved oxygen. Metabolizes 0.1u/s |
| Adminordrazine | N/A | N/A | It's magic. We don't have to explain it. Metabolizes 0.1u/s |
| Advanced Tranquility | N/A | N/A | A highly mutative liquid of unknown origin. |
| Aetericilide | 1u Unstable Mutagen, 1u Stable Plasma, 1u Diethylamine, 1u Copper (makes 2u) | any | An immune system enhancement drug, able to increase the power of a person's immune system up to 5 times its starting level. |
| Aiuri | 1u Ammonia, 1u Sulfuric Acid, 2u Hydrogen | 50-315k endothermic | Used to treat burns. Does minor eye damage. |
| Aivime | Inverse chem of [] use Australium | n/a | This reagent is known to interfere with the eyesight of a patient. |
| Aluminium | N/A | N/A | A silvery white and ductile member of the boron group of chemical elements. |
| Aluxive | 1u Sugar, 1u Seiver, 1u Cryptobiolin | any | A powerful immune enhancing drug, often used in small doses to counteract immunodeficiency. |
| Amanitin | n/a | n/a | A very powerful delayed toxin. Upon full metabolization, a massive amount of toxin damage will be dealt depending on how long it has been in the victim's bloodstream. |
| Amatoxin | n/a | n/a | A powerful poison derived from certain species of mushroom. |
| Ammonia | 3u Hydrogen, 1u Nitrogen | any | A caustic substance commonly used in fertilizer or household cleaners. |
| Ammoniated Mercury | 1u Calomel, 2u Ammonia | any | Quickly purges the body of toxic chemicals. Heals toxin damage when in a good condition someone has no brute and fire damage. When hurt with brute or fire damage, it can deal a great amount of toxin damage. When there are no toxins present, it starts slowly purging itself. |
| Anacea | 1u Haloperidol, 1u Impedrezene, 1u Radium | any | A toxin that quickly purges medicines and metabolizes very slowly. |
| Antihol | 1u Ethanol, 1u Multiver, 1u Copper | 1k-550k | Purges alcoholic substance from the patient's body and eliminates its side effects. |
| Ants | 2u Ants, 8u Sugar (3u Ants) | 50k+ | A genetic crossbreed between ants and termites, their bites land at a 3 on the Schmidt Pain Scale. |
| Aranesp | 1u Epinephrine, 1u Atropine, 1u Morphine | any | Amps you up, gets you going, and rapidly restores stamina damage. Side effects include breathlessness and toxicity. |
| Ash | 1u Oil, 1u Welding Fuel, 1u Oxygen | 480k+ | Supposedly phoenixes rise from these, but you've never seen it. |
| Atropine | 1u Ethanol, 1u Acetone, 1u Diethylamone, 1u Phenol, 1u Sulfuric Acid | any | If a patient is in critical condition, rapidly heals all damage types as well as regulating oxygen in the body. Excellent for stabilizing wounded patients, and said to neutralize blood-activated internal explosives found amongst clandestine black op agents. |
| Australium | 1u Mercury, 1u Happiness, 1u Sulfuric Acid | any | Causes people to invert into austrilians, has interesting effects on chemicals as well. |
| Baldium | 1u Radium, 1u Sulfuric Acid, 1u Lye | 395k+ | A major cause of hair loss across the world. |
| Barber's Aid | 1u Carpet, 1u Radium, 1u Space Drugs | any | A solution to hair loss across the world. |
| Bath Salts | 1u Bad Food, 1u Saltpetre, 1u Nutriment, 1u Space Cleaner, 1u Universal Enzyme, 1u Tea, 1u Mercury | 374k+ | Makes you impervious to stuns and grants a stamina regeneration buff, but you will be a nearly uncontrollable tramp-bearded raving lunatic. |
| Black Carpet | 1u Carpet, 1u Oil | any | The carpet also comes in... BLAPCK |
| Black Powder | grind black crayons | n/a | A black powder, used for coloring things black. |
| BLaStOoF | 10u Silver, 10u Cyanide, 5u Lye | n/a | A drug for the hardcore party crowd said to enhance ones abilities on the dance floor. Most old heads refuse to touch this stuff, perhaps because memories of the luna discoteque incident are seared into their brains. |
| Blood | 1u Unstable Mutagen, 1u Blood | n/a | It’s blood |
| Blue Carpet | 1u Carpet, 1u Cryostylane | any | For those that really need to chill out for a while. |
| Bone Hurting Juice | 1u Unstable Mutagen, 1u Milk, 3u Itching Power | any | A strange substance that looks a lot like water. Drinking it is oddly tempting. Oof ouch. |
| Bromine | n/a | n/a | A brownish liquid that's highly reactive. Useful for stopping free radicals, but not intended for human consumption. |
| Calomel | 1u Mercury, 1u Chlorine | 374k+ | Quickly purges the body of all chemicals except itself. The more health a person has, the more toxin damage it will deal. It can heal toxin damage when people have low enough health. |
| Capsaicin Oil | n/a | n/a | This is what makes chilis hot. |
| Carbon | n/a | n/a | A crumbly black solid that, while unexciting on a physical level, forms the base of all known life. Kind of a big deal.  |
| Carpet | 1u Space Drugs, 1u Blood | any | For those that need a more creative way to roll out a red carpet. |
| Carpotoxin | n/a | n/a | A deadly neurotoxin produced by the dreaded spess carp. |
| Chloral Hydrate | 1u Ethanol, 3u Chlorine, 1u Water | 200k+ | A powerful sedative that induces confusion and drowsiness before putting its target to sleep. |
| Chlorine | n/a | n/a | A pale yellow gas that's well known as an oxidizer. While it forms many harmless molecules in its elemental form it is far from harmless. |
| Chlorine Trifluoride | 1u Chlorine, 3u Fluorine | 424-1050k | Makes a temporary 3x3 fireball when it comes into existence, so be careful when mixing. ClF3 applied to a surface burns things that wouldn't otherwise burn, sometimes through the very floors of the station and exposing it to the vacuum of space. |
| Clonexadone | 1u Cryoxadone, 1u Sodium, 5u Plasma |  | A chemical that derives from Cryoxadone. It specializes in healing clone damage, but nothing else. Requires very cold temperatures to properly metabolize, and metabolizes quicker than cryoxadone. |
| Cocaine |  |  | A powerful stimulant extracted from coca leaves. Reduces stun times, but causes drowsiness and severe brain damage if overdosed. |
| Colorful Reagent | 1u Stable Plasma, 1u Radium, 1u Space Drugs, 1u Cryoxadone, 1u Triple Citrus | any | Thoroughly sample the rainbow. |
| Concentrated Barber's Aid | 1u Barber’s Aid, 1u Unstable Mutagen | any | A concentrated solution to hair loss across the world. |
| Condensed Capsaicin | 1u Capsaicin Oil, 5u Ethanol | any | A chemical agent used for self-defense and in police work. |
| Convermol | 1u Hydrogen, 1u Fluorine, 1u Oil | 370-570k | Restores oxygen deprivation while producing a lesser amount of toxic byproducts. Both scale with exposure to the drug and current amount of oxygen deprivation. Overdose causes toxic byproducts regardless of oxygen deprivation. |
| Copper | n/a | n/a | A highly ductile metal. Things made out of copper aren't very durable, but it makes a decent material for electrical wiring. |
| Corazargh | n/a | n/a | Interferes with the body's natural pacemaker, forcing the patient to manually beat their heart. |
| Coveroli | Inverse chem of Convermol use Australium | n/a | This reagent is known to coat the inside of a patient's lungs, providing greater protection against hot or cold air. |
| Cryogelidia | Inverse chem of Cryostylane use Australium | n/a | Freezes the live or dead patient in a cryostasis ice block. |
| Cryostylane | 1u Ice, 1u Stable Plasma, 1u Nitrogen | ←200k | Induces a cryostasis like state in a patient's organs, preventing them from decaying while dead. Slows down surgery while in a patient however. When reacted with oxygen, it will slowly consume it and reduce a container's temperature to 0K. Also damages slime simplemobs when 5u is sprayed. |
| Cryoxadone | 1u Stable Plasma, 1u Acetone, 1u Unstable Mutagen | any | A chemical mixture with almost magical healing powers. Its main limitation is that the patient's body temperature must be under 270K for it to metabolise correctly. |
| Cryptobiolin | 1u Potassium, 1u Oxygen, 1u Sugar | any | Cryptobiolin causes confusion and dizziness. |
| Cyan Carpet | 1u Carpet, 1u Cyanide | any | For those that need a throwback to the years of using poison as a construction material. Smells like asbestos. |
| Cyanide | 1u Oil, 1u Ammonia, 1u Oxygen | 380k+ | An infamous poison known for its use in assassination. Causes small amounts of toxin damage with a small chance of oxygen damage or a stun. |
| Decaying Uranium Gel | 1u Uranium, 1u Virus Food | any | A jade-green metallic chemical element in the actinide series, weakly radioactive. |
| Diethylamine | 1u Ammonia, 1u Ethanol | any | A secondary amine, mildly corrosive. |
| Diphenhydramine | 1u Oil, 1u Carbon, 1u Bromine, 1u Diethylamine, 1u Ethanol | any | Rapidly purges the body of Histamine and reduces jitteriness. Slight chance of causing drowsiness. |
| Drying Agent | 2u Stable Plasma, 1u Ethanol, 1u Sodium | any | A desiccant. Can be used to dry things. |
| Eigenstasium | 1u Bluespace Dust, 1u Stable Plasma, 1u Caramel | 350-650k | A strange mixture formed from a controlled reaction of bluespace with plasma, that causes localised eigenstate fluxuations within the patient |
| Eigenswap | Inverse chem of Eigenstasium | any | This reagent is known to swap the handedness of a patient. |
| Ephedrine | 1u Sugar, 1u Oil, 1u Hydrogen, 1u Diethylamine | 200-500k | Increases resistance to batons and movement speed, giving you hand cramps. Overdose deals toxin damage and inhibits breathing. |
| Epinephrine | 1u Phenol, 1u Acetone, 1u Diethylamine, 1u Oxygen, 1u Chlorine, 1u Hydrogen | any | Very minor boost to stun resistance. Slowly heals damage if a patient is in critical condition, as well as regulating oxygen loss. Overdose causes weakness and toxin damage. |
| Ethanol | n/a | n/a | A well-known alcohol with a variety of applications. |
| Fentanyl | 1u Space Drugs | 674-874k | Fentanyl will inhibit brain function and cause toxin damage before eventually knocking out its victim. |
| Firefighting Foam | 1u Stabilizing Agent, 1u Fluorosurfactant, 1u Carbon | 5-200k | A historical fire suppressant. Originally believed to simply displace oxygen to starve fires, it actually interferes with the combustion reaction itself. Vastly superior to the cheap water-based extinguishers found on NT vessels. |
| Flash Powder | 1u Aluminium, 1u Potassium, 1u Sulfur | any | Makes a very bright flash. |
| Fluorine | n/a | n/a | A comically-reactive chemical element. The universe does not want this stuff to exist in this form in the slightest. |
| Fluorosulfuric Acid | 1u Sulfuric Acid, 1u Fluorine, 1u Hydrogen, 1u Potassium | 380k+ | Fluorosulfuric acid is an extremely corrosive chemical substance. |
| Fluorosurfactant | 2u Fluorine, 2u Carbon, 1u Sulfuric Acid | any | A perfluoronated sulfonic acid that forms a foam when mixed with water. |
| Foaming Agent | 1u Lithium, 1u Hydrogen | any | An agent that yields metallic foam when mixed with light metal and a strong acid. |
| Formaldehyde | 1u Ethanol, 1u Oxygen, 1u Silver | 420k+ | Formaldehyde, on its own, is a fairly weak toxin. It contains trace amounts of Histamine, very rarely making it decay into Histamine. |
| Freebase cocaine |  |  | A smokable form of cocaine. |
| Granibitaluri | 1u Table Salt, 1u Carbon, 1u Sulfuric Acid, 5u Iron (Catalyst) | any | A mild painkiller useful as an additive alongside more potent medicines. Speeds up the healing of small wounds and burns, but is ineffective at treating severe injuries. Extremely large doses are toxic, and may eventually cause liver failure. |
| Gravitum | 1u Wittel, 10u Sorium | any | A rare kind of null fluid, capable of temporalily removing all weight of whatever it touches. |
| Green Carpet | 1u Carpet, 1u Green Beer | any | For those that need the perfect flourish for green eggs and ham. |
| Gunpowder | 1u Saltpetre, 1u Multiver, 1u Sulfur | any | Explodes. Violently. |
| Haloperidol | 1u Chlorine, 1u Fluorine, 1u Aluminium, 1u Potassium Iodide, 1u Oil | any | Increases depletion rates for most stimulating/hallucinogenic drugs. Reduces druggy effects and jitteriness. Severe stamina regeneration penalty, causes drowsiness. Small chance of brain damage. |
| Happiness | 2u Nitrous Oxide, 1u Epinephrine, 1u Ethanol, 5u Plasma (catalyst) | any | Fills you with ecstasic numbness and causes minor brain damage. Highly addictive. If overdosed causes sudden mood swings. |
| Hauntium | n/a | n/a | An eerie liquid created by purifying the prescence of ghosts. If it happens to get in your body, it starts hurting your soul. |
| Helbital | 1u Sugar, 1u Fluorine, 1u Carbon | n/a | Named after the norse goddess Hel, this medicine heals the patient's bruises the closer they are to death. Patients will find the medicine 'aids' their healing if not near death by causing asphyxiation. |
| Hercuri | 3u Cryostylane, 1u Bromine, 1u Lye | 5-47k | Not to be confused with element Mercury, this medicine excels in reverting effects of dangerous high-temperature environments. Prolonged exposure can cause hypothermia. |
| Higadrite | 2u Phenol, 1u Lithium | any | A medication utilized to treat ailing livers. |
| Hydrogen | n/a | n/a | A colorless, odorless, nonmetallic, tasteless, highly combustible diatomic gas. |
| Hydrogen Peroxide | 1u Water, 1u Oxygen, 1u Chlorine | any | An ubiquitous chemical substance that is composed of hydrogen and oxygen and oxygen. |
| Impedrezene | 1u Mercury, 1u Oxygen, 1u Sugar | any | Impedrezene is a narcotic that impedes one's ability by slowing down the higher brain cell functions. |
| Inacusiate | 1u Water, 1u Carbon, 1u Multiver | 300-500k | Rapidly repairs damage to the patient's ears to cure deafness, assuming the source of said deafness isn't from genetic mutations, chronic deafness, or a total defecit of ears. |
| Inaprovaline |  |  | Stabilizes the breathing of patients. Good for those in critical condition. |
| Iodine |  |  | Commonly added to table salt as a nutrient. On its own it tastes far less pleasing. |
| Ipecacide |  |  | An extremely gross substance that induces vomiting. It is produced when Lipolicide reactions are impure. |
| Iron |  |  | Pure iron is a metal. |
| Itching Powder | 1u Welding Fuel, 1u Ammonia, 1u Multiver | 280-700k | A powder that induces itching upon contact with the skin. Causes the victim to scratch at their itches and has a very low chance to decay into Histamine. |
| Krokodil | 1u Diphenhydramine, 1u Morphine, 1u Space Cleaner, 1u Potassium, 1u Phosphorus, 1u Welding Fuel | 380k | Cools and calms you down. If overdosed it will deal significant Brain and Toxin damage. |
| Kronkaine |  |  | A highly illegal stimulant from the edge of the galaxy. It is said the average kronkaine addict causes as much criminal damage as five stick up men, two rascals and one proferssional cambringo hustler combined. |
| Lenturi | 1u Ammonia, 1u Silver, 1u Sulfur, 1u Oxygen, 1u Chlorine | 200-500k | Used to treat burns. Makes you move slower while it is in your system. Applies stomach damage when it leaves your system. |
| Leporazine | 1u Silicon, 1u Copper, 5u Plasma (catalyst) | any | Leporazine will effectively regulate a patient's body temperature, ensuring it never leaves safe levels. |
| Lexorin | 1u Plasma, 1u Hydrogen, 1u Salbutamol | any | A powerful poison used to stop respiration. |
| Libital | 1u Phenol, 1u Oxygen, 1u Nitrogen | 225-840k | A bruise reliever. Does minor liver damage. |
| Libitoil |  |  | Temporarilly interferes a patient's ability to process alcohol. |
| Lipolicide | 1u Mercury, 1u Diethylamine, 1u Ephedrine | any | A powerful toxin that will destroy fat cells, massively reducing body weight in a short time. Deadly to those without nutriment in their body. |
| Lithium |  |  | A silver metal, its claim to fame is its remarkably low density. Using it is a bit too effective in calming oneself down. |
| Lye | 1u Sodium, 1u Hydrogen, 1u Oxygen | any | Also known as sodium hydroxide. As a profession making this is somewhat underwhelming. |
| Maintenance Powder | 6u Maintenance Sludge, 1u Nitric Acid, 1u Universal Enzyme, 5u Acetone Oxide (catalyst) |  | An unknown powder that you most likely gotten from an assistant, a bored chemist... or cooked yourself. It is a refined form of tar that enhances your mental ability, making you learn stuff a lot faster. |
| Maintenance Sludge | 3u Maintenance Tar, 1u Fluorosulfuric Acid, 5u Hydrogen Peroxide (catalyst) | any | An unknown sludge that you most likely gotten from an assistant, a bored chemist... or cooked yourself. Half refined, it fills your body with itself, making it more resistant to wounds, but causes toxins to accumulate. |
| Maintenance Tar | 1u Tea, 1u Organic Slurry, 1u Welding Fuel | any | An unknown tar that you most likely gotten from an assistant, a bored chemist... or cooked yourself. Raw tar, straight from the floor. It can help you with escaping bad situations at the cost of liver damage. |
| Mannitoil |  |  | Gives the patient a temporary speech impediment. |
| Mannitol | 1u Sugar, 1u Hydrogen, 1u Water | 50-650k | Efficiently restores brain damage. |
| Mercury |  |  | A curious metal that's a liquid at room temperature. Neurodegenerative and very bad for the mind. |
| Metalgen |  |  | A purple metal morphic liquid, said to impose it's metallic properties on whatever it touches. |
| Methamphetamine | 1u Ephedrine, 1u Iodine, 1u Phosphorus, 1u Hydrogen | 372-380k | Reduces stun times by about 300%, speeds the user up, and allows the user to quickly recover stamina while dealing a small amount of Brain damage. If overdosed the subject will move randomly, laugh randomly, drop items and suffer from Toxin and Brain damage. If addicted the subject will constantly jitter and drool, before becoming dizzy and losing motor control and eventually suffer heavy toxin damage. |
| Methanol |  |  | A light, colourless liquid with a distinct smell. Ingestion can lead to blindness. It is a byproduct of organisms processing impure Formaldehyde. |
| Mindbreaker Toxin | 1u Silicon, 1u Hydrogen, 1u Multiver | any | A powerful hallucinogen. Not a thing to be messed with. For some mental patients. it counteracts their symptoms and anchors them to reality. |
| Miner's Salve | 1u Oil, 1u Water, 1u Iron | any | A powerful painkiller. Restores bruising and burns in addition to making the patient believe they are fully healed. Also great for treating severe burn wounds in a pinch. |
| Modafinil | 1u Diethylamine, 1u Ammonia, 1u Phenol, 1u Acetone, 1u Sulfuric Acid, 1u Bromine (catalyst) | any | Long-lasting sleep suppressant that very slightly reduces stun and knockdown times. Overdosing has horrendous side effects and deals lethal oxygen damage, will knock you unconscious if not dealt with. |
| Monover | Inverse chem of Multiver use Australium | any | A toxin treating reagent, that only is effective if it's the only reagent present in the patient. |
| Morphine | 2u Carbon, 2u Hydrogen, 1u Ethanol, 1u Oxygen | 480k+ | A painkiller that allows the patient to move at full speed even when injured. Causes drowsiness and eventually unconsciousness in high doses. Overdose will cause a variety of effects, ranging from minor to lethal. |
| Multiver | 1u Ash, 1u Table Salt | 380-410k | A chem-purger that becomes more effective the more unique medicines present. Slightly heals toxicity but causes lung damage (mitigatable by unique medicines). |
| Musiver | created in body using syriniver | n/a | The active metabolite of syriniver. Causes muscle weakness on overdose |
| Mutadone | 1u Unstable Mutagen, 1u Acetone, 1u Bromine | any | Removes jitteriness and restores genetic defects. |
| Mutagenic Agar | 1u Unstable Mutagen, 1u Virus Food | any | Might cause unpredictable mutations. Keep away from children. |
| Mute Toxin | 2u Uranium, 1u Water, 1u Carbon | any | A nonlethal poison that inhibits speech in its victim. |
| Napalm | 1u Oil, 1u Welding Fuel, 1u Ethanol | any | Very flammable. |
| Neon Carpet |  |  | For those who like the 1980s, vegas, and debugging. |
| Neruwhine | Inverse chem of Neurine, use Australium |  | Induces a temporary brain trauma in the patient by redirecting neuron activity. |
| Neurine | 1u Mannitol, 1u Acetone, 1u Oxygen |  | Reacts with neural tissue, helping reform damaged connections. Can cure minor traumas. |
| Nicotine |  |  | Slightly reduces stun times. If overdosed it will deal toxin and oxygen damage. |
| Nitric Acid | 1u Fluorosulfuric Acid, 1u Nitrogen, 1u Hydrogen Peroxide | 480k+ | Nitric acid is an extremely corrosive chemical substance that violently reacts with living organic tissue. |
| Nitrogen |  |  | A colorless, odorless, tasteless gas. A simple asphyxiant that can silently displace vital oxygen. |
| Nitroglycerin | 1u Glycerol, 1u Nitric Acid, 1u Sulfuric Acid | any | Nitroglycerin is a heavy, colorless, oily, explosive liquid obtained by nitrating glycerol. |
| Nitrous Oxide | 2u Ammonia, 1u Nitrogen, 2u Oxygen | 525-575k | A potent oxidizer used as fuel in rockets and as an anaesthetic during surgery. As it is an anticoagulant, nitrous oxide is best used alongside sanguirite to allow blood clotting to continue. |
| Nooartrium |  |  | A reagent that is known to stimulate the heart in a dead patient, temporarily bringing back recently dead patients at great cost to their heart. |
| Oculater | Inverse chem of Oculine use Australium | any | Temporarily blinds the patient. |
| Oculine | 1u Multiver, 1u Carbon, 1u Hydrogen | 200-600k | Quickly restores eye damage, cures nearsightedness, and has a chance to restore vision to the blind. |
| Oil | 1u Welding Fuel, 1u Carbon, 1u Hydrogen | any | Burns in a small smoky fire, can be used to get Ash. |
| Omnizine | n/a | n/a | Slowly heals all damage types. Overdose will cause damage in all types instead. |
| Orange Carpet | 1u Carpet, 1u Carrot Juice | any | For those that prefer a healthy carpet to go along with their healthy diet. |
| Oxandrolone | 3u Carbon, 1u Phenol, 1u Hydrogen, 1u Oxygen | any | stimulates the healing of severe burns. Extremely rapidly heals severe burns and slowly heals minor ones. Overdose will worsen existing burns. |
| Oxygen |  |  | A colorless, odorless gas. Grows on trees but is still pretty valuable. |
| Pax | 1u Mindbreaker Toxin, 1u Syanptizine, 1u Water | any | A colorless liquid that suppresses violence in its subjects. |
| Pentaerythritol | 1u Acetaldehyde, 3u Formaldehyde, 1u Lye | any | Slow down, it ain't no spelling bee! |
| Pentetic Acid | 1u Welding Fuel, 1u Chlorine, 1u Ammonia, 1u Formaldehyde, 1u Sodium, 1u Cyanide | any | Reduces massive amounts of toxin damage while purging other chemicals from the body. |
| Penthrite | 1u Pentaerythritol, Acetone, 1u Nitric Acid, 1u Wittel | 255-450k | An expensive medicine that aids with pumping blood around the body even without a heart, and prevents the heart from slowing down. Mixing it with epinephrine or atropine will cause an explosion. |
| Phenol | 1u Water, 1u Chlorine, 1u Water | any | An aromatic ring of carbon with a hydroxyl group. A useful precursor to some medicines, but has no healing properties on its own. |
| Phlogiston | 1u Phosphorus, 1u Sulfuric Acid, 1u Stable | any | Catches you on fire and makes you ignite. |
| Phosphorus |  |  | A ruddy red powder that burns readily. Though it comes in many colors, the general theme is always the same. |
| Plasma |  |  | Plasma in its liquid form. |
| Plastic Polymers | 5u Oil, 2u Sulfuric Acid, 3u Ash | 374k+ | the petroleum based components of plastic. |
| Polonium |  |  | An extremely radioactive material in liquid form. Ingestion results in fatal irradiation. |
| Potassium |  |  | A soft, low-melting solid that can easily be cut with a knife. Reacts violently with water. |
| Potassium Iodide | 1u Potassium, 1u Iodine | any | Heals low toxin damage while the patient is irradiated, and will halt the damaging effects of radiation. |
| Probital | 1u Copper, 2u Acetone, 1u Phosphorus | 225-750k | Originally developed as a prototype-gym supliment for those looking for quick workout turnover, this oral medication quickly repairs broken muscle tissue but causes lactic acid buildup, tiring the patient. Overdosing can cause extreme drowsiness. An Influx of nutrients promotes the muscle repair even further. |
| Protozine |  |  | A less environmentally friendly and somewhat weaker variant of omnizine. |
| Psicodine | 2u Mannitol, 2u Water, 1u Impedrezene | any | Suppresses anxiety and other various forms of mental distress. Overdose causes hallucinations and minor toxin damage. |
| Pump-Up | 5u Coffee, 2u Epinephrine | any | Take on the world! A fast acting, hard hitting drug that pushes the limit on what you can handle. |
| Purple Carpet | 1u Carpet, 1u Regenerative Jelly | any | For those that need to waste copious amounts of healing jelly in order to look fancy. |
| Pyroxadone | 1u Cryoxadone, 1u Slime Jelly | any | A mixture of cryoxadone and slime jelly, that apparently inverses the requirement for its activation. |
| Radiohydrate | 1u Radium, 1u Miner’s Slave | any | A potent immunosuppressant, can be used to prevent so-called benifical viruses from being naturally cured. |
| Radium |  |  | Radium is an alkaline earth metal. It is extremely radioactive. |
| Red Carpet | 1u Carpet, 1u Liquid Gibs | any | For those that need an even redder carpet. |
| Rezadone | 1u Carpotoxin, 1u Cryptobiolin, 1u Copper | any | A powder derived from fish toxin, Rezadone can effectively treat genetic damage as well as restoring minor wounds and restoring corpses husked by burns. Overdose will cause intense nausea and minor toxin damage. |
| Romerol |  |  | Romerol is a highly experimental bioterror agent which causes dormant nodules to be etched into the grey matter of the subject. These nodules only become active upon death of the host, upon which, the secondary structures activate and take control of the host body. |
| Rosenol | Inverse chem of Mindbreaker Toxin, use Australium | any | A strange, blue liquid that is produced during impure mindbreaker toxin reactions. Historically it has been abused to write poetry. |
| Rotatium | 1u Mindbreaker Toxin, 1u Teslium, 1u Fentanyl | any | A constantly swirling, oddly colourful fluid. Causes the consumer's sense of direction and hand-eye coordination to become wild. |
| Salbutamol | 1u Salicyclic Acid, 1u Lithium, 1u Aluminium, 1u Bromine, 1u Ammonia | any | Rapidly restores oxygen deprivation as well as preventing more of it to an extent. |
| Salicylic Acid | 1u Sodium, 1u Phenol, 1u Carbon, 1u Oxygen, 1u Sulfuric Acid | any | stimulates the healing of severe bruises. Extremely rapidly heals severe bruising and slowly heals minor ones. Overdose will worsen existing bruising. |
| Saline-Glucose Solution | 1u Table Salt, 1u Water, 1u Sugar | any | Has a 33% chance per metabolism cycle to heal brute and burn damage. Can be used as a temporary blood substitute, as well as slowly speeding blood regeneration. |
| Saltpetre | 1u Potassium, 1u Nitrogen, 3u Oxygen | any | Volatile. Controversial. Third Thing. |
| Sanguirite |  |  | A proprietary coagulant used to help bleeding wounds clot faster. It is purged by heparin. |
| Saturn-X |  |  | This compound was first discovered during the infancy of cloaking technology and at the time thought to be a promising candidate agent. It was withdrawn for consideration after the researchers discovered a slew of associated safety issues including thought disorders and hepatoxicity. |
| Stabilized Saturn-X |  |  | A chemical extract originating from the Saturn-X compound, stabilized and safer for tactical use. After the recipe was discovered, it was planned to be put into mass production, but the program fell apart after its lead disappeared and was never seen again. |
| Seiver | 1u Nitrogen, 1u Potassium, 1u Aluminium | any | A medicine that shifts functionality based on temperature. Hotter temperatures will heal more toxicity, while colder temperatures will heal larger amounts of toxicity but only while the patient is irradiated. Damages the heart. |
| Seraka Extract |  |  | A deeply coloured oil present in small amounts in Seraka Mushrooms. Acts as an effective blood clotting agent, but has a low overdose threshold. |
| Shakeium | 1u Vanilla Shake, 1u Corn Syrup, 3u Pwr Game | any | Causes violent shaking in consumers. |
| Silicon |  |  | A tetravalent metalloid, silicon is less reactive than its chemical analog carbon. |
| Silver |  |  | A soft, white, lustrous transition metal, it has the highest electrical conductivity of any element and the highest thermal conductivity of any metal. |
| Smart Foaming Agent | 3u Foaming Agent, 1u Acetone, 1u Iron | any | An agent that yields metallic foam which conforms to area boundaries when mixed with light metal and a strong acid. |
| Smoke Powder | 1u Potassium, 1u Sugar, 1u Phosphorus | any | Makes a large cloud of smoke that can carry reagents. |
| Sodium |  |  | A soft silver metal that can easily be cut with a knife. It's not salt just yet, so refrain from putting it on your chips. |
| Sodium Thiopental |  |  | Sodium Thiopental induces heavy weakness in its target as well as unconsciousness. |
| Sonic Powder | 1u Oxygen, 1u Cola, 1u Phosphorus | any | Makes a deafening noise. |
| Sorium | 1u Mercury, 1u Oxygen, 1u Nitrogen, 1u Carbon | any | Sends everything flying from the detonation point. |
| Space Cleaner | 1u Ammonia, 1u Water | any | A compound used to clean things. Now with 50% more sodium hypochlorite! |
| Space Drugs | 1u Mercury, 1u Sugar, 1u Lithium | any | An illegal chemical compound used as drug. |
| Space Lube | 1u Water, 1u Silicon, 1u Oxygen | any | Lubricant is a substance introduced between two moving surfaces to reduce the friction and wear between them. giggity. |
| Spaceacillin | 1u Cryptobiolin, 1u Epinephrine | any | A generic antipathogenic agent. |
| Spewium |  |  | A powerful emetic, causes uncontrollable vomiting. May result in vomiting organs at high doses. |
| Spray Tan | 1u Orange Juice, 1u Oil | any | A substance applied to the skin to darken the skin. |
| Stable Plasma | 1u Plasma, 1u Stabilizing Agent (catalyst) | any | Non-flammable plasma locked into a liquid form that cannot ignite or become gaseous/solid. |
| Sterilizine | 1u Ethanol, 1u Multiver, 1u Chlorine | any | Sterilizes wounds in preparation for surgery. |
| Sugar |  |  | The organic compound commonly known as table sugar and sometimes called saccharose. This white, odorless, crystalline powder has a pleasing, sweet taste. |
| Sulfonal | 1u Acetone, 1u Diethylamine, 1u Sulfur | any | A stealthy poison that deals minor toxin damage and eventually puts the target to sleep. |
| Sulfur |  |  | A sickly yellow solid mostly known for its nasty smell. It's actually much more helpful than it looks in biochemisty. |
| Sulfuric Acid |  |  | A strong mineral acid with the molecular formula H2SO4. |
| Super Melatonin | Inverse chem of Tirimol use Australium |  | This will send the patient to sleep, adding a bonus to the efficacy of all reagents administered. |
| Synaptizine | 1u Sugar, 1u Water, 1u Lithium | any | Increases resistance to stuns as well as reducing drowsiness and hallucinations. |
| Synthflesh | 1u Blood, 1u Carbon, 1u Libital | 250-325k | Heals brute and burn damage at the cost of toxicity (66% of damage healed). 100u or more can restore corpses husked by burns. Touch application only. |
| Synthpax |  |  | A colorless liquid that suppresses violence in its subjects. Cheaper to synthesize than normal Pax, but wears off faster. |
| Syriniver | 1u Sulfur, 1u Fluorine, 1u Toxin, 2u Nitrous Oxide | 250k+ | A potent antidote for intravenous use with a narrow therapeutic index, it is considered an active prodrug of musiver. |
| System Cleaner | 1u Ethanol, 1u Chlorine, 2u Phenol, 1u Potassium | any | Neutralizes harmful chemical compounds inside synthetic systems. |
| Table Salt | 1u Sodium, 1u Chlorine, 1u Water | any | A salt made of sodium chloride. Commonly used to season food. |
| Teslium | 1u Stable Plasma, 1u Silver, 1u Gunpowder | 400k+ | An unstable, electrically-charged metallic slurry. Periodically electrocutes its victim, and makes electrocutions against them more deadly. Excessively heating teslium results in dangerous destabilization. Do not allow to come into contact with water. |
| Thermite | 1u Aluminium, 1u Iron, 1u Oxygen | any | Thermite produces an aluminothermic reaction known as a thermite reaction. Can be used to melt walls. |
| Tinacusiate | Inverse chem of Inacusiate use Australium | any | Makes the patient's hearing temporarily funky. |
| Tinea Luxor |  |  | A stimulating ichor which causes luminescent fungi to grow on the skin.  |
| Tirimol | 3u Nitrogen, 2u Acetone, 1u Sulfuric Acid | 720k max | An oxygen deprivation medication that causes fatigue. Prolonged exposure causes the patient to fall asleep once the medicine metabolizes. |
| Tranquility |  |  | A highly mutative liquid of unknown origin. |
| Uranium |  |  | A jade-green metallic chemical element in the actinide series, weakly radioactive. |
| Welding Fuel |  |  | Required for welders. Flammable. |
| Wittel |  |  |  |
