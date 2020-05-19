# Changelog

- [Changelog](#changelog)
  - [1.1.5: Various Mod Updates](#115-various-mod-updates)
  - [1.1.4: Loot Overhaul #1](#114-loot-overhaul-1)
  - [1.1.3: Various Fixes](#113-various-fixes)
  - [1.1.2: Various Fixes](#112-various-fixes)
  - [1.1.1: Fix the Gravemarker](#111-fix-the-gravemarker)
  - [1.1.0: Gold on Corpses](#110-gold-on-corpses)
  - [1.0.3: Various Fixes](#103-various-fixes)
  - [1.0.2: No Moar BSAs](#102-no-moar-bsas)
  - [1.0.1: Minor update due to mod changes](#101-minor-update-due-to-mod-changes)
  - [1.0.0: Initial Release](#100-initial-release)

## 1.1.5: Various Mod Updates

**Released at**: `19.05.2020`

**Info**:

Fixing broken installer due to mod updates.  Includes a rather large
change to Blade & Blunt.  You should go read the mod page.

**Changes**:
- Mods
  - Added
  - Removed
  - Updated
    - Blade and Blunt
    - Dwemer Spectres EBT Patch
    - Project Clarity
    - Reliquary of Myth
    - Storm Lightning

## 1.1.4: Loot Overhaul #1

**Released at**: `16.05.2020`

**Info**:
Forced update due to mod changes. Loot has been overhauled bringing it closer
to the MLU style model of rarity.  Monsters still need to have their loot updated
to make them fall in line... I didn't have time to do that before the installer
stopped working.

Midgame update should be safe but you might experience some missing items and 
such due to the loot list changes.

**Changes**:

- Mods
  - Added
    - aMidianBorn Content Addon
    - HookShareSSE
    - Morrowloot Miscellania - Hybrid Loot
    - QuickLootRE
    - QuickLootRe and HookShareSSE - Unofficial Update
  - Removed
    - Dynamic Dungeon Loot
    - MisterB's Unique Treasures
    - MisterB's Ultimate Loot Mod Patch
    - Thematic Loot
  - Updated
    - Adamant
    - Aetherius
    - Briraka's Draugr Overhaul
    - CK64Fixes
    - Mundus
    - SSE Display Tweaks

## 1.1.3: Various Fixes

**Released at**: `14.05.2020`

**Info**:

Forced update due to mod dependencies. Elder Souls - Death has been updated to
grant gold on kill based on enemy level. In order for these changes to apply
to your already existing characters you need to delete `ElderSouls_DeathScript`
from your save using `Fallrim Tools`

There is no reason to update if you're happy with the current gold granting
system in ESD. Wait for a new character.

**Changes**:

- Mods
  - Updated
    - Aetherious
    - Elder Souls - Death
    - Reliquary of Myths

## 1.1.2: Various Fixes

**Released at**: `12.05.2020`

**Info**:

Forced update due to mod dependencies.

**Changes**:

- Issues

  - Fixed

    - [Auris Neck](https://github.com/jdsmith2816/eldersouls/issues/3)
    - [Bugged Texture in Ragged Flagon](https://github.com/jdsmith2816/eldersouls/issues/64)
    - [Pre-placed Corpses contain Bonus Gold](https://github.com/jdsmith2816/eldersouls/issues/58)
    - [Whiterun Lod issues](https://github.com/jdsmith2816/eldersouls/issues/59)

  - Won't Fix
    - [Remove Crafting skills from the Purchase Skill Level screen](https://github.com/jdsmith2816/eldersouls/issues/60)
    - [Skills leveling](https://github.com/jdsmith2816/eldersouls/issues/62)

- Mods
  - Added
    - Song of the Green - Auri Replacer - Ella's version
  - Updated
    - Better Dynamic Majestic Mountains
    - Reliquary of Myth
    - Serana Dialogue Add-On
    - SSE Display Tweaks
    - SSE Engine Fixes

## 1.1.1: Fix the Gravemarker

**Released at**: `11.05.2020`

**Info**:

v1.1.0 suffered from a CTD caused by the new highly visible gravemarker. I have
reverted to the original gravemarker and re-opened [Gravemaker map marker](https://github.com/jdsmith2816/eldersouls/issues/7)

## 1.1.0: Gold on Corpses

**Released at**: `10.05.2020`

**Info**:

The primary focus of this release is fixes and quality of life updates for the
`Elder Souls - Death` mod. This release makes grave markers highly visible and
ensures that all enemies now have an amount of liquid currency on their corpse.
Additionally you can now disable `Elder Souls - Death` prior to creating your
character if you wish to play without the custom character progression and death
system.

**This update is most likely _NOT_ save-file safe. If you wish to continue playing
with your current save then _DO NOT_ update to v1.1.0** No support will be given
for those that choose to ignore this warning!

**Changes**:

- Issues

  - Fixed

    - [Black Mage Armor SE Mod](https://github.com/jdsmith2816/eldersouls/issues/52)
    - [CTD upon entering Whiterun](https://github.com/jdsmith2816/eldersouls/issues/43)
    - [DCR King Crusader Armor](https://github.com/jdsmith2816/eldersouls/issues/46)
    - [Death waypoint](https://github.com/jdsmith2816/eldersouls/issues/24)
    - [Disable Dark Souls Leveling for Crafting Skills Only](https://github.com/jdsmith2816/eldersouls/issues/51)
    - [Gravemaker map marker](https://github.com/jdsmith2816/eldersouls/issues/7)
    - [Halamshiral Missing Textures](https://github.com/jdsmith2816/eldersouls/issues/55)
    - [Lock pick breaking adds skill xp](https://github.com/jdsmith2816/eldersouls/issues/37)
    - Remove Glenmoril weapons from vanilla lists
    - Remove Runes and Covenants from lists
    - Vanila alternative weapons now populate the lists properly

  - Won't Fix

    - [Adding SKYTWEAK](https://github.com/jdsmith2816/eldersouls/issues/44)
    - [Tomebound](https://github.com/jdsmith2816/eldersouls/issues/54)

- Mods

  - Added

    - Arch-Knight Judicator Armor and Greatsword
    - Black Mage Armor
    - Blackened Steel
    - DCR King Crusader Armor
    - Dreaded Relics
    - Dynamic Dungeon Loot - Retexture and Remesh for Exotic Weapons
    - Ghouls
    - Honed Metal
    - Honed Metal - Voiced
    - Morrowloot Miscellania - Bound Weapons
    - Mortal Enemies
    - Reaper Paladin Armor Set
    - Reaper Weapon Kit
    - Revenants of the Forbidden Order
    - Sea Giants
    - Skyrim 2020
    - Stalhrim Paladin Armor
    - Supreme Dwemer Spheres
    - Thri-kreen Warriors
    - Vampire Greatsword

  - Removed

    - Skyrim HD Environments
    - Snow and Rock TEXTURES HD
    - Upgrade for Large Imperial Tent

  - Updated
    - Briraka's Draugr Overhaul
    - Dear Diary - Dark Mode
    - Dear Diary - Dark Mode - 21x9
    - DynDOLOD Resources
    - Improved College Entry - Questline tweaks
    - Majestic Mountains
    - Men of Winter
    - moreHUD
    - moreHUD Inventory Edition
    - Nether's Follower Framework
    - Project Clarity - Vanilla Armor Textures Redone
    - Reliquary of Myths
    - SSE Display Tweaks

## 1.0.3: Various Fixes

**Released at**: `04.05.2020`

**Info**:

Due to the unfortunate fact that there are a few stability problems currently I've
edited `Elder Souls - Death` to provide one `Elder Scroll - Break` every fifteen
minutes. This 'feature' will be removed once the stability concerns at hand are
resolved.

**Changes**:

- Fixed

  - Added another 61 possible respawn locations.
  - [Add Beds to Tagged](https://github.com/jdsmith2816/eldersouls/issues/33)
  - [Old Windmill Inn Untextured](https://github.com/jdsmith2816/eldersouls/issues/35)
  - Patched Warmonger Armory belt-fastened dragon priest masks for Frankly HD Miraak
  - Patched Warmonger Armory belt-fastened dragon priest masks for Masks of the Dovah Sonaak
  - [RaceMenu](https://github.com/jdsmith2816/eldersouls/issues/17)
  - [SQM and Sneak Keybind after reload](https://github.com/jdsmith2816/eldersouls/issues/18)

- Won't Fix

  - [Game save option](https://github.com/jdsmith2816/eldersouls/issues/32)
  - [Switch from UNP to CBBE](https://github.com/jdsmith2816/eldersouls/issues/29)

- Added

  - BodySlide and Outfit Studio
  - CBBE
  - Common Clothes and Armors - CBBE Patch
  - Cover Khajiit
  - Forgotten Argonian Roots
  - Frankly HD Dawnguard Armor and Weapons - CBBE Patch
  - Frankly HD Miraak - CBBE Patch
  - Frankly HD Nightingale Armor and Weapons - CBBE Patch
  - Practical Female Armors - CBBE Patch
  - Pride of Valhalla - Niflheim - CBBE
  - Prince and the Pauper - Orphan Clothes HD
  - Project Clarity - Vanilla Armor and Textures Redone
  - Rapid Rocks
  - RUSTIC AMULETS
  - SSE Display Tweaks
  - Talisman of Treachery HD
  - Talos Amulet SD
  - WACCF CBBE Patch
  - Warmonger's Armory Bodyslide Fil3s

- Removed

  - Havok Fixes
  - Modest Elderly
  - Pride of Valhalla - Niflheim - UNP
  - Remiro's Ancient Falmer Armor - UNP Patch
  - UNP Body Fit Female Armors and Clothing
  - UNP Female Body Renewal

- Updated
  - Adamant - A Perk Overhaul
  - Alternate Alchemy
  - Better Dynamic Majestic Mountains
  - Improved College Entry - Questline Tweaks
  - Majestic Mountains - Cathedral Concept
  - Majestic Mountains - Northside
  - Misc Dialogue Edits
  - Reliquary of Myth

## 1.0.2: No Moar BSAs

**Released at**: `01.05.2020`

**Info**:

Various people had serious issues with the compressed BSA files that shipped with the initial release of Elder Souls. The primary goal of this release is to revert back to a 'normal' installation to hopefully resolve the problems for those people. Unfortunately this will result in slower load times and significantly more hard drive space utilized by the game.

To ensure that your save file remains useable please perform the following procedure BEFORE you update:

1. Open the DynDOLOD MCM and deactivate the mod
2. Wait for the deactivation message
3. Go into an interior cell
4. Go back into the MCM and ensure that DynDOLOD shows as deactivated
5. Save the game
6. Update Elder Souls
7. Load your game and head outside.
8. DynDOLOD should now initialize itself; if it doesn't then activate it via MCM
9. That's it.

See below for the various other updates and changes included in this update.

**Changes**:

- Fixed

  - [Bugged door in Helgen](https://github.com/jdsmith2816/eldersouls/issues/14)
  - [Chest in tree](https://github.com/jdsmith2816/eldersouls/issues/5)
  - [Dave's Whiterun in BSA Textures Not Loading Correctly.](https://github.com/jdsmith2816/eldersouls/issues/10)
  - [Floating tree at Old Hroldan Inn](https://github.com/jdsmith2816/eldersouls/issues/21)
  - [Floating tree outside Solitude](https://github.com/jdsmith2816/eldersouls/issues/16)
  - [Link to Blade and Blunt actually goes to Storm and Steel in the README](https://github.com/jdsmith2816/eldersouls/issues/1)
  - [Purple face texture on Balimund](https://github.com/jdsmith2816/eldersouls/issues/15)
  - [Required gold to next level](https://github.com/jdsmith2816/eldersouls/issues/6)
  - [Start player with an elder scroll + autosave after leaving cell](https://github.com/jdsmith2816/eldersouls/issues/11)

- Won't Fix

  - [Gameplay-only version?](https://github.com/jdsmith2816/eldersouls/issues/23)

- Removed

  - Reyliik do Skyrim

- Updated
  - Better Dynamic Snow
  - Coldhaven
  - Reliquary of Myth

## 1.0.1: Minor update due to mod changes

**Released at**: `28.04.2020`

**Info**:

For some reason the installer was flagged to use 2.1.3?

**Changes**:

- Updated
  - Adamant - A Perk Overhaul
  - More to Say
  - Undead Werewolves

## 1.0.0: Initial Release

**Released at**: `27.04.2020`

**Info**:

This is the initial release of Elder Souls.

**Changes**:

- Added **everything**
