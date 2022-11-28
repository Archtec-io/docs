---
layout: default
title: Changelog
nav_order: 3
last_modified_date: "Sun , 17 Nov 2022 12:24:00 GMT"
---

{: .warning }
> This file is may not up to date.
> All times are UTC+1

Niklp — 21.09.2022 15:08
- Fixed not visible recipes with stairs

Niklp — 22.09.2022 13:46
- Removed 'nss_helicopter'
- Added 'streets'
- Updated 'bees' (ABM speedup)
- Added 'ts_vehicles'
- Fixed not working crafting recipes in 'xdecor'
- Reduced spawn chance of 'sequoia' trees
- Added jump and speed multiplier to mithril boots
 
Niklp — 23.09.2022 17:30
- Fixed crash in forceload restriction
- Notify staff when a player joins with VPN
- Updated 'dummies' (fixed undecleared var warnings)

Niklp — 24.09.2022 08:25
- Fixed crash when digging 'techage:cooler'
- Increased spawn rate of monsters (+50%)
- Updated 'lcdlib'
- Updated 'caverealms_lite' (new obsidian glass recipe)
- Updated 'moretrees'
- Updated 'moreblocks' (More recipe related fixes)
- Fixed a crash in 'chatplus'
 
Niklp — 25.09.2022 20:17
- Decreased max forceload blocks per player to 3
- Removed unused 'Beech' nodes in 'moretrees'
- Added 'Dry ice'

Niklp — 27.09.2022 20:48
- Updated 'titanium' (crafting recipes)
- Override 'digiline:chest'
- Updated 'ethereal' (spong recipe)
- Added crafting recipe for 'Dry ice'

Niklp — 28.09.2022 15:47
- Updated the server to Minetest 5.6.1 (including MTG)
- Updated LuaJIT to latest master
- Updated 'farming'

Niklp — 29.09.2022 20:04
- Fixed crash in 'archtec_teleport'
- Fixed crash in 'pride_flags'
- Updated 'travelnet'
- Updated 'mobs_redo'
- Updated 'mob_horse'

Niklp — 01.10.2022 20:30
- Give every new player a 'Techage construction board'
- Added cheat logger function
- Updated 'mobs_monster' (cleanup)
- Updated 'mobs_animal' (cleanup)
- Updated 'abriglass' (LBM performance)
- Updated 'futil'
- Updared 'unified_inventory' (removed unused buttons)
- Updated 'technic_chests' (removed locked chest recipe)
- Updated 'moreblocks' (removed unused category)
- Updated 'ethereal'(cleanup [2000 lines])
- Updated 'techage' (ingame documentation fixes)
 
Niklp — 02.10.2022 09:14
- Removed not working stairs recipes

Niklp — 03.10.2022 15:43
- Fixed 28 of 31 not working crafting recipes
- Refactored some things in 'archtec_xx' mods
- Updated 'castle_mansonry' (LBM performance)
- Updated 'colored_concrete' (translations)
- Updated 'xdecor' (removed packed ice/new rune recipe)
- Disabled a globalstep in the 'ts_furniture' mod (performance)
 
Niklp — 05.10.2022 07:43
- Better xban notification handler
- Updated 'cblocks' (code tidy)
- Updated 'moreblocks' (circular saw fixes)

Niklp — 07.10.2022 13:58
- Grant the 'forceload' priv automatically when placing a drillbox
- Improved '/playtime' command
- Updated 'ethereal' (moretrees compat)
- Updated 'farming' (faster cocoa generate code)
- Updated 'smartshop' (fixes)
- Updated 'mobs_redo' (tidy code)
 
Niklp — 08.10.2022 16:44
- Increased active block range to 4
- Fixed some recipes
- Added a join ratelimiter
- Updated 'unified_inventory' (tidy code)
- Updated 'xban2' (fix not working discord integration)
- Updated 'mesecons' (hydroturbine recipe fix)

Niklp — 09.10.2022 08:47
- Fixed crafting recipe of palace glas
- Re-enabled darkage Lua mapgen

Niklp — 10.10.2022 16:37
- Added custom /status message
- Improved some functions in 'archtec' mod
- Added delay param to '/sd' command
 
Niklp — 11.10.2022 13:37
- Added 'bushes:BushLeaves_xx' to 'group:leaves' group
- Updated 'abriglass' (pattern recipes)
 
Niklp — 14.10.2022 17:48
- Added 'mapserver' mod to see players on the server map
- Added some help messages
- Fixed crash when sending to long messages
- Updated 'colored_concrete' (redo)
- Updated 'drawers' (allow controller to store item when drawers are full)
- Updated 'ethereal' (changed bush texture)
- Updated 'farming' (changed melone texture)
- Updated 'futil' (performance, mod storage api)
- Updated 'item_drop' (handle old node defs)
- Updated 'smartshop' (futil compat)
- Updated 'mobs_npc' (screwdriver fix)
- Updated 'node_entity_queue' (groups support)
- Updated 'techage' (ethereal leaves support)

Niklp — 15.10.2022 14:36
- Added shortcommands for areas
- Block to put invisible armor into armor stands
- Updated 'colored_concrete' (fix broken translations)
- Updated 'futil' (fixes; new functions)
- Updated 'letters' (code cleanup)

Niklp — 15.10.2022 18:27
- Fixed broken invisible armor
- Updated 'drawers' (reverted last update; idk why)

Niklp — 16.10.2022 12:40
- Added a performance patch to darkage mapgen

