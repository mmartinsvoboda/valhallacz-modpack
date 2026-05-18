# ValhallaCZ Mods Overview

## BepInExPack Valheim

The mod loader. It does not add gameplay features by itself, but it makes the other Valheim mods load. Players need it through r2modman, and the server needs it to run BepInEx plugins.

## AzuCraftyBoxes

Lets crafting and building use materials from nearby chests. This is the "craft/build from nearby storage" mod. It is server-synced and will kick clients that do not have the mod when it is installed on the server.

## AzuAutoStore

Moves nearby dropped items into containers and adds quick store/search behavior. The current default lets players dump inventory into nearby containers with the configured shortcut, while respecting item/container rules. It is server-synced and requires matching client installation.

## Quick Stack - Store - Sort - Trash - Restock

Adds inventory quality-of-life actions such as quick stack, store, sort, trash, restock, and item favoriting. This is mainly player UI/inventory workflow, with server config sync enabled for area stacking/restocking settings.

## AutomaticFuel

Automatically pulls fuel and ore from nearby containers or drops into torches, fires, kilns, smelters, windmills, spinning wheels, and similar stations. The server config controls ranges and behavior where synced.

## AzuAreaRepair

Repairs damaged build pieces in an area around the player when using hammer repair. This is installed on the server and clients, uses ServerSync, and can kick clients that do not have the mod if the server has it installed.

## SleepSkip

Adds sleep voting so night can be skipped when enough players agree. This is installed on the server and clients, uses ServerSync, and prevents one AFK player from blocking sleep forever.

## PlantEasily

Adds farming quality-of-life helpers such as grid planting, cleaner crop placement, bulk harvest, and optional farming workflow shortcuts. This is client-side only and should not be installed on the dedicated server.

## AAA Crafting

Improves the crafting UI with quality-of-life controls such as crafting multiple items, recipe search, and recipe tracking. This is player-side UI/workflow QoL.

## AzuHoverStats

Shows useful hover details for plants, fires, fermenters, chests, and build pieces. This is client-side information QoL.

## ItemCompare

Compares hovered or craftable equipment against currently equipped items. This is client-side UI QoL.

## AzuClock

Adds a small in-game clock. This is client-side UI QoL.

## Practical Rule

If a mod is in this modpack and also on the server, all players should run the same modpack version. The server can sync config for supported mods, but it cannot install missing mods into a player's game.
