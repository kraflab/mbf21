# MBF21 OPTIONS Lump

The OPTIONS lump (originally from mbf) allows wad authors to set a series of variables that affect engine behaviour. This file contains descriptions of the options as well as examples you can use to approximate old environments.

| Key                   | Description                                                    |
|-----------------------|----------------------------------------------------------------|
| weapon_recoil         | Firing a weapon pushes the player back                         |
| monsters_remember     | Friendly monsters return to old target when losing current one |
| monster_infighting    | Monsters infight                                               |
| monster_backing       | Ranged monsters will back away from close melee targets        |
| monster_avoid_hazards | Monsters avoid hazards such as crushing ceilings               |
| monkeys               | Monsters can climb steep stairs                                |
| monster_friction      | Monsters are affected by friction modifiers                    |
| help_friends          | Friendly monsters prefer targets of friends                    |
| player_helpers        | Number of dogs to spawn                                        |
| friend_distance       | Friendly monsters try to keep at least this distance apart     |
| dog_jumping           | Dogs can jump down from high ledges                            |
| comp_telefrag         | Spawners only telefrag on Map 30                               |
| comp_dropoff          | Discourage / prevent enemies from walking off ledges (?)       |
| comp_vile             | Archviles can create ghosts                                    |
| comp_pain             | Pain elementals don't spawn lost souls if there are over 20    |
| comp_skull            | Lost souls can spawn past impassable lines                     |
| comp_blazing          | Blazing doors have double sounds                               |
| comp_doorlight        | Door lighting changes are abrupt                               |
| comp_model            | Assorted physics quirks and bugs                               |
| comp_god              | God mode is removed in sector 11 & ignored at 1000+ damage     |
| comp_falloff          | Don't pull monsters off ledges they are hanging off of         |
| comp_floors           | Assorted floor bugs                                            |
| comp_skymap           | Don't apply invulnerability palette to skies                   |
| comp_pursuit          | Monsters can infight immediately when alerted                  |
| comp_doorstuck        | Monsters get stuck in door tracks                              |
| comp_staylift         | Monsters don't prefer staying on lifts their target is on      |
| comp_zombie           | Dead players can activate things                               |
| comp_stairs           | Assorted stair bugs                                            |
| comp_infcheat         | ?                                                              |
| comp_zerotags         | Allow tag zero actions                                         |
| comp_respawn          | Monsters not spawned at level start respawn at the origin      |
| comp_soul             | Buggy lost soul bouncing                                       |
| comp_ledgeblock       | Monsters are blocked by ledges (except when scrolling)         |
| comp_friendlyspawn    | Spawned things inherit the friend attribute from the source    |
| comp_voodooscroller   | Voodoo dolls on slow scrollers move too slowly                 |
| comp_reservedlineflag | The line flag 0x0800 disables extended flags                   |

### MBF21 Defaults

```
# General / AI
weapon_recoil 0
monsters_remember 1
monster_infighting 1
monster_backing 0
monster_avoid_hazards 1
monkeys 0
monster_friction 1
help_friends 0
player_helpers 0
friend_distance 128
dog_jumping 1

# Compatibility Flags
comp_telefrag 0
comp_dropoff 0
comp_vile 0
comp_pain 0
comp_skull 0
comp_blazing 0
comp_doorlight 0
comp_model 0
comp_god 0
comp_falloff 0
comp_floors 0
comp_skymap 0
comp_pursuit 1
comp_doorstuck 0
comp_staylift 0
comp_zombie 1
comp_stairs 0
comp_infcheat 0
comp_zerotags 0
comp_respawn 0
comp_soul 0
comp_ledgeblock 1
comp_friendlyspawn 1
comp_voodooscroller 0
comp_reservedlineflag 1
```

### MBF Defaults
```
# General / AI
weapon_recoil 0
monsters_remember 1
monster_infighting 1
monster_backing 0
monster_avoid_hazards 1
monkeys 0
monster_friction 1
help_friends 0
player_helpers 0
friend_distance 128
dog_jumping 1

# Compatibility Flags
comp_telefrag 0
comp_dropoff 1
comp_vile 0
comp_pain 0
comp_skull 0
comp_blazing 0
comp_doorlight 0
comp_model 0
comp_god 0
comp_falloff 0
comp_floors 0
comp_skymap 0
comp_pursuit 0
comp_doorstuck 0
comp_staylift 0
comp_zombie 1
comp_stairs 0
comp_infcheat 0
comp_zerotags 0
comp_respawn 1
comp_soul 1
comp_ledgeblock 0
comp_friendlyspawn 1
comp_voodooscroller 1
comp_reservedlineflag 1
```

### Boom
```
# General / AI
weapon_recoil 0
monsters_remember 1
monster_infighting 1
monster_backing 0
monster_avoid_hazards 0
monkeys 0
monster_friction 0
help_friends 0
player_helpers 0
friend_distance 0
dog_jumping 0

# Compatibility Flags
comp_telefrag 1
comp_dropoff 1
comp_vile 0
comp_pain 0
comp_skull 0
comp_blazing 0
comp_doorlight 0
comp_model 0
comp_god 0
comp_falloff 1
comp_floors 0
comp_skymap 1
comp_pursuit 1
comp_doorstuck 0
comp_staylift 1
comp_zombie 1
comp_stairs 0
comp_infcheat 1
comp_zerotags 0
comp_respawn 1
comp_soul 1
comp_ledgeblock 0
comp_friendlyspawn 1
comp_voodooscroller 0
comp_reservedlineflag 1
```

### Doom 2
```
# General / AI
weapon_recoil 0
monsters_remember 0
monster_infighting 1
monster_backing 0
monster_avoid_hazards 0
monkeys 0
monster_friction 0
help_friends 0
player_helpers 0
friend_distance 0
dog_jumping 0

# Compatibility Flags
comp_telefrag 1
comp_dropoff 1
comp_vile 1
comp_pain 1
comp_skull 1
comp_blazing 1
comp_doorlight 1
comp_model 1
comp_god 1
comp_falloff 1
comp_floors 1
comp_skymap 1
comp_pursuit 1
comp_doorstuck 1
comp_staylift 1
comp_zombie 1
comp_stairs 1
comp_infcheat 1
comp_zerotags 1
comp_respawn 1
comp_soul 1
comp_ledgeblock 1
comp_friendlyspawn 1
comp_voodooscroller 0
comp_reservedlineflag 1
```

### Ultimate Doom
```
# General / AI
weapon_recoil 0
monsters_remember 0
monster_infighting 1
monster_backing 0
monster_avoid_hazards 0
monkeys 0
monster_friction 0
help_friends 0
player_helpers 0
friend_distance 0
dog_jumping 0

# Compatibility Flags
comp_telefrag 1
comp_dropoff 1
comp_vile 1
comp_pain 1
comp_skull 1
comp_blazing 1
comp_doorlight 1
comp_model 1
comp_god 1
comp_falloff 1
comp_floors 1
comp_skymap 1
comp_pursuit 1
comp_doorstuck 1
comp_staylift 1
comp_zombie 1
comp_stairs 1
comp_infcheat 1
comp_zerotags 1
comp_respawn 1
comp_soul 1
comp_ledgeblock 1
comp_friendlyspawn 1
comp_voodooscroller 0
comp_reservedlineflag 1
```
