---
title: Guide to Ordnance
description: Kabooomm?? Yes Rico, Kaboom.
published: true
date: 2023-12-15T02:27:56.714Z
tags: guides, science, ordnance, bombs, ttv
editor: markdown
dateCreated: 2023-12-15T02:27:56.714Z
---

# Guide to Ordnance
Ordnance is a section of the Research and Development section of the station. There was a time when being in this place was basically a dead giveaway that you were a bad guy but with the advent of Research bombs, this is no longer the case.* Instead, being a robust bomb-maker will get you praise and laudation as the crew realizes you used all the bombmix to complete difficult research experiments and get a lot of credits for the department's research budget rather than using it to turn the Station into a crater-ridden deathtrap! Hooray Science! 

## Tools of the trade

There are a few items that you will need to grab or at least keep track of. 

### Items

#### Rapid Pipe Dispenser

The rapid pipe dispenser can be found in the ordnance lab. You will need it to retool the pipe setup.
#### Analyzer

The analyzer will tell you what is going on with canisters, pipes, the environment, simply Left Click with it on your hand on things to examine them and Press Z or Click the analyzer itself to examine the air around you. Right click the analyzer icon to open the gas and reaction reference.
#### PDA or Modular Computer

We will need them to publish papers and read up on the experiments we are about to do. Make sure you have one nearby.
#### Holofans

Some station start with the luxury of having the Atmos Holofan in the ordnance lab. You can use it to retool the freezer chamber if you want. Simply Click on a tile with it in-hand to generate a barrier that will let you go through but not air and heat.
#### Tools

Pipes are reconfigured using tools, you might want to keep a toolbox nearby or have the tools inside your backpack by Click-dragging the toolbox into your backpack. In particular you will use the Wrench.png wrench the most to unwrench and fasten pipes.
#### Tanks

In ordnance, tanks are the objects that actually produce explosions from being overpressurized. However you cannot overpressurize a tank easily by pumping them with regular pumps, which is where ordnance comes in.
#### TTV

The TTV allows you to combine the contents of two tanks together. This will be the thing you need to make large bombs.
### Machines
#### Tank Compressor

The gas compressor is where you do the Gas shell experiments. They, unlike regular blue pumps, does not have a pressure limit and will allow you to overpressurize a tank very easily.
Implosion compressor.gif Anomaly Refinery

Anomaly refinery allows you to insert Tank Transfer Valves into them to compress Anomaly Cores. They are also equipped with a simulation feature for you to test out bombs without actually losing them, NT won't accept that data though for some reason...
#### Doppler Array

The doppler array is a directional device that allows the recording of real explosions. If those explosions happen to be caused by tanks, they can provide insight on the possible causes.

### Notable Mentions

Portable scrubbers and portable pumps are often used to clean or fill a tank.

Thermomachines are also used very often to cool down or heat up a gas.

Lastly, canisters store gas and will also be used to contain exotic or very hot gas.

# Papers and You

To complete experiments, as well as to acquire funding and scientific cooperation, you require the NT Frontier application. This can be downloaded on your department's civilian console, or a device like a laptop or PDA.

To do this, you need to:

- Grab your ID and insert them into a PDA or a modular computer.
- Open the NT Software Hub application and look for the program NT Frontier. It is in the Science tab if you didnt find it. Press download and wait for it to finish.

The application will helpfully list all available experiments as well as their tier requirements. Do note that for experiments which unlock research nodes upon completion, it is not required to reach the maximum tier. However you should endeavor to do so, as you will otherwise earn less funding and cooperation. Do note that you can only publish one paper per experiment and tier. So you cannot re-do the same tier later on to gain more rewards if you publish a worse result early.
### Using disks

In order to publish papers, the relevant file must be on your PDA's internal storage. To do this you will need to:

- Complete the appropriate experiment in the Tachyon-Doppler Array or Tank Gas Compressor.
- Grab a portable hard drive (data disk). These should by lying around near a computer or a doppler array.
- Insert the data disk into the Tachyon-Doppler Array or Tank Gas Compressor and print the experiment to the disk.
- Stick the disk into your PDA or computer and use the File Manager software to copy the file from the disk to the phone.

