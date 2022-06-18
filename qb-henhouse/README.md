# qb-henhouse
This is a Hen House Job for QBCore that uses qb-target and nh menus this was forked from https://github.com/DrBlackBeard095/Qb-Burgershot all credit goes to him. All I did was turn it into a Henhouse Job!
 

## REQUIREMENTS

PolyZone https://github.com/mkafrin/PolyZone

qb-target https://github.com/BerkieBb/qb-target

nh-context https://github.com/nerohiro/nh-context

## Add this to the shared.lua in qb-core

### Job

```
["henhouse"] = {
		label = "Hen House",
		defaultDuty = false,
		grades = {
            ['0'] = {
                name = "DJ",
                payment = 50
            },
			['1'] = {
                name = "Bartender",
                payment = 75
            },
			['2'] = {
                name = "Bouncer",
                payment = 100
            },
			['3'] = {
                name = "Manager",
                payment = 125
            },
			['4'] = {
                name = "Owner",
				isboss = true,
                payment = 150
            },
        },
	},

``` 

## Add this to qb-management config.lua
```up top
    ['henhouse'] = {
        vector3(-302.1, 6269.16, 31.48),
    },

``` vector secondary
    ['henhouse'] = {
        { coords = vector3(-302.1, 6269.16, 31.48), length = 1.15, width = 2.6, heading = 353.0, minZ = 43.59, maxZ = 44.99 },
    },
```

#### Other than that add your own food items you want and should be good to go!
