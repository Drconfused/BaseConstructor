Drs_BaseConstructor

<!-- ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ -->
<!-- ~~~~~~~~~~~~~~~~~~Base Constructor - Quests~~~~~~~~~~~~~~~~~~~~~~~ -->
<!-- ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ -->
				Current version 0.02	
					**Drconfused**
						*requires 
							Drconfused_MotorTools_Modifiers
							Drs_Oil_Extractor
<!-- ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ -->
<!-- ~~~~~~~~~~~~~~~~~~~~~~~CONTENTS~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ -->			
		* 	WHATS IN THE MOD?
		*	TO DO/WISH LIST
		*	VERSION HISTORY
		*	MADNESS NOTES
		*	ICON IMAGE USE
		*	OTHER RESOURCES USED, CREDITS AND RIGHTS

<!-- ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ -->
<!-- ~~~~~~~~~~~~~~~~~~~~~~~WHATS IN THE MOD?~~~~~~~~~~~~~~~~~~~~~~~~~~ -->	

	Quest lines
		BaseConstructor
			Quests that require you to get particular blocks and place them and follow an upgrade path. Don't get ahead of yourself with upgrading everything at once and follow the linear upgrade path. Helps unlock better tools early in the game.
		MaterialTrader
			Starts after finishing the BaseConstructor1 quest. This allows you to make a work order that you cash in as a quest reweard if you have the right items in your inventory to trade for the work order you craft in your recipes. So far we have the ability to obtain:
				Cobblestone
				Cement
				Forged Iron
				Forged Steel
				Flagstone Block
				Rebar Frames
				Scrap Iron Frames
				Poured Concrete
				
				You just need the ingredients it normally takes to craft these objects. Every quest gives you 100 dukes and 100 exp, helps a lot early in game.
		SecondBase
			Building outposts
			
	Blocks
		1. Steel Block now upgrades to Stainless Steel Block
		2. Barbed Wire Sheet now has a single upgrade to Barbed Wire Sheet 01 that has 500 damage and downgrades to Barbed wire.
		3. Wood Bars upgrade all the way to Steel bars
		4. Wood Dowel Bars upgrade all the way to Steel loot bars - these bars you can loot through the edges. 
		5. Crushed Cars added
			repair value 
			allow all rotations
			
	Items
		1. SkillBook
			Only skills that are fundamentally learnable through study are added as skillbooks.
		
	Loot
		adds lootgroups:
			questSkillBook
			questConstructionBlocks
			questConstructionMaterials
			questConstructionExtras

<!-- ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ -->
<!-- ~~~~~~~~~~~~~~~~~~~~~~~~TO DO/WISH LIST~~~~~~~~~~~~~~~~~~~~~~~~~~~ -->

	1. Tool related Quests line
			Will have to figure out if tool making should be part of the base constructor series or if it should be its own questline mod independent of the base constructor. Maybe an Economy Series.
		1.1 craft stone axe
				harvest wood, dirt, sand, stone
		1.2 craft iron pickaxe
		1.3 craft steel pickaxe
		1.4 craft nailgun
		1.5 craft quickerpickerupper
		1.6 craft auger
		1.7 craft chainsaw
		1.8 craft hoe
		1.9 craft impact wrench
		1.10 craft proper working gear
				leather gloves, wornboots/gothboots, leather items
	2. Block creation
		2.1 Frames
				flagstone frames
				rebarFrameBlock
				iron frames
				steel frames
		2.2 Solid Blocks
				Flagstone Blocks
				Cobblestone Block
				Concrete Block
				Wet Concrete Block
				Reinforced Concrete Block

	3. Quest Template
		3.1
			What is the most concise template for questing?
			
	4. Items that should be obtainable through quests
		4.1 First aid bandages/kits =  use the questMedical lootgroup
		4.2 Blocks for construction
		4.3 Materials for upgrades or raw construction
		4.4 Base odds and ends
				storage containers
				traps
				doors
					the garageDoorHouse should be activated and have its upgrade line opened.
				windows/glass
				workbench
				forge
				chemistry bench
				cement mixer
		4.4 define and distribute the new and existing questLootItems
			4.4.1 Existing questLootItems
				questAmmo
				questArmor
				questMedical
				questMelee
				questMods
				questRanged
				questSchematics
				questTools
			4.4.2 New questLootItems
				questSkillBook
					these skillbooks only include the skills that theoretically would increase by studying literature. Skills that theoretically require hands on activity to increase are not included.
				questConstructionBlocks
					only basic blocks will be included and won't include the specialized block types.
				questConstructionMaterials
					only materials that are directly involved in biulding and repairing basic construction are included.
				questConstructionExtras
					things like doors, hatches, generator, battery bank, 
				questBaseDefense
					all the typical traps that are used in the biulding of a base are included, also the woodLogSpike is given as an item reward as well.
		4.5 Shipping crates
			Possibly add in the shipping crates. This will have to be tested to see if the crates after placed and downgraded if they contain loot or are empty	
		4.6 Items on enter game
			Potentially change the entityclsases.xml for the starting items on enter game to clean up the file and streamline it a little bit more with beginning game.		
		4.7 Quest Loot system
				Its possible that the loot having more than 8 entries is creating a null reference in the quest system.
				Either reduce the system or create a furthre looting system that either works on the basis of containers or quest.
					Quest Loot System
						Make the icon look like a package
							Construction Reward Package
								using it makes it a quest that auto completes giving the rewards.
					Container System
						Outline further containers that may conflict with other mods.
		4.8 Base constructor go to POI
				a. Define a block that is a Poi marker 1 through 8 for the Base Constructor. 
				b. block is distributed enmass around the biomes at least 10 of each #
				c. 