Now you will be able to select the experiment in NT Frontier and publish your paper!

Scientific Cooperation

Other than funding, publishing papers earns scientific cooperation with the partner you select when publishing the papers. In the partner's overview tab, you can see your relations with each partner. Good relations allow you to purchase discounts on research nodes, which will however degrade the relations. 

# Practical guide to Gaseous Synthesis

The station is in chaos, a cruel wizard has kidnapped the captain and holds him hostage. He will accept bombs as ransom, and you are the only scientist on deck. We got you covered!

Ordnance is about making gas, either for bombs or for gas shells. You can read up on all the gas reactions in the game here.

If you are just starting out, you are recommended to make BZ first, then Tritium, before moving on to the harder gases like Hyper-Noblium.

## BZ Synthesis

BZ requires N2O and Plasma in a low pressure environment to produce. To use this you can use the freezer chamber to both cool down the reactants (drives the pressure down) and to give a larger area for the reaction to occur (also drives the pressure down). 

- Wrench the Plasma Canister.png plasma canister in to the first mixer port. Set the first mixer to 100% Side Node. **Why:** As stated above, one of the ingredients for BZ is Plasma. For the mixer, they are supposed to mix two inputs, but in this case we do not need the oxygen at all so we can route all of the plasma in.

- Wrench the N2O canister in to the second mixer port. Set the second mixer to 66.67% Main Node 33.33% Side Node. **Why:** As stated above, one of the ingredients for BZ is N2O. The ratio is 66.67% to 33.33% to keep the input and consumption the same. Other ratios might cause gas buildup inside the chamber

- Open the valve connecting the Mix Line (yellow) with the Freezer line (purple). **Why:** This will redirect our mixed gas to the freezer chamber.

- Wrench a plasma canister into the freezer port. Turn the thermomachine on and minimize the target temperature. **Why:** The heat exchangers on the freezer turf will need gas to start exchanging heat, Plasma is an exceptional coolant since it absorbs a lot of heat.

    Open the air alarm and look for the scrubber inside the freezer chamber (match the id). Set it to expanded mode and to scrub BZ. **Why:** This will allow us to collect the BZ as they are formed in the chamber.

- Wrench a canister or a portable pump in the output port. **Why:** The BZ collected by the chamber will be deposited to the canister or portable pump. The former is more readily available while the latter allows you to do gas shells very precisely.

- Look for the Chamber Monitor, navigate to the Freezer Chamber selection, and in this order: Lower the injector to 1 L/S, and turn it on. **Why:** This will be the final step that allows our reactants to go inside the chamber. You might be able to optimize it even further by adjusting the input rate up and down as time passes. Aim for somewhere below 50 kPa.

### Addendum

If you overpressurized the gas inside the freeze chamber, you might want to:

- Disconnect the output canister.
- Set the scrubber to siphoning in the Air Alarm.
- Turn on the bypass volume pump.

Though this may not always work, such as when the input line is already at maximum pressure. You can then change the normal gas pump to a volume pump.

## Tritium Synthesis

Tritium is still relatively simple to grasp, but it is prone to failure which can render your workplace hazardous to work in. Don't lose hope if you fail, even experienced players make mistakes.

The production of tritium requires the combustion of plasma inside a heavily oxygenated environment. Tritium also combusts relatively rapidly with oxygen, which means you will need to upgrade the scrubber network to get sizable amounts of it. This guide will assume that you do not have the means to do that.

- Set the Atmos first and second mixer to 100% Main Node. **Why:** We require oxygen in the chamber, this setting will fully pump the oxygen in.

- Open the valve connecting the Mix Line (yellow) with the Burn Line (black). **Why:** This will route the oxygen into the chamber.

- Open the air alarm and look for the scrubber inside the burn chamber. Set it to expanded mode and to scrub only Tritium. **Why:** The first one will allow us to clear the yellow/black line quicker, while the second one will let less tritium burn.

- Click the chamber control panel, and open the interior airlock. Wait for it to cycle. Then enter the outer part of the chamber and maximize the  pump leading in and pump leading out. **Why:** Maximizing the first pump will allow tritium to be produced more quickly, while the second one will let less tritium burn.

