# PSYCHRONIC_MegaVictoryMZ

**RPG Maker MZ Plugin**

Adds Extra Functionality to victory section of RPG Maker MZ.

## What It Does

MEGA VICTORY MZ - Enhanced Victory Screen.

## Plugin File

- `PSYCHRONIC_MegaVictoryMZ.js`
- Target: RPG Maker MZ
- Author: Psychronic
- URL: https://psychronic.itch.io

## Parameter Summary

- showLevels: Show current level and level-up information
- showLevelProgress: Show visual progress bar to next level
- playLevelUpSound: Play a sound effect when a character levels up
- levelUpSE: Sound effect to play on level up
- expAnimationSpeed: Speed of EXP bar animation (higher = faster)
- expBarColor1: Starting color for EXP bar gradient (hex format)
- expBarColor2: Ending color for EXP bar gradient (hex format)
- consumableColor: Color for consumable items (hex format)
- keyItemColor: Color for key items (hex format)
- weaponColor: Color for weapons (hex format)
- armorColor: Color for armor (hex format)
- descriptionFontSize: Font size for item descriptions

## Installation

1. Download `PSYCHRONIC_MegaVictoryMZ.js`.
2. Place it in your RPG Maker MZ project's `js/plugins/` folder.
3. Enable it from the RPG Maker Plugin Manager.
4. Configure any plugin parameters or commands listed below.

## Full Plugin Help

### MEGA VICTORY MZ - Enhanced Victory Screen

This plugin completely overhauls the victory screen in RPG Maker MZ with
a modern, visually appealing two-stage display:

Stage 1 - Experience Screen:
- Shows all party members with their portraits
- ANIMATED EXP bars that fill up based on gained experience
- Animated level-up notifications
- Optional level display toggle
- Advance manually with OK button

Stage 2 - Rewards Screen:
- Shows items acquired during battle with descriptions
- Displays gold earned
- Uses enhanced visual styling similar to MegaItems
- Color-coded item types with gradient backgrounds
- Advance manually with OK button

### Plugin Parameters

@param showLevels
@text Show Character Levels
@type boolean
@default true
@desc Show current level and level-up information

@param showLevelProgress
@text Show Level Progress Bar
@type boolean
@default true
@desc Show visual progress bar to next level

@param playLevelUpSound
@text Play Level Up Sound
@type boolean
@default true
@desc Play a sound effect when a character levels up

@param levelUpSE
@text Level Up Sound Effect
@type file
@dir audio/se
@default Up4
@desc Sound effect to play on level up

@param expAnimationSpeed
@text EXP Animation Speed
@type number
@min 1
@max 100
@default 30
@desc Speed of EXP bar animation (higher = faster)

@param expBarColor1
@text EXP Bar Color 1
@type string
@default #44ff88
@desc Starting color for EXP bar gradient (hex format)

@param expBarColor2
@text EXP Bar Color 2
@type string
@default #44aaff
@desc Ending color for EXP bar gradient (hex format)

@param consumableColor
@text Consumable Item Color
@type string
@default #44ff88
@desc Color for consumable items (hex format)

@param keyItemColor
@text Key Item Color
@type string
@default #ffaa44
@desc Color for key items (hex format)

@param weaponColor
@text Weapon Color
@type string
@default #ff6644
@desc Color for weapons (hex format)

@param armorColor
@text Armor Color
@type string
@default #4488ff
@desc Color for armor (hex format)

@param descriptionFontSize
@text Description Font Size
@type number
@default 14
@desc Font size for item descriptions

## Source

This standalone repository is generated from the latest PSYCHRONIC plugin source in the RPG Reactor Complex template.

## License

MIT. See `LICENSE`.
