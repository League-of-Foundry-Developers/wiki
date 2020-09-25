---
title: Community Unlisted Modules
description: 
published: true
date: 2020-09-25T17:07:38.535Z
tags: 
editor: markdown
dateCreated: 2020-09-25T02:02:48.214Z
---

Get Modules for Foundry VTT on the official site: [https://foundryvtt.com/packages/](https://foundryvtt.com/packages/)

The list below is an unofficial list of unlisted game modules.

# Foundry VTT Modules (Universal)

Foundry modules that work across all or most systems are noted here. These may include reskins, general improvement mods, and more.

---

## Chat Autoloader

* **Author**: Moerill#7205 on Discord. He accepts donations at his [PayPal](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=FYZ294SP2JBGS&source=url).
* **Translation Support**: EN (full)
* **Foundry VTT Compatibility**: 0.4.1
### Link(s) to Module
* [https://gitlab.com/moerills-fvtt-modules/chat-autoloader](https://gitlab.com/moerills-fvtt-modules/chat-autoloader)
* [https://gitlab.com/moerills-fvtt-modules/chat-autoloader/raw/master/chat-autoloader/module.json](https://gitlab.com/moerills-fvtt-modules/chat-autoloader/raw/master/chat-autoloader/module.json)

### Description
This module improves loading times by only rendering the last few chat messages at page load. Older messages will automatically get rendered while scrolling to the top. (This behavior is similar to e.g. scrolling in Discords chat)

---

## Create Actors from Folder
* **Author**: _cody#4113 on Discord
* **Version**: 0.2.0
* **Foundry VTT Compatibility**: 0.5.0+
* **System Compatibility (If applicable)**: N/A
* **Module Requirement(s)**: N/A
* **Module Conflicts**: N/A
* **Translation Support**: EN (full)

### Link(s) to Module
* [https://github.com/crobibero/fvtt-create-actors-from-folder](https://github.com/crobibero/fvtt-create-actors-from-folder)
* [https://raw.githubusercontent.com/crobibero/fvtt-create-actors-from-folder/master/module.json](https://raw.githubusercontent.com/crobibero/fvtt-create-actors-from-folder/master/module.json)

### Description
Recursivly creates actors from images in specified folder

---

## FFG Roller

* **Author**: Petep, @petep#0441 on Discord
* **Version**: 0.2
* **Foundry VTT Compatibility**: 0.3+
* **System Compatibility (If applicable)**: Universal, but you'll want to probably use it with the simple system
* **Module Requirement(s)**: None
* **Module Conflicts**: None
* **Translation Support**: EN (full)

### Link(s) to Module
* [https://github.com/petepeg/FFG-Roller](https://github.com/petepeg/FFG-Roller)

### Description
This adds a simple dice rolling window for the special dice used in Fantasy Flight Games Star Wars RPG and Genesys. 

---

## Foundry Pin

* **Author**: [Fyorl#1292](https://kim.mantas.me.uk)
* **Version**: 2.0
* **Foundry VTT Compatibility**: 0.4.4+
* **Translation Support**: N/A

### Link to Module

* [https://bitbucket.org/Fyorl/foundry-pin](https://bitbucket.org/Fyorl/foundry-pin)
* [https://bitbucket.org/Fyorl/foundry-pin/raw/master/module.json](https://bitbucket.org/Fyorl/foundry-pin/raw/master/module.json)

### Description

Allows the user to pin windows which will be re-opened automatically the next time you open foundry.

---

## Grape-Hud

* **Author**: grape_juice#2539 on Discord, support on [Patreon](https://www.patreon.com/foundry_grape_juice).
* **Version**: 0.0.10
* **Foundry VTT Compatibility**: 0.6.0+
* **System Compatibility (If applicable)**: Universal
* **Module Requirement(s)**: None
* **Module Conflicts**: None
* **Translation Support**: EN (full)

### Link(s) to Module
* [https://gitlab.com/jesusafier/grape-hud](https://gitlab.com/jesusafier/grape-hud) 
* [https://gitlab.com/jesusafier/grape-hud/-/jobs/artifacts/master/raw/module.json?job=build-module
](
https://gitlab.com/jesusafier/grape-hud/-/jobs/artifacts/master/raw/module.json?job=build-module
) 

![](https://i.imgur.com/g3K34hm.gif)
![](https://i.imgur.com/RhLdrKl.gif)

### Description

Diablo style Health and Mana orbs module for foundryVTT.

Currently has the following features:

- HP as health orb
- Spell slots as mana orb
- Shows up only for players

---

## Grape_Juice - Manual Roll

* **Author**: grape_juice#2539 on Discord, support on [Patreon](https://www.patreon.com/foundry_grape_juice).
* **Version**: 0.0.2
* **Foundry VTT Compatibility**: pre 0.7.x
* **System Compatibility (If applicable)**: Universal
* **Module Requirement(s)**: None
* **Module Conflicts**: None
* **Translation Support**: EN (full)

### Link(s) to Module
* [https://gitlab.com/fusafier/grape_juice-manual-roll](https://gitlab.com/jesusafier/grape_juice-manual-roll) 
* [https://gitlab.com/jesusafier/grape_juice-manual-roll/-/jobs/artifacts/master/raw/module.json?job=build-module](https://gitlab.com/jesusafier/grape_juice-manual-roll/-/jobs/artifacts/master/raw/module.json?job=build-module) 

### Description
Just a proof-of-concept for hooking into the roll system on pre 0.7.x

Enabling the module will cause any roll you attempt to make open up a prompt that requests the outcome of a die roll.

---

## Haste

* **Author**: grape_juice#2539 on Discord, support on [Patreon](https://www.patreon.com/foundry_grape_juice).
* **Version**: 0.4.9
* **Foundry VTT Compatibility**: 0.6.0+
* **Module Requirement(s)**: None
* **Module Conflicts**: None
* **Translation Support**: EN

### Link(s) to Module
* [https://gitlab.com/jesusafier/haste](https://gitlab.com/jesusafier/haste) 
* [https://gitlab.com/jesusafier/haste/-/jobs/artifacts/master/raw/module.json?job=build-module](https://gitlab.com/jesusafier/haste/-/jobs/artifacts/master/raw/module.json?job=build-module)


### Description
An experimental performance enhancement tweak modules for FoundryVTT it has 2 features:

- Wall fix - patches the FOW LOS FOV calculation to be much more efficient using spatial grid calculations. Big words that mean performance is basically unchanged when running 4000+ walls and 50+ light sources on large scenes.
- Adaptive GPU FPS - Stops the canvas redraws when no changes occurred in the scene, reduces GPU usage to 0% unless a token moves or the canvas is panned. Best used when disabling cursor pointers. When using this options you can set the FPS limiter to 60fps.

---

## Image Drop

* **U~man**: U~man#2374, contributions are welcome on core features, translations and new templates
* **Version**: 0.0.1
* **Foundry VTT Compatibility**: 0.5.0
* **System Compatibility (If applicable)**: Universal
* **Module Requirement(s)**: None
* **Module Conflicts**: None known
* **Translation Support**: Not applicable

### Link(s) to Module
* [https://gitlab.com/mesfoliesludiques/foundryvtt-image-drop](https://gitlab.com/mesfoliesludiques/foundryvtt-image-drop)
* [https://gitlab.com/mesfoliesludiques/foundryvtt-image-drop/-/raw/master/module.json](https://gitlab.com/mesfoliesludiques/foundryvtt-image-drop/-/raw/master/module.json)

### Description
Allows dropping images from journal entries to the canvas as tiles.

---

## Image Previewer

* **Author**: Felix#6196 on Discord, accepts donations via paypal, felix.mueller.86@web.de
* **Version**: 0.4
* **Foundry VTT Compatibility**: 0.4.4+
* **System Compatibility (If applicable)**: universal
* **Module Requirement(s)**: none
* **Module Conflicts**: none
* **Translation Support**: EN (full)

### Link(s) to Module
* [https://github.com/syl3r86/image-previewer](https://github.com/syl3r86/image-previewer)
* [https://raw.githubusercontent.com/syl3r86/image-previewer/master/module.json](https://raw.githubusercontent.com/syl3r86/image-previewer/master/module.json)

### Description
A little app to preview images on hover in the file picker menu.
#### Installation
1. Download the image-previewer.zip
2. Unzip it into FoundryVTT/resources/app/public/modules
3. Restart Foundry if it was running.
4. Enable the module in the Module Configuration

---

## Lancer Condition Icons

* **Author**: Eranziel#0410 on Discord
* **Version**: 0.2.1
* **Foundry VTT Compatibility**: 0.5.x+
* **System Compatibility (If applicable)**: universal
* **Module Requirement(s)**: none
* **Module Conflicts**: none
* **Translation Support**: EN (full)

### Link(s) to Module
* [https://github.com/Eranziel/lancer-conditions](https://github.com/Eranziel/lancer-conditions)
* [https://github.com/Eranziel/lancer-conditions/raw/master/module.json](https://github.com/Eranziel/lancer-conditions/raw/master/module.json)

### Description
Adds a variety of condition/status icons for tokens, which are the wonderful work of Cancermantis and Hayley on the Lancer Discord (Pilot.NET). Aimed at Lancer, but not restricted to that system. Includes per-world settings to either keep or replace the stock Foundry status icons, and to select which sub-set(s) of icons from this module to enable.

---

## Scaled Labels

* **Author**: imposeren#3557 on Discord
* **Version**: 0.1
* **Foundry VTT Compatibility**: 0.5.5+
* **System Compatibility (If applicable)**: Universal
* **Module Requirement(s)**: None
* **Module Conflicts**: May conflict with other modules that override `Token.prototype._drawNameplate`, or `Ruler.prototype._onAddWaypoint`
* **Translation Support**: EN (full)

### Link(s) to Module
* [foundry-scaled-labels on bitbucket](https://bitbucket.org/imposeren/foundry-scaled-labels)
* [module.json](https://bitbucket.org/imposeren/foundry-scaled-labels/raw/master/module.json)

### Description
Scale labels of rulers and token nameplates when zoomed-out.

---

## SVG Loader

* **Author**: Moerill#7205 on Discord. He accepts donations at his [PayPal](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=FYZ294SP2JBGS&source=url).
* **Translation Support**: EN (full)
* **Foundry VTT Compatibility**: 0.3+
### Link(s) to Module
* [https://gitlab.com/moerills-fvtt-modules/svg-loader](https://gitlab.com/moerills-fvtt-modules/svg-loader)
* [https://gitlab.com/moerills-fvtt-modules/svg-loader/raw/master/module.json](https://gitlab.com/moerills-fvtt-modules/svg-loader/raw/master/module.json)

### Description
This module allows to load walls, lights and sources through .svg files, provided e.g. by DungeonFog.


---

# Foundry VTT Modules for DnD 5E

Foundry modules that work within Dungeons and Dragons 5th Edition are noted here. These may include NPC compendiums that may be legally shared, world saves, character sheet mods, and much, much more.

---

## MyBeyond-Theme

* **Author**: Frederik Eschmann (Aylas#4838 on Discord; FreddyEs on GitHub)
* **Version**: 1.0.0 (2020-02-09)
* **Foundry VTT Compatibility**: 0.4.5+
* **System Compatibility (If applicable)**: D&D 5e v0.81+
* **Module Requirement(s)**: None
* **Module Conflicts**: overrites default character sheet styles, may cause issues with other character sheets

### Link(s) to Module
* [https://fvtt-modules.eschmann.online/](https://fvtt-modules.eschmann.online/)
* [https://fvtt-modules.eschmann.online/mybeyond-theme/module.json](https://fvtt-modules.eschmann.online/mybeyond-theme/module.json)

### Description
A simple css overwrite that brings the character sheet into a DnDBeyond like style without changing the function of the character sheet.
Note: In Version 1.0.0, this module will also add styles for the ChatLog Messages and Chat Input, but will be made optional in a later version.

---

## Roll20 Converter

* **Author**: KaKaRoTo#4756 on Discord. His Patreon can be found here: [https://www.patreon.com/kakaroto](https://www.patreon.com/kakaroto)
* **Version**: 0.8.8
* **Foundry VTT Compatibility**: 0.4.0+
* **System Compatibility (If applicable)**: Dungeons and Dragons 5th Edition, Universal
* **Module Requirement(s)**: None in Foundry, though module requires a campaign exported from Roll20 using KaKaRoTo’s export tool.
* **Module Conflicts**: None known.
* **Translation Support**: EN (full)

### Link(s) to Module
* The module is paywalled, and requires subscribing to KaKaRoTo’s [Patreon](https://www.patreon.com/kakaroto).

### Description 
This module is a PC application that imports most facets of a Roll 20 campaign, including scenes, walls, dynamic lighting, character sheets (D&D 5e), handouts, chat logs and more. 

Bear in mind that exporting a campaign from Roll20 may violate the EULA.

---

## Summoner

* **Author**: Jon Whitehouse Discord@MTGCarver#7753
* **Version**: 0.1.1
* **Foundry VTT Compatibility**: 0.6.0
* **System Compatibility (If applicable)**: DnD5e
* **Module Requirement(s)**: None
* **Module Conflicts**: None
* **Translation Support**: None

### Link(s) to Module
* https://github.com/Jonwh25/summoner
* https://raw.githubusercontent.com/Jonwh25/summoner/master/module.json

### Description
This FoundryVTT Module adds a simple compendium pack to help with DnD5e spells that summon creatures. It is nothing fancy. My players were casting find familiar and I tried to use the npc creatures that are in the DnD5e system and it wasn't working. So all I did was create actor/player types for each creature they could summon.

Hope this saves you some time.

Right now this only supports the following spells:

*Find Familiar
*Unseen Servant

---


# Foundry VTT Modules for GURPS

Foundry modules that work within GURPS 4th Edition are noted here. These may include NPC compendiums that may be legally shared, world saves, character sheet mods, changes to roll tables, etc.


## GURPSModule

* **Author**: Kalos#9376 on Discord
* **Version**: 0.2
* **Foundry VTT Compatibility**: 0.4.5
* **System Compatibility (If applicable)**: Universal (unless any others rewrite the ruler label!)
* **Module Requirement(s)**: None
* **Module Conflicts**: None.
* **Translation Support**: English

### Link(s) to Module
* [https://github.com/kalminos/GURPSmodule](https://github.com/kalminos/GURPSmodule) 
* [https://raw.githubusercontent.com/kalminos/GURPSmodule/master/module.json](https://raw.githubusercontent.com/kalminos/GURPSmodule/master/module.json) 

### Description
This mod changes the foundry ruler label to print out the GURPS range modifier from the size speed and range table. There are also some chat commands to roll on rolltables for hit location (off the grand unified hit location table), range, size modifier, fear results, critical hits, malfunctions, and more. Type in !ghelp into the chat for a bit of help. 

---

# Foundry VTT Modules for WFRP 4E
Foundry modules that work within Warhammer Fantasy Roleplay 4th Edition are noted here. These may include NPC compendiums that may be legally shared, world saves, character sheet mods, changes to roll tables, etc.

## Arcane Marks & Careers

* **Author**: Moo Man#7518 on Discord
* **Version**: 1.2.4
* **Foundry VTT Compatibility**: 0.4.4+
* **System Compatibility**: Warhammer Fantasy Roleplay 4th Edition.
* **Module Requirement(s)**: None
* **Module Conflicts**: None
* **Translation Support**: EN (full)

### Link(s) to Module
* [https://github.com/moo-man/Arcane-Marks-Careers-FVTT](https://github.com/moo-man/Arcane-Marks-Careers-FVTT)
* [https://raw.githubusercontent.com/moo-man/Arcane-Marks-Careers-FVTT/master/module.json](https://raw.githubusercontent.com/moo-man/Arcane-Marks-Careers-FVTT/master/module.json)

### Description
[This homebrew](https://drive.google.com/file/d/1uTy2r0EDMdcISFqqyxeIOSadtzz-OTAg/view) supplement I made adds Lore specific careers and marks for WFRP4e. 

This module for FVTT adds these careers and tables to the [WFRP4e system](https://github.com/CatoThe1stElder/WFRP-4th-Edition-FoundryVTT/tree/stable)

To install, simply add `arcane-marks-careers` into the modules folder in the `public` directory of Foundry. Enable the module in your world, then restart Foundry.

Once installed, you'll find the careers in the Arcane Careers Compendium, and you can roll on any Arcane Mark table with the chat command `/table <wind-name>`, e.g. `/table aqshy`.

---
## Rough Nights & Hard Days

* **Author**: Jagusti#3610
* **Version**: 0.7
* **Foundry VTT Compatibility**: 0.4.5+
* **System Compatibility**: WFRP4e 0.9.0+
* **Module Conflicts**: Any module that changes (rather than extends) the species or career tables

### Link(s) to Module
* https://github.com/Jagusti/fvtt-wfrp4e-rnhd/
* `https://raw.githubusercontent.com/Jagusti/fvtt-wfrp4e-rnhd/master/module.json`

### Description

* Extends the character creation capabilities to gnomes, including their stats, background, features. 
* Also includes pub games
* Adds campaign scenario content (see [readme.md](https://github.com/Jagusti/fvtt-wfrp4e-rnhd/blob/master/README.md) for current coverage)
---
## Gerwin Waffenhalter’s Magnificent Weapons Gallery
* **Author**: DasSauerkraut#3215
* **Version**: 1.0
* **Foundry VTT Compatibility**: 0.4.5+
* **System Compatibility**: WFRP4e 0.9.0+
* **Module Conflicts**: N/A
### Description
This module adds the 'Slashing' weapon quality as well as the expanded weapons from [The Ratter Vol. 1 Issue 2](https://indd.adobe.com/view/763c1883-228a-455f-a115-19f4059f4589)
### Link(s) to Module
* https://github.com/DasSauerkraut/wfrp-gwmwg
* Manifest: https://raw.githubusercontent.com/DasSauerkraut/wfrp-gwmwg/master/module.json

---

# Foundry VTT Modules (Defunct)

Foundry VTT modules that no longer work are noted here. Modules included here have been defunct for at least one month. This exists to help document previous work on Foundry Virtual Tabletop by the community, as well as to exist as a record for anyone who chooses to remain on a previous version of Foundry VTT.  

## Always Show Notes (see Show Notes for successor)

* **Author**: Pin#8969
* **Version**: 0.1
* **Foundry VTT Compatibility**: 0.3.5
* **System Compatibility (If applicable)**: Universal
* **Module Requirement(s)**: N/A
* **Module Conflicts**: No known conflicts
* **Translation Support**: EN (full)

### Link(s) to Module
* [https://github.com/Pingar5/alwaysshownotes](https://github.com/Pingar5/alwaysshownotes)
* [https://raw.githubusercontent.com/Pingar5/alwaysshownotes/master/alwaysshownotes/module.json](https://raw.githubusercontent.com/Pingar5/alwaysshownotes/master/alwaysshownotes/module.json)

### Description
Sets the Display Notes toggle to true by default

---

## Anvil Menu

* **Author**: Ionshard#7383 on Discord
* **Version**: 0.1
* **Foundry VTT Compatibility**: 0.3.7
* **System Compatibility (If applicable)**: Universal
* **Module Requirement(s)**: N/A
* **Translation Support**: EN (full)

### Link(s) to Module
* [https://gitlab.com/Ionshard/foundry-vtt-anvil-menu](https://gitlab.com/Ionshard/foundry-vtt-anvil-menu)

### Description

**UPDATE**: No longer a bundled module. But the Anvil Menu library is still usable by developers.

The Anvil Menu is a library able to be used by other module developers without the need to include the anvil-menu module itself. See the README on GitLab for more information.

---

## Arcane Viewing (module integrated into core)

* **Author**: KaKaRoTo#4756 (Discord). KaKaRoTo's Patreon can be found here: [https://www.patreon.com/kakaroto](https://www.patreon.com/kakaroto).
* **Version**: 0.1
* **Foundry VTT Compatibility**: 0.3.8
* **System Compatibility (If applicable)**: Universal
* **Module Requirement(s)**: None
* **Module Conflicts**: None
* **Translation Support**: EN

### Link(s) to Module
* [The module is paywalled, and requires subscribing to KaKaRoTo’s Patreon.](https://www.patreon.com/posts/arcane-viewing-30918808)

### Description
Arcane Viewing adds Audio/Video conferencing support directly from within FVTT.

Through the use of Arcane magic, you are able to see and hear your follow adventurers wherever they may hide! Peer through the looking glass and see the horror that grips them and hear their screams as they are attacked by a cute bunny. Huh?

**Note**: This module has been deprecated as most of its functionality has now been integrated into Foundry's core. See https://www.patreon.com/posts/beta-0-4-2-notes-32265287

---

## Better FilePicker

**Note**: This module has been deprecated as most of its functionality has now been integrated into Foundry's core.

* **Author**: Adriannom#0237 (Discord).
* **Version**: 0.1.3
* **Foundry VTT Compatibility**: 0.4.4+
* **System Compatibility (If applicable)**: Universal
* **Module Requirement(s)**: None
* **Module Conflicts**: Image Previewer
* **Translation Support**: EN, IT

### Link(s) to Module
* [https://github.com/Adriannom/fvtt-better-filepicker](https://github.com/Adriannom/fvtt-better-filepicker) 
* Manifest: [https://raw.githubusercontent.com/Adriannom/fvtt-better-filepicker/master/module.json](https://raw.githubusercontent.com/Adriannom/fvtt-better-filepicker/master/module.json)

### Description
Toggle image thumbnails in the file picker. Also improves file picker visibility on small screens.

---

## Chat Colors & More (discontinued)

* **Author**: Letheka
* **Foundry VTT Compatibility**: 0.5.3+
* **Module Requirement(s)**: None
* **Module Conflicts**: None

### Link(s) to Module
* [https://gitlab.com/lethekazhorai/chat-colors-and-more](https://gitlab.com/lethekazhorai/chat-colors-and-more)
* [https://gitlab.com/lethekazhorai/chat-colors-and-more/-/raw/master/module.json](https://gitlab.com/lethekazhorai/chat-colors-and-more/-/raw/master/module.json)

### Description
This module allows players to set custom colors for different types of chat messages (IC speech, emotes, rolls, and all other messages) in the Module Settings. Players can also specify a default chat prefix, which will be prefixed to all their chat messages that are not already commands. 

![Screenshot](https://gitlab.com/lethekazhorai/chat-colors-and-more/-/raw/master/ChatColors_Example.PNG?inline=true "Screenshot")

---

## Chat Damage Buttons (obsolete to minor-qol)

* **Author**: hooking#0492 on Discord.
* **Version**: 0.3.1
* **Foundry VTT Compatibility**: 0.4.0+
* **System Compatibility (If applicable)**: Dungeons and Dragons 5th Edition
* **Module Requirement(s): None.
* **Module Conflicts**: Module appears to be incompatible with the aDnD5e module.
* **Translation Support**: EN (full)

### Link(s) to Module
* [https://gitlab.com/hooking/foundry-vtt---chat-damage-buttons](https://gitlab.com/hooking/foundry-vtt---chat-damage-buttons)
* [https://gitlab.com/hooking/foundry-vtt---chat-damage-buttons/blob/master/module.json](https://gitlab.com/hooking/foundry-vtt---chat-damage-buttons/blob/master/module.json)

### Description
This module replaces the right-click context menu with buttons on the dice-roll chat message. This allows for quicker application of damage/healing.

To install the module, download the zip file included in the Github module directory. Extract the zip file to `/public/modules`. Restart Foundry Virtual Tabletop.

---

## Chat Damage Buttons - Better Rolls Edition

* **Discontinued**: The functionality has been added to the core features of Better Rolls
* **Author**: Felix#6196 and hooking#0492
* **Version**: 0.1
* **Foundry VTT Compatibility**: written for and tested on v0.3.6
* **Module Requirement(s)**: [Better Rolls for 5e](https://github.com/RedReign/FoundryVTT-BetterRolls5e) by RedReign
* **Module Conflicts**: none known.
* **Translation Support**: EN (full)

### Link(s) to Module
* [https://github.com/syl3r86/chatdamagebuttons-betterrolls](https://github.com/syl3r86/chatdamagebuttons-betterrolls)
* [https://raw.githubusercontent.com/syl3r86/chatdamagebuttons-betterrolls/master/chatdamagebuttons-betterrolls5e/module.json](https://raw.githubusercontent.com/syl3r86/chatdamagebuttons-betterrolls/master/chatdamagebuttons-betterrolls5e/module.json)

### Description
A small module to add "Apply Damage" buttons to Red Reigns Better Rolls 5e Module, based on hookings Chat Damage Buttons.
To install use the following link in Foundrys Module Setup https://raw.githubusercontent.com/syl3r86/chatdamagebuttons-betterrolls/master/chatdamagebuttons-betterrolls5e/module.json

---

## Critical Fumble

* **Author**: Jacob McAuley Discord: @JacobMcAuley3461
* **Version**: 0.5.0
* **Foundry VTT Compatibility**: 0.4.3
* **System Compatibility (If applicable)**: DnD5e
* **Module Requirement(s)**: None
* **Module Conflicts**: Any module that overrides Dice5e.roll()
* **Translation Support**: EN (Full)

### Link(s) to Module
* [https://github.com/JacobMcAuley/critical-fumble](https://github.com/JacobMcAuley/critical-fumble)
* [https://github.com/JacobMcAuley/critical-fumble/raw/master/module.json](https://github.com/JacobMcAuley/critical-fumble/raw/master/module.json)

### Description
Do you find yourself forgetting to roll on the critical hit table? The critical fumble table? Do you find yourself forgetting to roll that pesky loot table after each monster dies?

Then you're like me and this mod is what you need! Critical-fumble will automatically roll on the critical hit tables in the event of a critical hit! Each hit rolls a special table depending on the type of damage.

Additionally, every time a targeted monster is felled by your players, the CR table is rolled! To further your convience, the coins dropped can be automatically distributed to your players. This option can be ignored though!

---

## DDB Popper (use VTTA-DNDBEYOND instead)

* **Author**: errational#2007 on discord
* **Version**: 1.1
* **Foundry VTT Compatibility**: 0.3.7
* **System Compatibility (If applicable)**: dnd5e
* **Module Requirement(s)**: N/A
* **Module Conflicts**: N/A
* **Translation Support**: EN (full)

### Link(s) to Module
* [https://github.com/death-save/ddb-popper](https://github.com/death-save/ddb-popper)
* [https://raw.githubusercontent.com/death-save/ddb-popper/master/module.json](https://raw.githubusercontent.com/death-save/ddb-popper/master/module.json)

### Description
Opens a D&D Beyond popup for a linked actor.    
More info here: [https://github.com/death-save/ddb-popper](https://github.com/death-save/ddb-popper)

---

## DnD Beyond Character Importer (non-functional -- use VTTA-D&D Beyond Integration instead)

* **Author**: @Sillvva#2532 on Discord.
* **Version**: 0.19
* **Foundry VTT Compatibility**: 0.3+ (See Description)
* **System Compatibility (If applicable)**: Dungeons and Dragons 5th Edition
* **Module Requirement(s)**: None.
* **Module Conflicts**: None, but see description.
* **Translation Support**: EN (full)

### Link(s) to Module
* [https://github.com/sillvva/foundry-vtt-modules/tree/master/ddb-importer](https://github.com/sillvva/foundry-vtt-modules/tree/master/ddb-importer) 

### Description
This module allows you to import character data from DnD Beyond into Foundry Virtual Tabletop.  

The module has not been updated recently by its creator, but the community has produced a fix for this issue.  The fix is not included in the zip file for the module, but is instead contained within the Github repository, and must be retrieved there. Replace the file in the module folder with the fixed version.

---

## Dynamic Items (obsolete to dynamic effects)

**This module is obsolete and replaced with dynamic effects**  

* **Author**: @tposney discord
* **Version**: 0.0.45
* **Foundry VTT Compatibility**: 0.4.4+ dnd 5e 0.80+. Requires 0.4.4+ and wont work with earlier versions.
* **Module Requirement(s)**: None
* **Module Conflicts**: None that I know of
* **Translation Support**: English.
* **Translation Support**: Japanese. Kindly provided by @BrotherSharp

### Link(s) to Module
* [https://gitlab.com/tposney/dynamicitems](https://gitlab.com/tposney/dynamicitems)
* [https://gitlab.com/tposney/dynamicitems/raw/master/module.json](https://gitlab.com/tposney/dynamicitems/raw/master/module.json)
* [https://gitlab.com/tposney/dynamicitems/raw/master/dynamicitems.zip](https://gitlab.com/tposney/dynamicitems/raw/master/dynamicitems.zip)

### Description
Dynamic items are ones that makes changes to your stats/modifiers when they are active in your inventory. This module is really intended for player characters and NPCs that have linked tokens.

* Armor and shields now update your armor class when equipped and reverse the change when unequipped. (this happens automatically once the module is turned on and the items are equipped). Armor can have dynamic properties, e.g. ac+2 which can require attunement. Dexterity bonuses are added to AC up to the max dex mod specified in the armor.
* Rings of protection can increase saves or armor class when active, again changes are reversed when unequiped or unattuned (if that is a word).
* There is a straightforward ui to make changes/create items For more complex changes (e.g. AC based on dex mod, you need to know the attribute specification, e.g. data.avilities.dex.mod)
* Dynamic effects can be applied to any item, weapons/backpacks/armor/feats, in addition to its normal properties.
* as of 0.8 new bonus fields, like attacks, weapon damage and saves/checks can be added as strings. So +1d4 on saving throws for bless.
Please see the module link for documentation.

---

## D&D 5e Conditions (obsolete to CUB)

* **Author**: trdischat#2123 on Discord.
* **Version**: 0.4.5
* **Foundry VTT Compatibility**: 0.4.5+
* **System Compatibility (If applicable)**: Dungeons and Dragons 5th Edition.
* **Module Requirement(s)**: None
* **Module Conflicts**: None
* **Translation Support**: EN (full)

### Link(s) to Module
* [https://github.com/trdischat/conditions5e](https://github.com/trdischat/conditions5e)
* [https://raw.githubusercontent.com/trdischat/conditions5e/master/module.json](https://raw.githubusercontent.com/trdischat/conditions5e/master/module.json)

### Description
Alter the icons in the Status Effects panel of the Token Hub to reflect the standard "conditions" in D&D 5e, and repurpose the effects overlay to display whether the token is seriously wounded, unconscious, or dead.

---

## Encumbrance Variant

* **Obsolete replaced by VariantEncumbrance**
* **Author**: hooking#0492 on Discord.
* **Version**: 0.14
* **Foundry VTT Compatibility**: 0.2.8-0.2.10
* **System Compatibility (If applicable)**: Dungeons and Dragons 5th Edition.
* **Module Requirement(s)**: None.
* **Module Conflicts**: None currently known.
* **Translation Support**: EN (full)

### Link(s) to Module
* [https://gitlab.com/hooking/foundry-vtt---encumbrance-variant-5e](https://gitlab.com/hooking/foundry-vtt---encumbrance-variant-5e)
* [https://gitlab.com/hooking/foundry-vtt---encumbrance-variant-5e/blob/master/module.json](https://gitlab.com/hooking/foundry-vtt---encumbrance-variant-5e/blob/master/module.json)

### Description
This module modifies how the encumbrance bar in the actor sheet is displayed to distinguish the different levels of encumbrance when using the variant rules in **PHB pg. 175**. It does not currently support the Powerful Build feature, as doing so would require extending the base Actor5eSheet class.

---

## Entity Order

* **Author**: KaKaRoTo#4756 on Discord. His Patreon can be found here: [https://www.patreon.com/kakaroto](https://www.patreon.com/kakaroto)
* **Version**: 0.1
* **Foundry VTT Compatibility**: 0.4.0+
* **System Compatibility (If applicable)**: Universal
* **Module Requirement(s)**: None
* **Module Conflicts**: None
* **Translation Support**: EN (full)

### Link(s) to Module
* [https://github.com/kakaroto/fvtt-module-entityorder](https://github.com/kakaroto/fvtt-module-entityorder)
* [https://raw.githubusercontent.com/kakaroto/fvtt-module-entityorder/master/entityorder/module.json](https://raw.githubusercontent.com/kakaroto/fvtt-module-entityorder/master/entityorder/module.json)

### Description
This Foundry VTT module allows you to re-order entities (Actors, Scenes, Items and Journal entries).

---

## FVTT-Party (Discontinued, see VTTA-Party for an successor)

* **Author**: @solfolango77#0880 on Discord.
* **Version**: 0.1
* **Foundry VTT Version Compatibility**: 0.3+
* **System Compatibility (If applicable)**: Dungeons and Dragons 5th Edition.
* **Module Requirement(s)**: None
* **Module Conflicts**: None known, although module is a WIP.
* **Translation Support**: EN (full)

### Link(s) to Module
* [https://github.com/shwill/fvtt-party](https://github.com/shwill/fvtt-party)
* [https://github.com/shwill/fvtt-party/raw/master/module.json](https://github.com/shwill/fvtt-party/raw/master/module.json)

### Description
This module adds a convenient button to the actor’s tab, which will track the HP, AC, and Passive Perception, Investigation, and Insight of tokens on the Canvas. Currently a WIP, and may exhibit some bugs.

To install the module, download the zip file included in the Github module directory. Extract the zip file to `/public/modules`. Restart Foundry Virtual Tabletop.

---

## GM Roll Message

* **Author**: Hydroxi#0366 on Discord.
* **Version**: WIP
* **Foundry VTT Compatibility**: 0.3+
* **System Compatibility (If applicable)**: Universal
* **Module Requirement(s)**: None
* **Module Conflicts**: None
* **Translation Support**: EN (full)

### Link(s) to Module
* [https://github.com/Hydroxi/gmrollmessage](https://github.com/Hydroxi/gmrollmessage)
* [https://github.com/Hydroxi/gmrollmessage/raw/master/module.json](https://github.com/Hydroxi/gmrollmessage/raw/master/module.json)

### Description
Sends an extra public message/hint when rolling a `gmroll` or `blindroll`.

---

## Infinite Folders

* **Author**: KaKaRoTo#4756 on Discord. His Patreon can be found here: [https://www.patreon.com/kakaroto](https://www.patreon.com/kakaroto)
* **Version**: 0.1
* **Foundry VTT Compatibility**: 0.3.1
* **System Compatibility (If applicable)**: Universal
* **Module Requirement(s)**: None
* **Module Conflicts**: This module creates folders and allows you to create data where it shouldn't be. If a future FVTT update enforces the 2-depth limit on the server side, then all of the deeper folders and their content may be lost.
* **Translation Support**: EN (full)

### Link(s) to Module
* [https://github.com/kakaroto/fvtt-module-infinite-folders](https://github.com/kakaroto/fvtt-module-infinite-folders)
* [https://raw.githubusercontent.com/kakaroto/fvtt-module-infinite-folders/master/infinite_folders/module.json](https://raw.githubusercontent.com/kakaroto/fvtt-module-infinite-folders/master/infinite_folders/module.json)

### Description
This Foundry VTT module allows you to create infinite depth of folders for Scenes, Actors, Items and Journals. No more limit to a depth of 2 folders (or none for Journal entries). This will also add a `New entity` button on folders so you can create it directly in the folder (does not work for Scenes though).

---

## Item Sheet Buttons (obsolete to minor-qol)

* **Author**: hooking#0492 on Discord.
* **Version**: 0.13
* **Foundry VTT Compatibility**: 0.2.8-0.2.10
* **System Compatibility (If applicable)**: Dungeons and Dragons 5th Edition
* **Module Requirement(s)**: None.
* **Module Conflicts**: None currently known, but according to Github page may be prone to breaking in the future.
* **Translation Support**: EN (full)

### Link(s) to Module
* [https://gitlab.com/hooking/foundry-vtt---item-sheet-buttons](https://gitlab.com/hooking/foundry-vtt---item-sheet-buttons)
* [https://gitlab.com/hooking/foundry-vtt---item-sheet-buttons/blob/master/module.json](https://gitlab.com/hooking/foundry-vtt---item-sheet-buttons/blob/master/module.json)

### Description
This module adds item card buttons into the description of items, so that the item cards do not need to be pinged in chat. It does have the side effect of making it harder to ping item descriptions within chat.

To install, download the zip file included in the Github module directory. Extract the zip folder to `/public/modules`. Restart Foundry Virtual Tabletop.

---

## Journal Drag

* **Author**: @tposney - discord
* **Version**: 0.4.1
* **Foundry VTT Compatibility**: 0.4+
* **Obsolete as of version Foundry 0.4.2. of core. Please uninstall the module once updated to 0.4.2**

---

## Mother, May I? (Core Permission Setting)

* **Author**: Deuce#8801 on Discord.
* **Version**: 0.0.1
* **Foundry VTT Compatibility**: 0.4.4+
* **Translation Support**: None

### Link(s) to Module
* [https://github.com/RealDeuce/mother-may-i/](https://github.com/RealDeuce/mother-may-i/)
* [https://raw.githubusercontent.com/RealDeuce/mother-may-i/master/module.json](https://raw.githubusercontent.com/RealDeuce/mother-may-i/master/module.json)

### Description
Allows trusted players to drag items and actors they own to the canvas as long as a GM is logged in.

---

## NPC Browser 

* discontinued. functionality moved to Compendium Browser
* **Author**: Felix#6196 on Discord, syl3r31 on Github. He accepts donations on Paypal at felix.mueller.86@web.de
* **Version: 0.1**
* **Foundry VTT Compatibility**: 0.3.0  (discontinued, use Compendium Browser instead)
* **System Compatibility (If applicable)**: Dungeons and Dragons 5th Edition
* **Module Requirement(s)**: None
* **Module Conflicts**: None known
* **Translation Support**: EN (full)

### Link(s) to Module
* [https://github.com/syl3r86/npc-browser](https://github.com/syl3r86/npc-browser)

### Description
This module adds a search interface for actors. This enables more comfortable browsing and searching via predefined filters like challenge rating, type or ability score.

---

## Polymorpher

* Obsolte because its functionality has been merged to the core dnd5e system
* **Author**: Felix#6196 on Discord, syl3r31 on Github. He accepts donations on Paypal at felix.mueller.86@web.de
* **Version**: 0.3.5
* **Foundry VTT Compatibility**: 0.4.4+
* **System Compatibility (If applicable)**: Dungeons and Dragons 5th edition.
* **Module Requirement(s)**: None.
* **Module Conflicts**: Previous version of the module deleted actors, do not use v0.1.
* **Translation Support**: EN (full)

### Link(s) to Module
* [https://github.com/syl3r86/polymorpher](https://github.com/syl3r86/polymorpher)
* [https://raw.githubusercontent.com/syl3r86/polymorpher/master/module.json](https://raw.githubusercontent.com/syl3r86/polymorpher/master/module.json)

### Description
A module for Foundry VTT that lets you polymorph characters into any other character! Just drag any Actor (NPC or Character) on top of another Actor to change the later into the prior. Support dropping both from Compendium or the sidebar.

---

## Request Roll (obsolete to LMRTFY)

* **Author**: Jacob McAuley Discord: @JacobMcAuley3461
* **Version**: 1.0.0
* **Foundry VTT Compatibility**: 0.4.3
* **System Compatibility (If applicable)**: DnD5e
* **Module Requirement(s)**: None
* **Module Conflicts**: None known
* **Translation Support**: EN (Full)

### Link(s) to Module
* [https://github.com/JacobMcAuley/request_roll](https://github.com/JacobMcAuley/request_roll)
* [https://github.com/JacobMcAuley/request_roll/raw/master/module.json](https://github.com/JacobMcAuley/request_roll/raw/master/module.json)

### Description
Request Roll is a module designed to help Gamemasters speed up the rolling process by requesting rolls from PCs. This can help reduce player navigation time, questions about where a roll is located, and other unforseen delays that cause chokepoitns in your game. You can select from a range of options varying from hidden rolls, where only the gm knows, to rolls with advantage or disadvantage! Consider installing this module to speed along your game!

---

## Roll20 NPC Importer, for 5e

* **Depreicated**: No longer recieves updates. See R20 Converter here for similar functionality @ [https://www.patreon.com/kakaroto](https://www.patreon.com/kakaroto)
* **Author**: Felix#6196 on Discord, syl3r31 on Github. He accepts donations on Paypal at felix.mueller.86@web.de
* **Version**: Roll20 NPC Importer 5e v0.5.1
* **Foundry VTT Compatibility**: 0.3.0
* **System Compatibility (If applicable)**: Dungeons and Dragons 5th Edition
* **Module Requirement(s)**: None.
* **Module Conflicts**: None known.
* **Translation Support**: EN (full), JA (full)

### Link(s) to Module
* [https://github.com/syl3r86/roll20npcimporter](https://github.com/syl3r86/roll20npcimporter)
* [https://raw.githubusercontent.com/syl3r86/roll20npcimporter/master/roll20npcimporter/module.json](https://raw.githubusercontent.com/syl3r86/roll20npcimporter/master/roll20npcimporter/module.json)

### Description
This module allows for the importing of NPCs from Roll20, through use of JSONs exported via [VTT Enhancement Suite](https://ssstormy.github.io/roll20-enhancement-suite/). This import currently only supports NPCs created in the Roll20 OGL or Shaped version sheets. This module supports the Better NPC Sheet 5e, as well as the aDnD5e sheet in tagging actor items according to abilities, reactions, legendary actions, etc.  To install, first download the module, unzip it into `/public/modules`, and then restart Foundry while it is running.

---

## Roll Table Buttons (defunct)

* **Author**: RaySSharma#4736 on Discord
* **Version**: 0.3.1
* **Foundry VTT Compatibility**: 0.4.4+
* **System Compatibility (If applicable)**: Universal
* **Module Requirement(s)**: None
* **Module Conflicts**: None
* **Translation Support**: EN (full)

### Link(s) to Module
* [https://github.com/RaySSharma/foundry-modules/tree/master/rolltable-buttons](https://github.com/RaySSharma/foundry-modules/tree/master/rolltable-buttons)
* [https://raw.githubusercontent.com/RaySSharma/foundry-modules/master/rolltable-buttons/rolltable-buttons/module.json](https://raw.githubusercontent.com/RaySSharma/foundry-modules/master/rolltable-buttons/rolltable-buttons/module.json)

### Description
This module adds a button to the chat controls for easier access to rolltables. Came about as a way to add critical-hit decks for players.

---

## Spell Browser 

* discontinued. functionality moved to Compendium Browser
* **Author**: Felix#6196 on Discord, syl3r31 on Github. He accepts donations on Paypal at felix.mueller.86@web.de.
* **Version**: 0.3
* **Foundry VTT Compatibility**: 0.3.0 (discontinued, use Compendium Browser instead)
* **System Compatibility (If applicable)**: Dungeons and Dragons 5th Edition
* **Module Requirement(s)**: None
* **Module Conflicts**: None known.
* **Translation Support**: EN (full)

### Link(s) to Module
* [https://github.com/syl3r86/Spell-Browser](https://github.com/syl3r86/Spell-Browser)

### Description
This module adds a search interface for spells. This enables more comfortable browsing and searching via predefined filters like spell level, class or damage type.

---

## SRD Bestiary Module

* Obsolte because its functionality has been merged to the core dnd5e system
* **Author**: DestinyGrey#2890, also known as “The_Entire_Eurozone”.  
* **Version**: 0.2
* **Foundry VTT Compatibility**: 0.2.8+
* **System Compatibility (If applicable)**: Dungeons and Dragons 5th Edition
* **Module Requirement(s)**: None, though it is compatible and has optional sorting tags for the Better NPC Sheet 5E module, as well as the aDnD5e module.  
* **Module Conflicts**: None (currently).  
* **Translation Support**: EN (full)

### Link(s) to Module
* [https://drive.google.com/file/d/1oHMQhKuV-Vpdg5ftWTMaGZg76MVngZqO/view?usp=sharing](https://drive.google.com/file/d/1oHMQhKuV-Vpdg5ftWTMaGZg76MVngZqO/view?usp=sharing)

### Description
This module includes each SRD NPC in 5th edition, imported into Foundry VTT. This includes all of their features, immunities/resistances/vulnerabilities, actions, and much, much more.  Other than lacking token images (token images do not appear to be part of the SRD), each NPC is built and ready for use in Foundry Virtual Tabletop.  Included in the module is a folder containing each individual NPC json, in case you wish to experiment with importing them, or future updates break the NPCs in this module. These can be imported individually using the Roll20 NPC Importer, for 5e module.  

Future updates will include edits to the imports to bring them in line with “good practice” for Foundry NPCs.

To install, simply extract the zip file into `/public/modules`, enable the module in Foundry, and then do a full restart in order to display the compendium.

---

## Theatre Inserts

* **Noah Zorbaugh, U~man**: U~man#2374, contributions are welcome
* **Version**: 0.1.6
* **Foundry VTT Compatibility**: 0.5
* **System Compatibility (If applicable)**: Universal
* **Module Requirement(s)**: None
* **Module Conflicts**: None known
* **Translation Support**: English, French, Japanese, Korean, Portuguese, Thaï

### Link(s) to Module
* [https://gitlab.com/NoahZorbaugh/theatre](https://gitlab.com/NoahZorbaugh/theatre) 
* Manifest: [https://gitlab.com/mesfoliesludiques/theatre/-/raw/master/module.json](https://gitlab.com/mesfoliesludiques/theatre/-/raw/master/module.json)

### Description
Theatre is a mod that allows for a visual novel style RP experience for text, and text-voice hybrid games. The primary function of Theatre is to allow for graphical 'theatre-inserts' or 'standin-graphics' to appear on screen with an accompanying area for text beneath them. This follows the style of visual novels, and even provides a means to animate or decorate the text as it appears in the below box. It also provides an emote system to allow users to configure different graphics for the various emotive expressions. Most of the emotes additionally have a built in 'emote animation' that occurs when the emote is selected, which can be toggled off globally if undesired.

Instructions at [https://gitlab.com/Ayanzo/theatre/-/wikis/home](https://gitlab.com/Ayanzo/theatre/-/wikis/home)

---

## Tiles Browser (in Core)

* **Author**: Moerill#7205 on Discord. He accepts donations at his [PayPal](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=FYZ294SP2JBGS&source=url).
* **Translation Support**: EN (full)
* **Foundry VTT Compatibility**: 0.4.2+
### Link(s) to Module
* [https://gitlab.com/moerills-fvtt-modules/tiles-browser/](https://gitlab.com/moerills-fvtt-modules/tiles-browser/)
* [https://gitlab.com/moerills-fvtt-modules/tiles-browser/raw/master/module.json](https://gitlab.com/moerills-fvtt-modules/tiles-browser/raw/master/module.json)

### Description
Adds a browser to the tiles layer to conveniently preview and then drag and drop tiles onto the scene. Providing additional features to manipulate tile rotation and size while dragging.

---

## Z Order

* Obsolte because its functionality has been merged to the core
* **Author**: KaKaRoTo#4756 on Discord. His Patreon can be found here: [https://www.patreon.com/kakaroto](https://www.patreon.com/kakaroto)
* **Version**: 0.1
* **Foundry VTT Compatibility**: 0.3+
* **System Compatibility (If applicable)**: Universal
* **Module Requirement(s)**: None
* **Module Conflicts**: None
* **Translation Support**: EN (full)

### Link(s) to Module
* [https://github.com/kakaroto/fvtt-module-zorder](https://github.com/kakaroto/fvtt-module-zorder)
* [https://raw.githubusercontent.com/kakaroto/fvtt-module-zorder/master/zorder/module.json](https://raw.githubusercontent.com/kakaroto/fvtt-module-zorder/master/zorder/module.json)

### Description
This Foundry VTT module lets you send tiles to the front or the back of the scene.

---

## ZoomKey

* Obsolte because its functionality has been merged to the core
* **Author**: U~man#2374, contributions are welcome
* **Version**: 0.2.1
* **Foundry VTT Compatibility**: 0.4.x
* **System Compatibility (If applicable)**: Universal
* **Module Requirement(s)**: None
* **Module Conflicts**: None known
* **Translation Support**: No text

### Link(s) to Module
* [https://gitlab.com/mesfoliesludiques/foundryvtt-zoomkey](https://gitlab.com/mesfoliesludiques/foundryvtt-zoomkey) 
* [https://gitlab.com/mesfoliesludiques/foundryvtt-zoomkey/-/raw/master/zoomkey/module.json](https://gitlab.com/mesfoliesludiques/foundryvtt-zoomkey/-/raw/master/zoomkey/module.json) 

### Description
Adds hotkeys for zooming and panning on the canvas without mousewheel
- Zooming in: Page Up or Ctrl + '+'
- Zooming out: Page Down or Ctrl + '-'
- Panning : Ctrl + arrows

---
# Appendix
## Appendix A: Best Editing Practices

- Ideally, the term module should be used over mod, unless it is in the mod’s name or the author’s description. Mod can carry connotations from other games that might not exist in Foundry VTT, while modules in Foundry VTT can range from NPC compendiums, to worlds, to “enhancement suite” functions. They’re effectively the same thing, but it helps to emphasize how flexible Foundry Virtual Tabletop is. 
- Links to modules should link to the author’s page for it, if such exists. This helps emphasize the module author’s control over their creation, and allows users to see information that the module author deems important. If you have the module author’s permission otherwise, or you are the creator, feel free to link directly to the module download link. 
- Modules are sorted by system compatibility, then function, and then alphabetically. If a module is compatible with more than one system, but not “universally” in Foundry Virtual Tabletop, note compatibility in each system’s section. Otherwise, if a module is compatible universally, list it in the appropriate section for “universal modules”. 
- Ensure that Foundry is noted as “Foundry VTT” or “Foundry Virtual Tabletop” in writing, unless it is the module title, or the module author desires otherwise in the description. This helps emphasize Foundry’s role as a unique, standalone tabletop, and helps distinguish it from other brands using the word “foundry”.   
- Ideally, each module should be separated by a single line break. This is just to help it look neat. 
- Modules should not be listed if they violate existing copyright law.  