- Open the Atmos Monitor, switch the chamber to the Burn Chamber if it isn't already set. Turn on the injector and maximize it. Oxygen should be showing up in the sensor. **Why:** The black line is where our oxygen is currently residing, but the injector starts off. So we need to turn it on first.

- Head back down to the Oxygen Stationary Tanks, use your analyzer on them and turn the first mixer off (Ctrl-Click) once you are satisfied with how much oxygen is in the chamber. **Why:** However much gas you leave in the tanks is completely optional. Keeping a reserve of around 2-3k (around 1-2 canisters) might be a good idea in case you decided to pursue another experiment that needs oxygen.

- Wait for the black and yellow line to empty out and turn the injector off with the Atmos Monitor. The monitor should read around 1-2k moles of oxygen. **Why:** We will need the plasma to be trickled in slowly, turning the injector off first will give us ample time to prepare the plasma.

- Wrench a Plasma Canister.png plasma canister in to the first mixer side port. Set the Side Node to 100% and turn it on. **Why:** We are now ready to route the plasma into the chamber. The black and yellow line should be filling up with unadulterated plasma.

- Activate the burn button. Make sure you don't press the vent button. **Why:** This button will trigger the igniter in the chamber and allow the plasma to ignite.

- Head back to the Atmos Monitor and start trickling the plasma. Start with a small number, turn the injector on, and keep adding the rate slowly until the temperature is above 1.7k Kelvins. You are free to increase or decrease the rate afterwards. **Why:** Tritium is made when there are around 100x as much oxygen as plasma, we trickle the plasma slowly so this ratio is maintained. We also aim for the temperature to be above 1.7k Kelvins because the oxygen consumption is most efficient at that temperature. Higher rates mean more tritium made per second, but it also means a higher burden on your cooling system.

- If all goes well, tritium should be made and collected by the scrubber. Go to the freezer and crank the temperature down. You should wait a bit and then wrench a canister or a portable pump to the output connector port when finished. **Why:** The canister is withheld because wrenching it means a smaller volumetric share for the freezer. Rather than being (200L / Pipe volume), the gas that the freezer can cool directly becomes (200 L / (Pipe volume + Canister volume)).

### Addendum

In most cases, you will need to add more scrubbers to the chamber. You should do this before adding anything to the chamber. To do this simply:

- Grab a firesuit and fire helmet from a Fire Closet, wear them.
- Equip and activate internals.
- Use the Airlock Control door control and open the interior airlock. Wait for it to cycle and then enter it.
- Open the exterior airlock by interfacing with the same console again.
- Unwrench either the scrubber line pump or pipe and replace them with a layer manifold of a suitable color.
- Add four more scrubbers to the chamber. You will most likely need to do this in another layer, feel free to choose any.
- Go out by using the airlock panel once again. Wait for it to cycle.

# Gas Shells

Before playing with bombs directly, you are recommended to try out gas shells first. They are far less punishing and final than a proper bomb test.

To do gas shell experiments, you will need to visit the Tank Compressor.png tank compressor. The tank compressor in essence is an overgrown pump. It is mainly used to burst tanks with exotic contents inside, letting it spew into the collection chamber to be evaluated.

The tank will then either spring a leak or explode, both of which will be contained by the machine. In case of a leak, it's advised to wait for the tank to empty before removing it from the machine. In case of an explosion, all of the gas content will be outputted to the collection chamber.

Upon a succesful ejection or detonation, the collection chamber's gas data will be finalized and recorded into an experiment file. A printable experiment is then available to be printed into a data disk. Gas in the chamber will also be flushed into the output port.

To properly use this contraption, there are two course of action you can take:

- Overpressurize a tank with the experiment gas
        Pros: Very quick to do.
        Cons: Difficult to clean the input port up, less control.
- Prefill a tank with the experiment gas, overpressurize it with another gas in the compressor.
        Pros: Easier to clean the input port up, more control over the number of moles.
        Cons: Takes a bit more time, requires a portable pump in most cases.
        
To do the former, simply:

