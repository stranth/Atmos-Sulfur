<!--
    ✏️ Optional: Customize the content below to let your community know what you intend to use Discussions for.
-->
### This is a draft and will be updated
# What is this?

  Hullo, I'm out here proposing some changes and additions to sulfur, now that we have sodium based compounds I think the wiggle room for sulfuric acid based medicinces can expand! This time with Atmosian intervention. Sulfuric Acid will be given a Gas counterpart, given what the reagent could do this would be a very dangerous gas to handle, like with most atmos products. The source gas would be something that can sustainably be mined, Sour Gas. 
  
  Sour Gas is a natural gas containing high amounts of the chemical Hydrogen Sulfide. Using this as a base to expand from, took from existing entities that could be used alongside this and found the paperweight that is the Gas Recycler Machine. A reagent buffer could be added to give the machine more functionality with its current reaction of CO2 degradation, the buffer itself would start at 200u, adding in the reagent at 0.14u/mol and a reaction would be given to it immediately. 20u of Carbon would compress into a single diamond.
  
  Because of the unique medicinal and toxic properties of sulfur compounds, nitrogen compoinds will also be added to help round out the chemistry gameplay and as well make some items harder to obtain through normal means, requiring smarter decision making when it comes to employing those items. This will also create a more rounded set of chemicals, having sodium based reagents that and be expanded on and directly assist with these processes.
  
  This Fork will facilitate multiple PRs that focus on single focus additions within this document.
  
## What would this PR change? A summary.

- **Make acids harder to make via Chemistry**
- **Add some related gases to assist with making acids harder to make via Chemistry**
- **Add some reactions that further make acids just harder to make in general.**
- **Add some new acids!**
- **Give some much needed love to our good ol' Gas Recycler Machine, to assist with making acids harder to make and give more opportunity to use it.**
- **Add new atmosphere compositions for toxic and volatile atmospheric planets to give more variety for salvagers.**

### Details!

# What will change in modules:

## Ore Addition Module

### **Star Date Today:** 
  **The mining team gave me a startling report, this planet seems to be rich in ores we haven't heard of since earth. My curiosity led me into the mines, and when I laid my eyes on it. My god.**
##
- Add Aluminium Hydroxide reagent.
  - Should block puking, this is a common antacid. (This will be useful should virology ever come back)
- Add Bauxite Ore. Grinds into 5u Aluminium and 5u Aluminium Hydroxide. Only will be able to spawn in Grasslands.
- Add Platinum reagent. Oh hoh what could it do?
- Add Platinum Ore. Now we have all the rad space valuables. Grinds into 10u Platinum reagent. 
- Add Potassium Nitrate Reagent:
  - Effects(Poison 0.5u) Deals 1 Genetic (It does in fact cause cancer...)
- Add Sodium Nitrate Reagent
  - Slows your metabolism while there is less than 5u of Sodium Nitrate.
- Gunpowder is now produced by mixing 4u of Sodium nitrate with 3u of charcoal and 3u of sulfur, instead of using Potassium. The item produced isn't black enough to be black powder.
- Add Saltpeter: Grinds into 4u sodium nitrate + 4u potassium nitrate + 2u table salt 
###
## Industrial Machine Refactors
### **Engineering Log #11938347**
  **I found this dusty old thing in the storage, seemed to be so heavy its locked in its rotation.... magnets? Anyway I tore it open and what do you know, its a gas compression chamber! This thing is a god damned mess though, I believe using some prior proven methods we can provide a better product! I even found a bunch of diamonds lodged in the thing, that might explain the weight issues... now if only this could be leveraged... Eureka! This will help our processors with that new ore!**

Gale Hurrican
Chief Engineer
DMMMD Chemicals
##
- Update the sprite of the Gas Recycler Machine to resemble a more modern machine.
- Add a reagent buffer to the Gas Recycler Machine of 200u.
- Make the Gas Recycler Machine its own reaction container.
- CO2 degradation in the Gas Recycler Machine will now add 0.07u of Carbon per mol of CO2 processed.
- The Gas Recycler Machine will now output 1 diamond for every 20u of Carbon within it while pressure is higher than 5500 kPa & temp is between 1984.15K & 3773.15K.
- The Gas Recycler Machine will be renamed into the Gas Processor Machine to make its function more obvious.
- Add 10 Diamonds to the recipe for the Industrial Ore Processor. (Diamond teeth grind ya ore go brrrrrr. Harass atmos if you lack the diamonds.)
- Add a reagent buffer to the Industrial Ore processor. 
- Make the IOP its own reaction container.
- Add Aluminium Sheet. Only available from Industrial ore processor. 1 Water 2 Bauxite Ore 1 Coal Ore 1 Salt ore -> 30 Aluminium Sheets
- Add Aluminium Rod. Rod but in shiny new format.
- Shuttle walls and other shuttle specific constructions will now require Aluminium Sheets or Rods repsectively in their construction. The advantage will be less mass of the fixture compared to its steel counterpart or current mass in the case of wallmounts. Uranium and Plasma reinforced glass will be made to need Aluminium rods as well.
###
## Augh! My nose!
### **Star Date A Week Away:**
  **The mining team and I have come across this unforgivable sin of a planet. I'm unsure if we have anything right now to handle this. Advised to crew to return to the station. Upon our return we noticed the ship was covered in some residue, its making the shuttle bay smell awful!**
  
  **Edit: The CMO has advised me that we have found something with great implications for how we do our chemistry as a whole... this planet is one for the databases certainly**
