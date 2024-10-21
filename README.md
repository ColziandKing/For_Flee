# ff
Settler unlocks at Globalization

PolIcons.png
size: 2048, 128
format: RGBA8888
filter: MipMapLinearLinear, Linear
repeat: none
PolicyBranchIcons/Rationality
  rotate: false
  xy: 1164, 4
  size: 50, 50
  orig: 50, 50
  offset: 0, 0
  index: -1
f
PolicyIcons/Planned Economy
  rotate: false
  xy: 1092, 1286
  size: 50, 50
  orig: 50, 50
  offset: 0, 0
  index: -1

PolicyIcons/Workers Faculties
  rotate: false
  xy: 1000, 627
  size: 50, 50
  orig: 50, 50
  offset: 0, 0
  index: -1

PolicyIcons/Entrepreneurship
  rotate: false
  xy: 1856, 708
  size: 50, 50
  orig: 50, 50
  offset: 0, 0
  index: -1

PolicyIcons/Urbanization
  rotate: false
  xy: 452, 7
  size: 50, 50
  orig: 50, 50
  offset: 0, 0
  
PolicyIcons/Urbanization
  rotate: false
  xy: 642, 4
  size: 50, 50
  orig: 50, 50
  offset: 0, 0
  index: -1
PolicyIcons/Urbanization
  rotate: false
  xy: 1632, 1826
  size: 50, 50
  orig: 50, 50
  offset: 0, 0
  index: -1
  
PolicyIcons/Fine Arts
  rotate: false
  xy: 1914, 708
  size: 50, 50
  orig: 50, 50
  offset: 0, 0
  index: -1
  index: -1

PolicyIcons/Elite Forces
  rotate: false
  xy: 1176, 685
  size: 50, 50
  orig: 50, 50
  offset: 0, 0
  index: -1
PolicyIcons/Universal Healthcare
  rotate: false
  xy: 861, 454
  size: 50, 50
  orig: 50, 50
  offset: 0, 0
  index: -1

PolicyIcons/Iron Fist
  rotate: false
  xy: 1458, 1174
  size: 50, 50
  orig: 50, 50
  offset: 0, 0
  index: -1

PolicyIcons/Consulates
  rotate: false
  xy: 1060, 677
  size: 50, 50
  orig: 50, 50
  offset: 0, 0
  index: -1

PolicyIcons/Volunteer Army
  rotate: false
  xy: 1176, 627
  size: 50, 50
  orig: 50, 50
  offset: 0, 0
  index: -1


	{
        "name": "World",
        "era": "Ancient era",
        "uniques": [
            "[+1 Culture] [in all cities]",
		"Only available <after adopting [Piety]>", "Only available <after adopting [Rationalism]>", "Unlocks building the Angkor Wat"
        ],
        "policies": [
            {
                "name": "Populism",
                "uniques": [
                    "[-25]% construction time for [All] improvements",
                    "Free [Worker] appears"
                ],
                "row": 1,
                "column": 1
            },
		
		{
                "name": "Their Finest Hour",
                "uniques": [
                    "[+20]% Great Person generation [in all cities]"
                ],
                "row": 1,
                "column": 3
            },
		{
                "name": "Planned Economy",
                "uniques": [
                    "[+1 Production] [in all cities]",
                    "[+5]% Production when constructing [All] buildings [in all cities]"
                ],
                "row": 1,
                "column": 5
            },
            {
                "name": "Free Religion",
                "uniques": [
                    "[+50]% Production when constructing [Settler] units [in capital]",
                    "Free [Settler] appears"
                ],
                "requires": ["Republic"],
                "row": 2,
                "column": 1
            },
            {
                "name": "Dictatorship of the Proletariat",
                "uniques": [
                    "Each city founded increases culture cost of policies [33]% less than normal",
                    "Empire enters golden age"
                ],
                "requires": ["Citizenship"],
                "row": 2,
                "column": 3
            },
            {
                "name": "Scorched Earth",
                "uniques": [
                    "[+15]% [Gold] [in all cities connected to capital]",
                    "[+1 Happiness] [in all cities connected to capital]",
                    "[-5]% Unhappiness from [Population] [in all non-occupied cities]"
                ],
                "requires": ["Citizenship"],
                "row": 2,
                "column": 5
            },
            {
                "name": "World Complete",
                "uniques": [
                    "Free Great Person",
                    "[+33]% Production when constructing [National Epic] wonders [in all cities]",
                    "[+33]% Production when constructing [National College] wonders [in all cities]",
                    "[+33]% Production when constructing [Circus Maximus] wonders [in all cities]",
                    "[+33]% Production when constructing [Heroic Epic] wonders [in all cities]",
                    "[+33]% Production when constructing [East India Company] wonders [in all cities]",
                    "[+33]% Production when constructing [Grand Temple] wonders [in all cities]",
                    "[+33]% Production when constructing [Ironworks] wonders [in all cities]",
                    "[+33]% Production when constructing [Oxford University] wonders [in all cities]",
                    "[+33]% Production when constructing [Hermitage] wonders [in all cities]",
                    "[+33]% Production when constructing [National Intelligence Agency] wonders [in all cities]",
                    //"[+33]% Production when constructing [National Visitor's Center] wonders [in all cities]",
                    
                    "[+15]% Production when constructing [Monument] buildings [in all cities]",
                    "[+15]% Production when constructing [Library] buildings [in all cities]",
                    "[+15]% Production when constructing [Colosseum] buildings [in all cities]",
                    "[+15]% Production when constructing [Barracks] buildings [in all cities]",
                    "[+15]% Production when constructing [Market] buildings [in all cities]",
                    "[+15]% Production when constructing [Temple] buildings [in all cities]",
                    "[+15]% Production when constructing [Workshop] buildings [in all cities]",
                    "[+15]% Production when constructing [University] buildings [in all cities]",
                    "[+15]% Production when constructing [Opera House] buildings [in all cities]",
                    "[+15]% Production when constructing [Constabulary] buildings [in all cities]",
                    //"[+15]% Production when constructing [Hotel] buildings [in all cities]",
                ]
            }
        ]
    },
