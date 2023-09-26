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
 