<!-- ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ -->
<!-- ~~~~~~~~~~~~~~~~~~~~~~~VERSION HISTORY~~~~~~~~~~~~~~~~~~~~~~~~~~~~ -->
	0.03
		Revamp the award system
			
	0.02 	
		adds lootgroups to start balancing rewards and making the quets line more robust and worthwhile
			questSkillBook
			questConstructionBlocks
			questConstructionMaterials
			questConstructionExtras
		Started making the descriptions in the quests more robust to give it more of a roleplaying and belonging feel.
			currently the offer and other descriptions are suffering and could really be advanced.
		Added quest item to activate Second_Base_1 rather than auto give the quest, which the likihood of missing it going into the quest log is high.
		Added oil extractor as a reward in BaseConstructor4
		
	0.01	Unreleased
		Establishing basic questlines:
			BaseConstructor
			MaterialTrader
			ToolTrader
			ResourceCollector
	
<!-- ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ -->
<!-- ~~~~~~~~~~~~~~~~~~~~~~~MADNESS NOTES~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ -->			

	1. I want to continue the building format of the basic survival quests. What is the basis and where do the outcomes point towards?
		Basis is to reward following the upgrade path of basebuilding and to make it feel like it adds an rpg element to the basis of base building.
		The rpg element is the potential discourse and narrative between the player and the Trader. 
		The Trader is need of community, without individuals to trade with a trader is useless. 
	
	2. 
		// After cashing in the initial start quest start the Base Constructor quest.
			Can give it as a note rather then force start or we can see how to make a popup like the initial start quest.
			
				Trader wants
				
				
		//Greetings Survivor, if you have come across this note, be aware that we have set up a system of trades across the habitable land for those that would work hard and bring materials for already made building materials. 
		2.1 We want to start you out small, bring to a trader 
			20 clay 
			or
			20 stone and we will give you 10 flagstone blocks
			
	3. Base Constructor series
		Make it so that this is the quest series right after finding the trader. It should come across like the trader is helping his community grow. It should be a significant reward as far as Dukes go, make it clear that the trader is doing this for insentive to have a good trade partner.
			3.1 Trading basic materials for the recipe equivalent to make them through quests cashed in at the trader.
			3.2 Should they be craftable notes? Or should they be found? How should the quest system work?
				3.2.1 For starters making it a hand it to the trader so it can be assessed how well that works. Adds a little more to the idea of a functional trading system.
	
	4. 

<!-- ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ -->
<!-- ~~~~~~~~~~~~~~~~~~~~~~~ICON IMAGE USE~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ -->

	1. Any usage of other's images/code/objects etc should be included here so that credit is given where credit is due. 
	2. 
	
	
<!-- ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ -->
<!-- ~~~~~~~~~~~OTHER RESOURCES USED, CREDITS AND RIGHTS~~~~~~~~~~~~~~~ -->

*Elucidus - Impact Wrench

	https://www.nexusmods.com/7daystodie/mods/173
	https://7daystodie.com/forums/showthread.php?96954-Luc-s-Modlet-Collection-(Quality-Bonuses-better-stamina-terrain-mv-spd-etc-)&highlight=elucidus

*Manux - A17 Custom Vehicles Modlet (only using the quad specifically in my mod cause it just fits with the idea of being a base constructor item) I am using the modlet version.
	https://7daystodie.com/forums/showthread.php?97001-A17-Custom-Vehicles-Modlet
	
	https://github.com/manux32/7d2d_A17_modlets
	
