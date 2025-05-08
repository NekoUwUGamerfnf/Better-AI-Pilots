# Better AI Pilots

[Discord Server](https://discord.gg/9wcEdgRyrs)

Give AI Pilots Titans

Spawn With `ent_create npc_pilot_elite` Must Have sv_cheats On Or `entity pilot CreateEntity( "npc_pilot_elite" ) DispatchSpawn( pilot )`

Can Now Spawn With `script SpawnPilot( team )` Team Can Be 1 2/TEAM_IMC 3/TEAM_MILITIA 4 etc

Spawn Scripts Can Have Godmode And Custom Spawn Locations And Angles Example `SpawnPilot( 3, true, < 2000, 2000, 2000 >, < 180, 0, 0 > )` Godmode Is true Location Is < 2000, 2000, 2000 > Angles Is < 180, 0, 0 >

Spawn Scripts Require Team

Spawn Scripts `SpawnPilot( team )` `SpawnPilotWithTitan( team )` `SpawnPilotInTitan( team )`

Don't Use With Attrition Extended Or Grunt Mode