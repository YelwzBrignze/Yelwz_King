# Colziand_Brignze
Colziand Brignze is the ultimate mod made by ColziandKing and YelwzBrignze.

[
	{
				"name": "Prehistory Era Pack",
				"row": 1,
				"uniques": ["[+1 Faith] [in all cities]"],
				"quote": "'The press is the best instrument for enlightening the mind of man, and improving him as a rational, moral and social being.' - Thomas Jefferson"
			},
]
{
				"name": "Ancient Era Pack",
				"row": 3,
				"prerequisites": [""],
				"uniques": ["Improves movement speed on roads"],
				"quote": "'The press is the best instrument for enlightening the mind of man, and improving him as a rational, moral and social being.' - Thomas Jefferson"
			},
  {
				"name": "Classical Era Pack",
				"row": 4,
				"prerequisites": [""],
				"uniques": ["Improves movement speed on roads"],
				"quote": "'The press is the best instrument for enlightening the mind of man, and improving him as a rational, moral and social being.' - Thomas Jefferson"
			},
{
				"name": "Medieval Era Pack",
				"row": 8,
				"prerequisites": [""],
				"uniques": ["Improves movement speed on roads"],
				"quote": "'The press is the best instrument for enlightening the mind of man, and improving him as a rational, moral and social being.' - Thomas Jefferson"
},
	{
				"name": "Renaissance Era Pack",
				"row": 8,
				"prerequisites": [""],
				"uniques": ["Improves movement speed on roads"],
				"quote": "'The press is the best instrument for enlightening the mind of man, and improving him as a rational, moral and social being.' - Thomas Jefferson"
	},
	{
				"name": "Modern Era Pack",
				"row": 8,
				"prerequisites": [""],
				"uniques": ["Improves movement speed on roads"],
				"quote": "'The press is the best instrument for enlightening the mind of man, and improving him as a rational, moral and social being.' - Thomas Jefferson"
	},
	{
				"name": "Atomic Era Pack",
				"row": 8,
				"prerequisites": [""],
				"uniques": ["Improves movement speed on roads"],
				"quote": "'The press is the best instrument for enlightening the mind of man, and improving him as a rational, moral and social being.' - Thomas Jefferson"
	},
	{
				"name": "New Era Pack",
				"row": 8,
				"prerequisites": [""],
				"uniques": ["Improves movement speed on roads"],
				"quote": "'The press is the best instrument for enlightening the mind of man, and improving him as a rational, moral and social being.' - Thomas Jefferson"
	},
	{
				"name": "Contempory Era Pack",
				"row": 8,
				"prerequisites": [""],
				"uniques": ["Improves movement speed on roads"],
				"quote": "'The press is the best instrument for enlightening the mind of man, and improving him as a rational, moral and social being.' - Thomas Jefferson"
	}
[
  {
    "name": "Pledge to Protect",
    "description": "Our people deserve to be protected by the likes of you. By signing a Protection Pedging, you'll confirm the bond that ties us.",
    "influence": 20,
    "duration": 30
  },
  {
    "name": "Denounce Civilization",
    "description": "Our people are in a huge problem because of the likes of them.",
    "influence": 10,
    "duration": 30
  }
 ]