- Prepare an empty (or default) tank from the Tank Dispenser.png tank dispenser. Insert it into the Tank Compressor.png tank compressor.
- Wrench the portable pump / canister filled with the experiment gas (preferrably cooled) to the input port (green pipe) connector of the tank compressor.
- Maximize the input rate and activate the compressor using the UI (left click the machine)
- Set the Atmos filter to filter only the experiment gas and turn it on.
- Move the original canister/pump with the experiment gas to the side node of the filter.

To do the latter,

- Prepare an empty (has to be empty) tank from the tank dispenser. Empty it with the portable scrubber.
- Prepare a portable pump (canister is not recommended here) filled with the experiment gas.
- Put the empty tank in the portable pump, pump until the mole number you want is reached.

        P = nRT/V
        n being the mole that you want (prefferably the target mole in the NT Frontier), R being the ideal gas constant (8.31), T being the temperature of the portable pump, V being tank volume (70L), and P being the pressure that you want to set in the portable pump. Eyeballing this however, is also perfectly fine.

- Insert the filled tank into the tank compressor.
- Grab a canister of gas that doesn't react with the experiment gas from the gas storage (Nitrogen tends to be rather stable and thus is recommended).
- Wrench the new canister into the input port, turn on the compressor and maximize it.
- Set the filter to filter only the experiment gas and turn it on.
- Move the original pump with the experiment gas to the side node of the filter.

Try and pay attention to the pressure at which tanks leaks or explodes, we might revisit this concept again later.

# Making Research Bombs

A TTV does not explode on its own: it only connects two tanks. The tanks themselves explode.

The explosion depends entirely on how high the pressure is able to rise inside a tank before it destroys itself or leaks out. There are two main ways to do this: 

## Reactionless Explosions
### Principles

Reactionless explosions are more often than not the easiest to produce. They work by letting a hot gas mixture heat up another gas mixture.

In order to do this effectively, we need to do two things:

- Put as much energy as possible to the system.

        The more energy we can fit into the first tank, the bigger the explosion.

- Make the resultant gas mixture extremely easy to heat up while packing as many moles as possible, I.E. low resultant specific heat capacity.

        The lower we can push the resultant gas mixture down, the bigger the explosion.
        
### Execution

We need a hot gas with high specific heat capacity, and a cold gas with low heat capacity. The former will give more energy, while the latter will drive the resultant heat capacity down and allow more moles to be involved.

- The easiest gas to obtain with a reasonably high heat capacity is Plasma Canister.png Plasma.
- The easiest gas to obtain with a reasonably low heat capacity is Nitrogen or Oxygen. Though oxygen also burns with plasma, further adding to it's pressure. 

Procure both canisters and heat the plasma and cool the nitrogen/oxygen using a thermomachine. Simply wrench the canisters to the connector port and adjust the thermomachine directly. 

If a thermomachine is not available. you may relocate a thermomachine from the ordnance chambers or build a new one.

- To do the former, screwdriver the thermomachine, and right-click with a wrench to unwrench it. Left-click with a wrench to rotate it if necessary.
- To do the latter, build a machine frame, procure the circuit and necessary components, and build the thermomachine.

You can flush a thermomachine's air contents by reconstructing it too!

After you procured the thermomachine, connect a connector port to it's input node using a RPD.

## Reaction-Based Explosions

Another method to make explosions is to have exothermic reactions occur inside them. The reactions will drive the temperature up, which in turn drives the pressure up, causing an explosion.

To generate very big theoretical explosions, you will need reactions, especially the very energetic ones like Tritium Combustion and Hyper-Noblium Formation. Both requires tritium which you should already have.

### Production of a Tritium Bomb
#### Principles

Tritium combustion have several main properties. Upon the opening of a valve, the tanks will allow exactly two reaction ticks before exploding. We also know that tritium combustion:

- Needs to happen above 100 Celcius.
- Needs 10 times the oxygen as tritium for the highest energetic burn.
- Consumes half as much oxygen than tritium burnt.
- Burns tritium at 5% of the oxygen each tick, up to half of the tritium per tick.
- Factor three and four means the number of oxygen burnt each tick 2.5% of the oxygen each tick, up to 25% of the oxygen each tick.

All of these factors have led that a 12.85% tritium 87.15% oxygen mixture to be an efficient choice, due to the unique interaction between the reaction ticks and the properties of the tritium burn itself.

