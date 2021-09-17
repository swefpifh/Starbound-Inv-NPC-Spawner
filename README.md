# Starbound-Inv-NPC-Spawner

INFORMATIONS :

♦ Compatibility with v1.4.4

♦ Steam page : https://steamcommunity.com/sharedfiles/filedetails/?id=###########

**∴ Open the "invisibleNpcSpawner.object" file and modifiy informations by yours :**

- `npcSpecies : ["human"]` *Race of NPCs. You can use multiple race. Ex: ["human", "avian", etc]*

- `npcType : ["foundryguard"]` *ID of NPC to spawn. You can spawn multiple NPC in the list. Ex: ["npc01", "npc02", etc]*
	
- `npcThreatLevelmin : 1` *Select the minimum and maximum threat level. This will generate a selection in the min and max interval. ex: min:1, max:3, your npc will be able to spawn randomly with a threat level 1, 2 or 3.*

- `npcThreatLevelmax : 6` *If you write 0 in both cases, or if you enter a number in the maximum value that is lower than the minimum value, the level will adapt to the instance.*
	
- `position : [0, 0.5]` *Relative position to spawn at*

- `positionVariance : [10, 0]` *[x,y] size of randomized spawn area, centered on position*
	
- `stock : -1` *Total number of spawns, -1 for infinite*

- `frequency : [2.0, 5.0]` *Cooldown time between spawns (random within range)*

- `trigger : "wire"` *Options include "wire", "interact", "break", null (periodic)*

- `outOfSight : false` *Only spawn where the player can't see*

**∴ You can duplicate the .object file. RChange informations (object's id, species npc, etc) for create a new spawner**

> Mod Pack Permissions : Anyone can use this mod in their mod compilation without the author's consent.

> Mod Assets Permissions : Anyone can alter/redistribute the mod's assets without the author's consent.
