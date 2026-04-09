# Buildings

The city data currently defines **24 buildings** split across fixed, military/support, and resource-production roles. All buildings cap at **level 30** in the current JSON data.
| Type | Count | Buildings |
| --- | --- | --- |
| building | 14 | Barracks, Drill Grounds, Stables, Range, Siege Eng. Factory, Depot, Fortress, Market, Embassy, Hall of War, Wishing Well, College, Ancient Dragons Tower, Blacksmith |
| farm | 6 | Farm, Sawmill, Hospital, Military Tent, Iron Mine, Mithril Mine |
| fixed | 4 | Castle, Walls, Turret, Watchtower |

## Default city layout

These buildings exist in the starting city layout or are placed automatically by default.

| Building | Category | Zone | Slot | Demolishable |
| --- | --- | --- | --- | --- |
| Walls | Core & Defense | 1 | 1 | No |
| Watchtower | Core & Defense | 1 | 2 | No |
| Turret | Core & Defense | 1, 1 | 3, 4 | No |
| Castle | Core | 1 | - | No |
| Drill Grounds | Military | 2 | 1 | No |
| Depot | Economy & Support | 2 | 2 | No |
| Wishing Well | Economy & Support | 2 | 3 | No |
| Barracks | Military | 2 | - | No |
| Sawmill | Resource Production | 3 | 1 | Yes |
| Hospital | Military | 3 | 2 | Yes |
| Military Tent | Military | 3 | 3 | Yes |
| Farm | Resource Production | 3 | - | Yes |

## City zones and expansion

The castle starts with three active zones and unlocks more farming space through zone requirements.

| Zone | Default | Slots | Unlock requirements |
| --- | --- | --- | --- |
| Fixed Zone (fixed) | Yes | 5 | Default zone |
| Building Zone 1 (building) | Yes | 14 | Default zone |
| Farming Zone 1 (farm) | Yes | 15 | Default zone |
| Farming Zone 2 (farm) | No | 5 | Wood 30,000; Food 30,000 |
| Farming Zone 3 (farm) | No | 5 | Wood 60,000; Food 60,000; Zone 4 |
| Farming Zone 4 (farm) | No | 5 | Wood 100,000; Food 100,000; Iron 2,000; Zone 5 |
| Farming Zone 5 (farm) | No | 5 | Wood 200,000; Food 200,000; Iron 50,000; Mithril 5,000; Zone 6 |

## Building slot unlocks by Castle level

Castle progression expands how many copies of key building families you can place.

| Castle level | Unlocked limits |
| --- | --- |
| 1 | Farm x4; Sawmill x4; Turret x2 |
| 2 | Military Tent x4 |
| 4 | Hospital x4 |
| 5 | Farm x8; Hospital x6; Military Tent x6; Sawmill x8 |
| 7 | Farm x10; Hospital x8; Military Tent x8; Sawmill x10 |
| 10 | Iron Mine x8 |
| 15 | Mithril Mine x8 |

## Full building reference

This table is the fast index for what each building is meant to support in the current data set.

| Building | Category | Internal type | Max level | Default | Demolishable | Role |
| --- | --- | --- | --- | --- | --- | --- |
| Ancient Dragons Tower | Economy & Support | building | 30 | No | No | Advanced progression support |
| Barracks | Military | building | 30 | Yes | No | Unlocks Infantry troops |
| Blacksmith | Economy & Support | building | 30 | No | No | Item and equipment support |
| Castle | Core | fixed | 30 | Yes | No | Main progression anchor |
| College | Economy & Support | building | 30 | No | No | Research building |
| Depot | Economy & Support | building | 30 | Yes | No | Protected resource storage |
| Drill Grounds | Military | building | 30 | Yes | No | Raises march size |
| Embassy | Economy & Support | building | 30 | No | No | Alliance support |
| Farm | Resource Production | farm | 30 | Yes | Yes | Food production |
| Fortress | Military | building | 30 | No | No | Military progression support |
| Hall of War | Military | building | 30 | No | No | Rally-oriented progression support |
| Hospital | Military | farm | 30 | Yes | Yes | Stores wounded troops |
| Iron Mine | Resource Production | farm | 30 | No | Yes | Iron production |
| Market | Economy & Support | building | 30 | No | No | Economy support |
| Military Tent | Military | farm | 30 | Yes | Yes | Training speed and capacity |
| Mithril Mine | Resource Production | farm | 30 | No | Yes | Mithril production |
| Range | Military | building | 30 | No | No | Unlocks Archer troops |
| Sawmill | Resource Production | farm | 30 | Yes | Yes | Wood production |
| Siege Eng. Factory | Military | building | 30 | No | No | Unlocks Siege troops |
| Stables | Military | building | 30 | No | No | Unlocks Cavalry troops |
| Turret | Core & Defense | fixed | 30 | Yes | No | Static city defense |
| Walls | Core & Defense | fixed | 30 | Yes | No | City defense and trap capacity |
| Watchtower | Core & Defense | fixed | 30 | Yes | No | Fixed city utility |
| Wishing Well | Economy & Support | building | 30 | Yes | No | Wish system building |