In essence, the 12.85% tritium 87.15% oxygen mixture which contains more than 6 times oxygen as Tritium, allowing the burn to happen twice near peak efficiency, with as high reaction rate as one can get.

The first tick will consume around a third of the tritium and five percent of the oxygen. Paving the way for the second tick to also be energetic.

The second tick will consume half of the remaining tritium, leaving a third of the initial tritium left. Letting us make the biggest, baddest bomb possible.

A lower temperature for the tritium-oxygen mix means a higher reaction rate for the two ticks that are allotted to us, but also means a higher energy requirement to exceed the 100 Celcius threshold for the reaction to occur. Keep this in mind when you are upgrading your mix.

#### Execution

We want a 87.15% 12.85% mix of Oxygen and Tritium (in that order) in the payload tank.

A very common temperature to aim for is 43 Kelvins at 2533 kPa, which requires a hot plasma mix of around 800 Kelvins to heat the resultant up to 373.15 Kelvins. A hotter plasma mix is very often desirable here, since hotter plasma means a lower resultant heat capacity, which means a larger temperature increase, which means a larger explosion.

If you wish to follow this recipe, for the cold tank simply:

- Pump up to 325.5 kPa of 43.15 Kelvin tritium into a tank.
- Pump up to 2533 kPa of 43.15 Kelvin oxygen into a tank.
- Analyzer the resulting tank and make sure oxygen is above 65.52%

### Production of a Hyper-Nob Bomb
#### Principles

Hyper-Nob bombs are made using their formation reaction, which when unmoderated by BZ releases a lot of energy. This formation involves Nitrogen and also Tritium.

There are a few notable properties about this reaction:

- Can only occur below 15 Kelvins
- Consumes nitrogen at twice the rate of tritium. Moderated by BZ but we will not include BZ in this mix at all so it's safe to ignore.
- The consumption rate for Nitrogen is equal to 10% of the pooled Nitrogen + Tritium mole count. Tritium consumption is half of this.

Since this reaction occurs on very low temperatures and is incredibly exothermic, it will only happen on one tick. This means we will need to make the first tick occur with as much reaction rate as we can.

If we pay attention to how the reaction rate works with the mole consumption, we can see that we will not need to fill the payload with 50% Tritium as this is incredibly wasteful. It is possible to pad out the reaction with Nitrogen to drive the reaction rate high enough so that all of our tritium is consumed, netting us the most tritium-efficient Hyper-Nob burn possible.

This ratio works out to be 95-5 Nitrogen-Tritium. The burn will consume Nitrogen equal to 10% of the total mole count and more importantly Tritium equal to 5% of the total mole count, leaving us with a full Tritium consumption. Most of the Nitrogen will be left unreacted, but the station has an abundance of Nitrogen so it should be relatively easy to replenish it.

#### Execution

For this, we will need a significant amount of cooled Nitrogen and also  Tritium.

Nitrogen is already available, so grab a canister from the gas storage and cool it down to below 15 Kelvins on an upgraded freezer (Tier 3 parts or better).

Tritium on the other hand needs to be made first, so read up on Tritium Synthesis if you haven't. You will also need to cool it down to below 15 Kelvins using an upgraded freezer.

- Optional: A padding gas like Carbon Dioxide or Oxygen can also be used to have more moles in the mix and thus more pressure once the bomb reacts, producing a bigger explosion. Just make sure they are also cooled to below 15 Kelvins or else they might make the resultant gas mixture too hot to react.

The target mixture is 95-5 Nitrogen-Tritium, we cannot combine both of them inside a tank like in the tritium bomb cold mix, since they will start reacting and explode. So we need to put them in separate tanks. To do this simply:

- Pump up to 2533 kPa of 13 Kelvin Nitrogen to a tank.
- Pump up to 127 kPa of 13 Kelvin Tritium to another tank.
- (Optional) Brim the Tritium tank with 13 Kelvin Carbon Dioxide or Oxygen.
- Analyzer both of the tanks and make sure both of them are below 15 Kelvins and the Nitrogen mole count is about 19 times the Tritium.