##
- Add Hydrogen Sulfide Reagent: 
  - 2u Hydrogen + 1u Sulfur @ 723.15K -> 1u Hydrogen Sulfide
  - Effect (Poison 0.5u/s): Has a 10% chance to cause vomiting. Deals 1.5 Airloss when there is at least 10u of this reagent. Deals 3 Airloss when there is at least 35u of this reagent. Deals 10 Airloss when there is at least 80u of this reagent. Upon reaching 100u of this reagent you instantly crit.
- Change Sulfuric Acid Recipe:
  - 1u Hydrogen Sulfide + 2u Oxygen -> 1u Sulfuric Acid
- Remove the -1 priorty from hydroxide since it will no longer interfere with the production of Sulfuric Acid.
- Add Quantized Sodium Nitrite Reaction:
  - 10 Sodium Nitrate + 10 Iron -> 10 Sodium Nitrite + 1 Iron ore
  - Effect: (Poison 0.5u/s): Has a 5% chance to block vomiting from the metabolizer if there is less than 1u of this reagent. Removes 2u of Hydrogen Sulfide when theres at least 1.5u of Hydrogen Sulfide present.
- Add an effect to Vitamin reagent: Removes 0.1u of Hydrogen Sulfide when theres at least 0.1u of Hydrogen Sulfide present. (Basically a weaker version of Sodium Nitrate that is readily available and will be helpful to provide for later additions.)
- Add Sodium Nitrate Effect:
  - Removes 0.5u of Hydrogen Sulfide in the metabolizer as long as there is 5u of Hydrogen Sulfide.
###
## Holy shit there's real acid rain in my lungs
### **NT-AUDIOLOG-X229-NO:**
  *Log Playback: Initializing* **THE RD DIED. HE TOOK HIS MASK OFF AND HE DIED. I WENT IN THE ROOM AND THE GAS ANALYZER ONLY READ WATER??? WATER DOESNT ACIDIFY SOMEONE OH GOD OH FUCK OH SHIT.** *End Log, Glory to NanoTrasen*
##
- Add Nitric Oxide Reagent:
  - 4u Ammonia + 5u Oxygen + 2u Platinum @1123.15K -> 4u Nitric Oxide + 2u Platinum + create gas effect for 28.6mol of Water Vapor.
- Add Nitrogen Dioxide Reagent:
  - 4u Ammonia + 7u Oxygen @1173.15K -> 4u Nitrogen Dioxide + create gas effect for 28.6 mol of Water Vapor.
  - 2u Nitric Oxide + 1u O2 -> 2u Nitrogen Dioxide (See below)
  - 1u Nitrogen + 2u Oxygen @1173.15K -> 2u Nitogen Dioxide (This will probably get used for gasses, he fucking died)
- Add Nitric Acid Reagent:
  - 3u Nitrogen Dioxide + 1u Water -> 2u Nitric Acid + Nitric Oxide
- Add Sodium Nitrite Reagent:
  - 1u Nitric Oxide + 1u Nitrogen Dioxide + 2u Sodium Hydroxide -> 2u Sodium Nitrite
- Add a Fume Hood Machine, a T2 service tech. It would be toggleable like condenser machines, while active it would query for events related to adding reagents and then use the dictionary lookup available to reagents to predict the products available to the solution to check if they are going to make a reagent with a gaseous product,  similarly on reaction the reaction container would need to check for a fume hood machine on the tile of the reaction. if no fume hood the reaction spills its gas into the air, else the gas gets transferred to the fume hoods buffer. Don't be the RD that died.
- 1500 Caustic Damage : )

###
## I am become Gas. Destroyer of Water.
### **Engineering Log #G45P155-E-R-093**
  **So the Chemistry nerds have been complaining about some awful god damn smells coming from their new fume hoods. After reading the logs I couldn't find a god damned thing, so I took one of their hoods to peer into its innards. You know they were right, that thing is absolutely rancid, there's signs of corrosion all over the place too. What in the god damn were they mixing?**
##
- Add Sulfur Dioxide Reagent
###
## Yet to be categorised
###

###
- Add Ammonium Nitrate (this is gonna make IEDs harder just you wait): 1u Nitric Acid + 1u Ammonia -> 1u Ammonium Nitrate
- Add two reactions to make AN a hard to store chemical:
  - 1u Ammonium Nitrate @ 503.15K -> create gas 4.76mol Nitrous Oxide + create gas 9.52mol Water Vapor
  - 2u Ammonium Nitrate @ 574.15K -> create gas 9.52mol Nitrogen + create gas 4.76mol Oxygen + create gas 19.04mol Water Vapor.