Niklp — 22.10.2022 10:08
- Implemented a function to cache privs
- Implemented a function to get online_players faster
- Improved 'item_drop' mod
- Updated 'archtec_pvp' (fixed wrong message formatting)
- Updated 'customskins' (cleanup; performance)
- Updated '3d_armor_ui' (new model based player preview in armor tab)
- Updated 'farming' (fixed drops and recipes)
- Updated 'homedecor' (fixed wrong aligned door textures)
- Updated 'mobs_redo' (improved smooth rotation)
- Updated 'techage' (new isobutane recipe)
- Removed 'player_monoids' (it was too buggy)

Niklp — 22.10.2022 16:58
- Fixed not working VPN blocker

Niklp — 29.10.2022 17:18
- Added a new hunger system based on stamina
- Removed 'hbhunger and 'hudbars'
- Added '/watch' command (staff only)
- Added '/joined' (get first join date of a player)
- Improved '/privs_cache' command
- Added 'archtec_physic' mod
- Added new help messages
- Full redo of 'archtec_vpn_blocker'
- Updated 'action_queues' (bump needed futil version)
- Updated 'customskins' (fixed preview in /skin)
- Updated 'bees' (abm descriptions)
- Updated 'bonemeal' (support for new farming redo plants)
- Updated 'chatplus' (code cleanup)
- Updated 'display_modpack' (on_blast callback)
- Updated 'ethereal' (fixed plant generation)
- Updated 'farming' (added ginger)
- Updated 'futil' (many things)
- Updated 'mobs_animal' (ABM speedup)
- Updated 'mobs_monster' (ABM speedup; new textures)
- Updated 'mobs_npc' (added dialogs)
- Updated 'mobs_redo' (fixed peaceful mode)
- Updated 'moretrees' (no biome lib depend, crafting improvements)
- Updated 'node_entity_queue' (bump needed futil version)
- Updated 'signs_lib' (on_blast callback; custom edit priv)
- Updated 'unified_inventory' (hide disabled buttons)
- Updated 'minetest_game' (disabled not needed LBMs)
 
Niklp — 29.10.2022 20:05
- Fixed a crash in 'archtec_stamina'

Niklp — 30.10.2022 11:35
- Fixed not updating hudbar in 'archtec_stamina'
- Improved /watch and /unwatch

Niklp — 30.10.2022 20:35
- Fixed broken healing

Niklp — 31.10.2022 18:11
- Enabled monitoring for lag detection

Niklp — 01.11.2022 21:14
- Improved and refactored the Archtec bot

Niklp — 06.11.2022 17:02
- Added '/geoip' command (staff only)
- Improved placing of dry ice
- Ratelimited joins to 1 every 3 seconds
- Changed 'biome_lib' elevation range to 0-48
- Updated 'basic_materials' (stripped materials)
- Updated 'bonemeal' (helper functions)
- Updated 'castle_masonry (remove intllib support)
- Updated 'colored_concrete' (fixed translations; maintenance)
- Updated 'digicolor' (mod.conf)
- Updated 'emote' (eye offset)
- Updated 'ethereal' (crystal shovel improvements)
- Updated 'facade' (compressed media files)
- Updated 'farming' (esperanto translations)
- Updated 'futil' (mod.conf)
- Updated 'smartshop' (mof.conf)
- Updated 'mobs_redo' (luacheck)
- Updated 'node_entity_queue' (mod.conf)
- Updated 'plantlife' (things without changes for the server)
- Updated 'ropes' (recipe fix for wood ladder)
- Updated 'techage' (many fixes)
- Updated 'towercrane' (esperanto translations)

Niklp — 13.11.2022 10:05
- Untamed Mobs will not be removed once a map chunk is out of view
- Updated 'itemframes' (logging)
- Updated 'farming' (sugar cube)
- Updated 'areas' (translation fixes)
- Updated 'plantlife' (vines upside down fix)
- Updated 'techage' (documentation)
- Updated 'technic_cnc' (compressed obj files)
- Updated 'archtec_stamina' (fixed healing, try no. 4)
- Updated 'ethereal' (lilac, leaves fix)
- Updated 'futil' (many things)
- Updated 'smartshop' (higher res entity rendering)

LonnySophie — 16.11.2022 21:28
- Fixed healing
- Disabled 'darkage' lua mapgen (performance)

Niklp — 17.11.2022 17:29
- Updated LuaJIT to latest master
- Added some improvements for the healing system (thx Juri)

Niklp — 19.11.2022 15:26
- Remade 'bridger' mod
- Updated 'abriglass' (crafting fixes)
- Removed some 'abriglass' nodes
- Updated 'bonemeal' (support for new plants)
- Updated 'darkage' (ix glas recipes)
- Updated 'farming' (increase barley steps to 8)
- Updated 'homedecor' (fake fire restarts automatically)
- Updated 'mobs_animal' (fix sheeps losing their protection)
- Updated 'mobs_redo' (meta for extra drops)
- Updated 'quartz' (ore is not longer in group:stone)
- Updated 'signs_bot' (fix bot movement)
- Updated 'techage' (detect mesecons correctly)
- Updated 'tubelib2' (fix translations)
- Updated 'xdecor' (move changes into archtec mod)

Niklp — 27.11.2022 10:24 Uhr
- Added some debug tools for performance
- Updated 'moreores' (fix hoe recipes)
- Updated 'drawers' (techage support)
- Updated 'wine' (new textures)
- Updated 'farming' (new textures)
- Updated 'techage' (updated ingame manuals)
- Updated 'mobs_redo' (new textures, meat block)
- Updated 'hopper' (license)
- Updated 'signs_bot' (crash fixes)
- Updated 'bakedclay' (license)
- Updated 'tubelib2' (chinese translation)
- Updated 'signs_lib' (fix wrong usage of default global)