Extra note: Unlike the tritium burn reaction, messing up the mole count and the ratio of this mixture is not as debilitating. Your bomb might still be able to explode even if you have a little too much Nitrogen or Tritium, as long as the temperature is below 15 Kelvins. 

# Using Research Bombs

So you made your mix and are here to test it? Great. Lets get you started. 

## Guide to TTV Assembling

Screwdriver your desired assembly to loosen it, and with it in hand hit the TTV. If you need to adjust it afterwards simply use the TTV in hand and press the gear button in the UI.

There are two primary methods for detonating bombs remotely and safely, namely the timer and the remote signalling device.

- The timer is self explanatory. It will detonate the TTV after a certain time has passed. You can start the countdown by using the aforementioned gear button.
- The remote signalling device will open the valve once a signal with a matching frequency and code is sent. Attach one to your TTV, adjust the frequency and/or code, send the bomb to the satelite, and with another signaller send the matching combination.
- Some jokers like to randomly signal the default frequencies of these devices so before you attach one to a bomb you'll want to change the frequency and/or code so that you don't get a nasty surprise.

To attach the tanks, hit the TTV with it in hand. If you need to detach it afterwards simply use the TTV in hand and press the eject button in the UI.

It might be a good idea to deal with the assemblies first before attaching the tanks to prevent accidental detonations. 

## Testing Your Bomb

It is possible to test your bomb without actually losing it by fitting a finished bomb inside an anomaly refinery and using the Run Simulations tab in that machine.

If you are new or unsure about a particular bomb mix, it is recommended to always use an analyzer on the cold and hot tanks before blowing them up. If you are asking for help from other people the information here will be crucial, and if you are already experienced you will immediately know why a bomb went dud.

## Doppler Array

The doppler array is able to capture explosions directly in front of it (indicated by the red light). If the source of the explosion is a tank, it will provide possible causes. These causal data are used to publish papers.

To safely detonate a tank and capture it, you will need to head to the Ordnance Launch Site, put the TTV in the Mass Driver chamber and interface with the control button.

It might be useful to double check your doppler array to make sure it is on. Explosions that occur when the doppler array is off will not be recorded and will be wasted!

You can initiate a launch or open the door and test fire immediately for faster payload delivery. Once the TTV is in the bomb satelite and fully detonated (read the previous section for information on how to detonate your bomb), insert the data disk into the doppler array and print it.

The requirement for the experiments can be read on NT Frontier, complete with available tiers and the target amount for them. Remember that the target amount only refers to the optimal explosion range for the experiment, not the minimum amount! If your range is too low from the target amount however, the experiment may not be published. 

## Anomaly Refining

That funny-looking box in the ordnance launch room does more than just sit around. It's the main way of getting anomaly cores.

What's an anomaly core?

Anomaly cores are essentially an item with the special property of being able to exist only in a very small number (currently eight) per type. They're used to give functionality to several high-end research items, and can be obtained in one of two ways:

- Defusing Anomalies with an analyzer and signaller, or with an Anomaly Neutralizer

- Buying raw cores from Cargo or using the random ones ordnance spawns with, and activating them in the Anomaly Refinery.

The refinery will first take the raw core, then accept a TTV with two tanks attached. If the mixture of the two tanks would have provoked a blast that fulfills its requirements, the refinery will rock the station with an equivalent effect of the actual blast, and the raw core will be spit out as a proper, activated core. You'll also get your TTV back, likely with one of the tanks gone. It's that easy!

Refining more cores will increase the needed blast radius, from 4 light tiles up to 20 light tiles, with increments of 2 per core.

## Final Warning

Seriously, don't go and randomly set bombs on the station if you aren't a syndicate or otherwise an antagonistic character, you WILL get job-banned or even permabanned.

If you manage to accidentally blow up or burn down ordnance and maybe even the surrounding Research department once or twice as a beginner, don't panic and just explain what happened to the admins who will likely contact you. They're usually an understanding bunch and know that mistakes happen. Just make sure to learn from them!

On the other hand, if you DO know what you're doing, the potential damage you can cause to the station can be extreme and sometimes irreversible, very likely changing the course of the round. There are VERY few instances where you can use these bombs as a weapon while being a normal non-antagonist crew member, and even when faced with a situation where it could be used to save the station, use it only as a last resort.