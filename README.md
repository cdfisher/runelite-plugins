# Radius Markers
![Icon](icon.png)

## Info
![Illustration of a radius marker in-game](https://user-images.githubusercontent.com/53493631/141151545-25cd9067-29e6-42f2-a663-c1899f41b840.PNG)  
*Radius marker for a barbarian ranger in Barbarian Village*

A radius marker is a way to display the spawn point, attack range, hunt range, max range and/or wander range of an NPC in the game scene, on the minimap or on the world map. You place down a marker by clicking the ![plus icon](../radius-markers/src/main/resources/com/radiusmarkers/add_icon.png) icon in the plugin panel while being logged in-game. This will place the marker at the feet of your character, but the location can easily be adjusted in the panel later. This plugin does **NOT** automatically detect the radius regions for you. See [this plugin's wiki](https://github.com/skretzo/runelite-plugins/wiki#-radius-markers) for information on how you can determine those. Here is a short description of the radius range types as shown in the above illustration image:
- Spawn point
  - The location where the NPC will respawn after being killed.
- Wander range (*roaming range*)
  - The area in which the NPC will pathfind freely inside.
- Max range (*retreat range*, *fleeing range*)
  - The area in which the NPC will follow the player while in combat.
- Aggression range (*aggro range*)
  - The area in which the NPC will attack the player (includes both max range and attack range).
- Retreat interaction range
  - The area in which the player can get the NPC to initiate into retreat mode, and the area in which the NPC will remain in focus/interaction with the player while in retreat mode.
- Attack range
  - The area in which the NPC's attacks are confined to (depends on NPC combat style).
- Hunt range
  - The area in which an aggressive NPC can detect a nearby player and initiate combat.
- Interaction range (*talking range*)
  - The area in which the player can interact (e.g. talk-to) the NPC.

## Panel
![Example of radius marker in the plugin panel](https://user-images.githubusercontent.com/53493631/141155950-e9c3f4a8-72b8-427e-adcf-e1a0cadb829d.PNG)

## Config options
- Default radiuses
  - Wander radius: `5`
  - Max radius: `7`
  - Attack radius: `1`
  - Hunt radius: `1`
  - Interaction radius: `1`
- Default colours
  - Spawn point: ![#FF00FFFF](https://via.placeholder.com/15/00FFFF/000000?text=+) `#FF00FFFF`
  - Wander range: ![#FFFFFF00](https://via.placeholder.com/15/FFFF00/000000?text=+) `#FFFFFF00`
  - Max range: ![#FFFF00FF](https://via.placeholder.com/15/FF00FF/000000?text=+) `#FFFF00FF`
  - Aggression range: ![#FFFF0000](https://via.placeholder.com/15/FF0000/000000?text=+) `#FFFF0000`
  - Retreat interaction range: ![#FF0000FF](https://via.placeholder.com/15/0000FF/000000?text=+) `#FF0000FF`
  - Attack range: ![#FF7F0000](https://via.placeholder.com/15/7F0000/000000?text=+) `#FF7F0000`
  - Hunt range: ![#FFFF7F00](https://via.placeholder.com/15/FF7F00/000000?text=+) `#FFFF7F00`
  - Interaction range: ![#FF00C800](https://via.placeholder.com/15/00C800/000000?text=+) `#FF00C800`
- Border width: `3`
- Show on minimap: ✅ `true`
- Show on world map: ✅ `true`
