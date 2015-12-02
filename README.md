# ArmorStandTools
A full suite of Armor Stand tools for CraftBukkit/Spigot

This is a fork of this original project: https://github.com/St3venAU/ArmorStandTools
Spigot resource page with plugin download: http://www.spigotmc.org/resources/armor-stand-tools.2237/

This forked version
-----------
The improvement patch for PvP, Survival and Creative servers as well as third party plug-ins.
Higher priority death handler to clean up the inventory before other plug-ins like factions (combat tag) and such access the inventory.
Player can not throw away any tools.
Player can not pick up any items in tools mode.
Fills up the inventory with glass so that third party plug-ins will see the inventory is full.
Use this fork if you feel the original is abusable or not working as expected.
Visit us on http://choicecraft.net/

Inspiration
-----------
I wanted to create an armor stand for each kit in my mini-game Fortress Wars that acts out its special ability. I quickly became frustrated with trying to use commands and numeric values to position the legs, arms, body and head of each armor stand, so I created this plugin which allows you to do all of this with ease. Among other features you can create any pose you wish just by holding right click on the tools and moving your cursor up and down on the armor stand. You can then generate the summon command that will re-create the armor stand at any time.

Compatibility
-------------
- Spigot/CraftBukkit 1.8.x

Features
--------
- Summon armor stands.
- Name armor stands.
- Toggle: Gravity, Visibility, Arms, Base, Size, Invulnerability, Equipment Lock.
- Manipulate the x/y/z rotations of the Head, Body, Arms and Legs. The value depends on how high up the armor stand's body you click with the tool (i.e. click near the feet is one extreme, near the top of the head is the other extreme).
- Pick up and move armor stands.
- Armor stand cloning tool.
- Save tool: Automatically generate a command block with the command to summon that armor stand in its current state.
- Player head tool: Give an armor stand the head of a specific player.
- WorldGuard region support.

Commands
--------
- /astools : Give yourself all of the armor stand tools (Note: Clears your inventory)
- /astools reload : Reload the config file
- /ast : Alias for /astools

Permissions
-----------
- astools.command : Permission for the /astools command
- astools.reload : Permission to reload the plugin with /astools reload
- astools.use : Permission for using any of the tools
- astools.clone: Permission to use the clone tool
- astools.cmdblock: Permission to use the save tool (Create a command block)

Config
------
- config.yml - The main config file allows you to set the default starting settings for newly summoned armor stands. This is useful if you plan on creating a lot of armor stands with similar equipment.
- language.yml - Contains all of the strings of text that the player will see. Edit this file if you wish to change the text or translate it into a different language.
