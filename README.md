# crx_customblips
A simple FiveM /set____blip chat command script for players to use add permanent map blips. This script includes Fire blips, LEO Department blips, Agency blips, Business blips, &amp; Building blips. You may NOT resell or reupload this content as your own!
Or I will find you!!! >:(

# Steps on installing
* Drag and drop crx_customblips into your resource folder
* Add paste the following in your server.cfg
* ensure crx_customblips

# Configuration
config.lua
```
Config = {}

-- Define the blip properties for each type
Config.BlipTypes = {
    house = { sprite = 40, color = 0, scale = 0.8, label = "Player House" },
    building = { sprite = 475, color = 0, scale = 0.8, label = "Office Building" },
    department = { sprite = 60, color = 3, scale = 0.9, label = "LEO Department" },
    business = { sprite = 407, color = 0, scale = 0.8, label = "Business" },
    fire = { sprite = 436, color = 1, scale = 0.8, label = "Fire Department" }
}

-- Add static blips here using vector3 or vector4
Config.StaticBlips = {
    { coords = vec3(425.1, -979.5, 30.7), type = "department", label = "Mission Row PD" },
    { coords = vec4(-139.2, -630.4, 168.8, 0.0), type = "building", label = "Arcadius Business Center" }
}
```
blips.json -- Where to add/edit blips
```
[
    {
        "label": "Davis Sheriff Station",
        "coords": {
            "z": 29.29206085205078,
            "x": 363.4764709472656,
            "y": -1589.7900390625
        },
        "type": "department"
    },
    {
        "label": "La Mesa Highway Patrol Station",
        "coords": {
            "z": 28.23316574096679,
            "x": 841.1737670898438,
            "y": -1304.54736328125
        },
        "type": "department"
    },
    {
        "label": "Vespucci Police Station",
        "coords": {
            "z": 23.4582347869873,
            "x": -1081.9208984375,
            "y": -827.1317749023438
        },
        "type": "department"
    },
    {
        "label": "Del Perro Pier Police Station",
        "coords": {
            "z": 17.47801780700683,
            "x": -1632.639892578125,
            "y": -1022.4345703125
        },
        "type": "department"
    },
    {
        "label": "Vespucci Beach Police Hut",
        "coords": {
            "z": 4.41675424575805,
            "x": -1313.983642578125,
            "y": -1526.9193115234376
        },
        "type": "department"
    },
    {
        "label": "La Puerta Police Station",
        "coords": {
            "z": 25.16750907897949,
            "x": -477.7983093261719,
            "y": -1037.6717529296876
        },
        "type": "department"
    },
    {
        "label": "Rockford Hills Police Station",
        "coords": {
            "z": 38.43224716186523,
            "x": -561.937255859375,
            "y": -131.07354736328126
        },
        "type": "department"
    },
    {
        "label": "Vinewood Police Station",
        "coords": {
            "z": 73.92694091796875,
            "x": 593.6777954101563,
            "y": 1.83166253566741
        },
        "type": "department"
    },
    {
        "label": "Alta Police Station",
        "coords": {
            "z": 45.55009460449219,
            "x": 248.49923706054688,
            "y": -324.3814697265625
        },
        "type": "department"
    },
    {
        "label": "West Vinewood Sheriff Station",
        "coords": {
            "z": 83.84491729736328,
            "x": -505.8853759765625,
            "y": 286.1944580078125
        },
        "type": "department"
    },
    {
        "label": "Bolingbroke Penitentiary State Prison",
        "coords": {
            "z": 45.91439819335937,
            "x": 1690.7491455078126,
            "y": 2591.145751953125
        },
        "type": "department"
    },
    {
        "label": "Sandy Shores Sheriff Station",
        "coords": {
            "z": 43.8123550415039,
            "x": 1842.81201171875,
            "y": 3683.633544921875
        },
        "type": "department"
    },
    {
        "label": "Grapeseed Sheriff Station",
        "coords": {
            "z": 42.1558952331543,
            "x": 1647.06591796875,
            "y": 4884.390625
        },
        "type": "department"
    },
    {
        "label": "Senora Highway Patrol Station",
        "coords": {
            "z": 45.0649185180664,
            "x": 2621.7177734375,
            "y": 5309.06103515625
        },
        "type": "department"
    },
    {
        "label": "Paleto Bay Sheriff Station",
        "coords": {
            "z": 31.71639633178711,
            "x": -449.2481384277344,
            "y": 6011.8466796875
        },
        "type": "department"
    },
    {
        "label": "Ranton Canyon Park Ranger Station",
        "coords": {
            "z": 63.35545349121094,
            "x": -1490.4163818359376,
            "y": 4981.431640625
        },
        "type": "department"
    },
    {
        "label": "Vinewood Beaver Bush Station",
        "coords": {
            "z": 187.64939880371098,
            "x": 383.3603210449219,
            "y": 795.9429321289063
        },
        "type": "department"
    },
    {
        "label": "National Office of Sercurity Enforcement Headquarters",
        "coords": {
            "z": 93.86441040039064,
            "x": 2491.572998046875,
            "y": -384.17724609375
        },
        "type": "department"
    },
    {
        "label": "National Office of Sercurity Enforcement LSIA",
        "coords": {
            "z": 14.02436733245849,
            "x": -883.73876953125,
            "y": -2398.074462890625
        },
        "type": "department"
    },
    {
        "label": "FIB Police Station",
        "coords": {
            "z": 36.38521575927734,
            "x": -593.3323364257813,
            "y": -722.0349731445313
        },
        "type": "department"
    },
    {
        "label": "FIB Headquarters",
        "coords": {
            "z": 45.7515640258789,
            "x": 118.11774444580078,
            "y": -752.8297729492188
        },
        "type": "department"
    },
    {
        "label": "Davis Fire Station",
        "coords": {
            "z": 34.48102188110351,
            "x": 203.52098083496098,
            "y": -1652.1561279296876
        },
        "type": "fire"
    },
    {
        "label": "Rockford Hills Fire Station",
        "coords": {
            "z": 38.06772232055664,
            "x": -631.2800903320313,
            "y": -111.4728546142578
        },
        "type": "fire"
    },
    {
        "label": "Sandy Shores Fire Station",
        "coords": {
            "z": 35.73924255371094,
            "x": 1695.3004150390626,
            "y": 3602.555419921875
        },
        "type": "fire"
    },
    {
        "label": "Paleto Bay Fire Station",
        "coords": {
            "z": 31.43956565856933,
            "x": -367.5111999511719,
            "y": 6117.17724609375
        },
        "type": "fire"
    },
    {
        "label": "Grapeseed Fire Station",
        "coords": {
            "z": 33.91883850097656,
            "x": 2572.303955078125,
            "y": 4672.1044921875
        },
        "type": "fire"
    },
    {
        "label": "Arcade",
        "type": "business",
        "coords": {
            "z": 82.07868194580078,
            "x": -610.001708984375,
            "y": 291.3660278320313
        }
    },
    {
        "label": "Del Perro Plaza",
        "type": "business",
        "coords": {
            "z": 24.62711334228515,
            "x": -1380.8035888671876,
            "y": -741.5433959960938
        }
    }
]
```
* start the server
* ensure the resource has started in your console log
* run "/set_______blip" and boom your done

# Support
[I_AM_FULLYCRX Official Discord](https://discord.gg/6QchSKDY7j)
[Iron Justice Roleplay Official Discord](https://discord.gg/YJXZagSzh7)