- Add a reaction threshold:
  - If 30u or more Ammonium Nitrate is produced create an explosion in the reaction container.
###
- Add Nutri-MAX Reagent
  - 1u Ammonium Nitrate + 2u Potassium Nitrate + 2u Phosphorus -> 5u Nutri-MAX
  - A potent industrial fertilizer that gives plants a ton of nutrient, too much will damage the plant to simulate fertilzer burn. (Funny that this is a more accurate rep of a fertilizer, do this in real life but use 4x phosphorus as phosphate rock for a (69-66-88) NPK fertilizer.)
###
- Change Bee bee-haviour. Aha.
  - Make bees seek out sources of pollen randomly.
  - Bees will act as sterile swabs for the purpose of pollentation. (Bees have 4 legs and one body that collect pollen, so technically it is 5 swabs worth of pollen.)
  - A Bee will enter a cleaning state after it has landed at two or more pollen sources.
  - Bees will be blocked by plants based on a factor of their pest resistance.
- Pest Killer now temporarily increases the pest resistance of a plant for some amount of time.

- Reagents will not heat past their boiling point, averaged out by solution mix and solution heat cap.
- The Min of the boiling point of gas reagents or the gas current temperature will be used as the instantiation temperature of a reagent within a condenser.
###
- Reagents will have triple points which will not yet be used for anything but clamping minimum temperatures, this will affect the temperature of spawned gasses.
###
###
## Major Plans
I am looking to break the knees of how atmospherics is calculated currently.


<!--
  For the maintainers, here are some tips 💡 for getting started with Discussions. We'll leave these in Markdown comments for now, but feel free to take out the comments for all maintainers to see.

  📢 **Announce to your community** that Discussions is available! Go ahead and send that tweet, post, or link it from the website to drive traffic here.

  🔗 If you use issue templates, **link any relevant issue templates** such as questions and community conversations to Discussions. Declutter your issues by driving community content to where they belong in Discussions. If you need help, here's a [link to the documentation](https://docs.github.com/github/building-a-strong-community/configuring-issue-templates-for-your-repository#configuring-the-template-chooser).

  ➡️ You can **convert issues to discussions** either individually or bulk by labels. Looking at you, issues labeled “question” or “discussion”.
-->

<p align="center"> <img alt="Space Station 14" width="880" height="300" src="https://raw.githubusercontent.com/space-wizards/asset-dump/de329a7898bb716b9d5ba9a0cd07f38e61f1ed05/github-logo.svg" /></p>

Space Station 14 is a remake of SS13 that runs on [Robust Toolbox](https://github.com/space-wizards/RobustToolbox), our homegrown engine written in C#.

This is the primary repo for Space Station 14. To prevent people forking RobustToolbox, a "content" pack is loaded by the client and server. This content pack contains everything needed to play the game on one specific server.

If you want to host or create content for SS14, this is the repo you need. It contains both RobustToolbox and the content pack for development of new content packs.

## Links

[Website](https://spacestation14.io/) | [Discord](https://discord.ss14.io/) | [Forum](https://forum.spacestation14.io/) | [Steam](https://store.steampowered.com/app/1255460/Space_Station_14/) | [Standalone Download](https://spacestation14.io/about/nightlies/)

## Documentation/Wiki

Our [docs site](https://docs.spacestation14.io/) has documentation on SS14s content, engine, game design and more. We also have lots of resources for new contributors to the project.

## Contributing

We are happy to accept contributions from anybody. Get in Discord if you want to help. We've got a [list of issues](https://github.com/space-wizards/space-station-14-content/issues) that need to be done and anybody can pick them up. Don't be afraid to ask for help either!  
Just make sure your changes and pull requests are in accordance with the [contribution guidelines](https://docs.spacestation14.com/en/general-development/codebase-info/pull-request-guidelines.html).

We are not currently accepting translations of the game on our main repository. If you would like to translate the game into another language consider creating a fork or contributing to a fork.

## Building

1. Clone this repo.
2. Run `RUN_THIS.py` to init submodules and download the engine.
3. Compile the solution.

[More detailed instructions on building the project.](https://docs.spacestation14.com/en/general-development/setup.html)

## License

All code for the content repository is licensed under [MIT](https://github.com/space-wizards/space-station-14/blob/master/LICENSE.TXT).

Most assets are licensed under [CC-BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) unless stated otherwise. Assets have their license and the copyright in the metadata file. [Example](https://github.com/space-wizards/space-station-14/blob/master/Resources/Textures/Objects/Tools/crowbar.rsi/meta.json).

Note that some assets are licensed under the non-commercial [CC-BY-NC-SA 3.0](https://creativecommons.org/licenses/by-nc-sa/3.0/) or similar non-commercial licenses and will need to be removed if you wish to use this project commercially.