[128,255,0]
[
	{
		"name": "God",
		"baseHappiness": 15,
		"extraHappinessPerLuxury": 1,
		"researchCostModifier": 0.9,
		"unitCostModifier": 0.5,
		"unitSupplyBase": 10,
		"unitSupplyPerCity": 3,
		"buildingCostModifier": 0.5,
		"policyCostModifier": 0.5,
		"unhappinessModifier": 0.4,
		"barbarianBonus": 0.75,
		"barbarianSpawnDelay": 5,
		"playerBonusStartingUnits": ["Settler", "Settler", "Worker", "Scout", "Era Starting Unit"], // Note that the units from Eras.json are added to this pool. This should only contain bonus starting units.
		"aiCityGrowthModifier": 1.6, // that is to say it'll take them 1.6 times as long to grow the city
		"aiUnitCostModifier": 1.75,
		"aiBuildingCostModifier": 1.6,
		"aiWonderCostModifier": 1.6,
		"aiBuildingMaintenanceModifier": 1,
		"aiUnitMaintenanceModifier": 1,
		"aiUnitSupplyModifier": 0,
		"aiFreeTechs": ["Pottery","The Wheel"],
		"aiMajorCivBonusStartingUnits": ["Settler", "Worker", "Scout", "Era Starting Unit", "Era Starting Unit", "Era Starting Unit"],
		"aiCityStateBonusStartingUnits": [],
		"aiUnhappinessModifier": 1,
		"aisExchangeTechs": false,
		"turnBarbariansCanEnterPlayerTiles": 5,
		"clearBarbarianCampReward": 50
	}
]
{
		"name": "Maori Warrior",
		"unitType": "Sword",
		"movement": 2,
		"strength": 8,
		"cost": 40,
		"obsoleteTech": "Metal Casting",
		"promotions": ["Haka War Dance"],
		"upgradesTo": "Swordsman",
		"attackSound": "nonmetalhit"
	},
	{
		"name": "Jaguar",
		"unitType": "Sword",
		"movement": 2,
		"strength": 8,
		"cost": 40,
		"obsoleteTech": "Metal Casting",
		"promotions": ["[Jaguar] ability","Woodsman"],
		"upgradesTo": "Swordsman",
		"attackSound": "nonmetalhit"
	},
 {
		"name": "War Chariot",
		"unitType": "Archery",
		"movement": 5,
		"strength": 6,
		"rangedStrength": 10,
		"cost": 56,
		"requiredTech": "The Wheel",
		"upgradesTo": "Knight",
		"obsoleteTech": "Chivalry",
		"uniques": ["No defensive terrain bonus", "Rough terrain penalty"],
		"attackSound": "arrow"
	},
 {
		"name": "Kolmeiah",
		"leaderName": "Aethaniel Ziander Kadllero",
		"adjective": ["Kolmeiahn"],
		"startBias": ["Grassland","Coast"],
  	        "preferredVictoryType": "Cultural",
		"favoredReligion": "Christianity",

		"startIntroPart1": "",
		"startIntroPart2": "",
		"declaringWar": "Prepare to lose your empire of opression!",
		"attacked": "You will see how fruitless this will be for you. Wait and see.",
		"defeated":  "I hope you treat my people good, don´t take away their happiness. Our love is in the Saviour.",
		"introduction":  "Greetings! This is Kolmeiah, our wonderful land. Want a kiss?",
		"neutralHello": "Hello There.",
		"hateHello": "Assh, what do you want?",
		"tradeRequest": "I  thought you might be intested in this...",

	        "outerColor": [0,0,0],
		"innerColor": [255,255,0],

		"uniqueName": "Kolmeiahn World",
		"uniques": ["\"Borrows\" city names from other civilizations in the game","Provides [1] [Citrus]","Provides [1] [Sugar]",
			"[+5]% [Production] <when between [20] and [200] Happiness>","Starts with [The Wheel]","Starts with [Mining]"],

		"cities": ["Kolmeiah","Coola","Indor"]
	},
		{
		"name": "Jeoxwin",
		"leaderName": "Jaine Dolxwin",
		"adjective": ["Jeoxwii"],
		"startBias": ["Tundra"],
  	        "preferredVictoryType": "Cultural",
		"favoredReligion": "Judaism",

		"startIntroPart1": "",
		"startIntroPart2": "",

		"declaringWar": "Prepare to lose your empire of opression!",
		"attacked": "You will see how fruitless this will be for you. Wait and see.",
		"defeated":  "I hope you treat my people good, don´t take away their happiness. Our love is in the Saviour.",
		"introduction":  "Greetings! This is Jeoxwin, our wonderful land.",
		"neutralHello": "Hello There.",
		"hateHello": "Assh, what do you want?",
		"tradeRequest": "I  thought you might be intested in this...",

	        "outerColor": [0,255,255],
		"innerColor": [0,102,0],

		"uniqueName": "Jeoxwii Spirit",
		"uniques": ["Can spend Gold to annex or puppet a City-State that has been your ally for [20] turns.","Provides [1] [Marble]","Provides [1] [Stone]",
			"\"Borrows\" city names from other civilizations in the game",
			"Receive a free Great Person at the end of every [Maya Long Count calendar cycle] (every 394 years), after researching [Theology]. Each bonus person can only be chosen once.",
			"Once The Long Count activates, the year on the world screen displays as the traditional Mayan Long Count."],

		"cities": ["Jeoxwin","Keoland","Heirland"]
	},
	{
		"name": "Ceygoa",
		"leaderName": "High Magistrate like President",
		"adjective": ["Ceygoa"],
		"startBias": ["Coast"],
  	        "preferredVictoryType": "Cultural",
		"favoredReligion": "Christianity",

		"startIntroPart1": "",
		"startIntroPart2": "",

		"declaringWar": "Prepare to lose your empire of opression!",
		"attacked": "You will see how fruitless this will be for you. Wait and see.",
		"defeated":  "I hope you treat my people good, don´t take away their happiness. Our love is in the Saviour.",
		"introduction":  "Namaste! Friends, you are in our hospitality. Would you want something to drink or eat?",
		"neutralHello": "Namaste.",
		"hateHello": "What! You come to commerce?",
		"tradeRequest": "I come to commerce...",

	        "outerColor": [0,153,76],
		"innerColor": [255,51,153],

		"uniqueName": "Union of States",
		"uniques": ["Can spend Gold to annex or puppet a City-State that has been your ally for [15] turns.","[+5]% [Science] <while the empire is happy>",
			   "Cannot build [Settler] units","[+1 Culture, +1 Gold, +1 Science, +1 Happiness, +1 Food, +1 Production] [in this city]",
				"[+20]% Strength <when fighting units from a Civilization with more Cities than you>",
				"Provides [1] [Incense]","Provides [1] [Gems]","[+1 Food, +1 Gold] from [All] tiles [in all cities]","[+50]% [Gold] [in capital]",
			    "Gain a free [Harbor] [in all coastal cities]"],

		"cities": ["Ceygoa"]
	},
