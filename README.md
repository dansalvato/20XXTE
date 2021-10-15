![20XXTE logo](https://user-images.githubusercontent.com/7810794/134628260-4fee49c1-5123-4edf-b76a-9c89238aafaf.png)

# Overview
20XX Tournament Edition (20XXTE) is a mod for Super Smash Bros. Melee that provides over 50 new features and quality-of-life improvements for competitive players. The entire mod is contained in a Melee save file and can be loaded by a normal Melee disc on any GameCube or Wii, without any homebrew required.

## Tournament Usage
20XXTE is designed to work well in tournament settings of any size. It contains a "Tournament Mode" switch that disables all features of the mod that could interfere with tournament play, such as training tools, while still providing players with great quality-of-life improvements. Only a single memory card is needed to load 20XXTE on every setup in a tournament venue.

## Home Usage
When using it at home, 20XXTE provides various features that can help with training or make friendlies more enjoyable. There are some fun aesthetic customizations, game adjustments to expedite friendlies, and convenient training tools.

## Features
<details>
  <summary>General Conveniences</summary>
  
  * All characters, stages, and trophies unlocked
  * Game settings set on boot: 4 stock, 8 minutes, Friendly Fire on
  * Title screen demo and intro video disabled
  * Special messages disabled
  * C-Stick enabled in 1P modes
  * Unrestricted pause camera
  * Start VS matches with only 1 player
  * Handicap is now used to control players' individual stock counts
  * Nametags disappear during Zelda/Sheik/Mewtwo teleport upB (except in doubles)
  * Pressing Start on match results screen doesn't undo your ready state (re-mapped to B)
  * Press D-pad up/down on character select screen to toggle rumble on/off
  * "Name Entry" is moved to the top of the nametag list
  * CPU Zelda will start as Sheik and never transform
  * Player ports can be closed even if the respective hand is still hovering over the characters
  * 20XXTE version displayed in upper-left corner of Character Select Screen
  
</details>

<details>
  <summary>Global New Features</summary>
  
  * Replays - Save or play back match replays by pressing Z on the character select screen
  * Extended Name Entry - up to 8 characters on name entry screen
  * Press X for lowercase characters on name entry screen
  * Choose your menu music by playing a song in Sound Test
  * Stage Striking - press X on Stage Select to strike stages
  * Frozen Mode - press Y on Stage Select to disable stage hazards
  * Hand-Wamer Mode - 1-minute Time matches prevent characters from interfering with each other for hand-warmers
  
</details>

<details>
  <summary>Tournament Features</summary>
  
  These features are available whether the Tournament Mode switch is on or off.
  
  * Tournament Mode switch disables all intrusive aesthetic/mechanic changes
  * Tournament settings and stage list are automatically reset between games during tournament matches
  * Neutral Spawn Points - players always spawn in neutral starting locations
  * UCF (Universal Controller Fix) on/off
  * Game Version - Toggle between v1.00 and v1.02 (affects hitlag behavior, Bowser's Flame Cancel, Link/YLink boomerang cancel, and Ness PK Thunder hitbox)
  * 16:9 widescreen mode on/off
  * Frozen Mode on/toggle/off
  * Pausing requires holding Start on/off (prevents accidental pauses during matches)
  * Enable slightly reduced volume of Dream Land 64 music (to improve venue acoustics)
  * Lock settings to prevent tampering during tournaments
  * Ability to auto-save replays after every match
  * Compatbility with v1.00/v1.01 versions of Melee (with limited features)
  
</details>

<details>
  <summary>Non-Tournament Features</summary>
  
  These features are only available when the Tournament Mode switch is turned off.
  
  * "Ready To Fight" banner is green to indicate that Tournament Mode is disabled
  * Skip Results Screen on/off
  * Randomize Stage Music on/off
  * Extra Shield Colors on/off
  * Disable Screen Rumble during powerful attacks on/off
  * Character flashes on successful/unsuccessful L-cancel on/off
  * Spoof Controller Plugins on/off
  * Hold A+B to quickly restart match on/off
  * Enable Taunt Cancelling on/off
  * Disable Star KO animation to speed up matches on/off
  * L-Cancel Training Wheels on/off (automatically L-cancel, but flash on successful input)
  * Toggle Infinite Shields on/off (When on, CPUs also hold shield to help with training)
  * Toggle Fixed Camera on/off
  * Toggle Collision Bubbles on/off
  * Unfreeze endgame: Disables freezing on "GAME!", enabling another 2 seconds of movement before the match results
  * Input display HUD on/off: Shows an input display in the corner of the screen during matches or replays
  * CPU Smart DI on/off: Random DI and teching for CPUs, and survival DI used against powerful attacks
  * Color Overlays on/off: Characters turn green when idle to show frame holes during movement
  
</details>

<details>
  <summary>What 20XXTE Doesn't Do</summary>
  
  * Texture, music, or file replacements of any sort (no custom skins/costumes)
  * Character changes (PAL or other unofficial character patches)
  * Add new stage layouts
  * Allow the player to change their controls or disable tap jump
  
</details>

# Installation

[Download Latest Release](https://github.com/dansalvato/20XXTE/releases/latest)

<details>
  <summary>Method 1: Save File Copy</summary>
  
  Many local tournament venues use 20XXTE. The easiest way to install 20XXTE is to copy it from another memory card that has it installed. Since it is just a Melee save file, this can be done by using the normal data copy offered on GameCube and Wii. There is also a "Copy 20XXTE" menu available in Melee itself, for extra convenience.
</details>

<details>
<summary>Method 2: Wii Homebrew</summary>
  
  [Video walkthrough by fornclake](https://www.youtube.com/watch?v=IotsXdokOMg)

  This method requires a Wii with the Homebrew Channel installed.

  1. Download the latest version of [GCMM](https://github.com/suloku/gcmm/releases/latest). Extract the GCMM download and copy the "apps" folder to your SD card. Choose 'Yes' to merge/replace any files if prompted.
  2. Create a folder on your SD card called "MCBACKUP" and copy 20XXTE.gci to that folder.
  3. Remove the SD card from your PC and insert it into your Wii.
  4. Launch the Homebrew Channel. Select GCMM from the apps list and load it.  
    *If you don't see GCMM in the list, make sure you copied the "apps" folder to the right place. Your SD card should look like:* `apps/gcmm/boot.dol`
  5. When GCMM loads, press A to select the SD card as your storage device.
  6. (Optional) If you want to back up your existing Melee save data, press Y to enter Backup mode. Then, press A to select Slot A. Select the file "SuperSmashBros0110290334" and press A to backup.
  7. In the "Choose your mode" menu, press X to enter Restore mode. Then, press A to select Slot A. Select 20XXTE.gci from the file list and press A to restore the data.
  8. Overwrite your existing save data if prompted.
  9. You're done.
</details>

<details>
<summary>Method 3: Dolphin Emulator</summary>
  
  If you want to load 20XXTE in Dolphin, you simply need to copy the .gci file to the correct location.

  Windows: `Documents\\Dolphin Emulator\\GC\\USA\\Card A\\01-GALE-SuperSmashBros0110290334.gci`

  macOS: `~/Library/Application Support/Dolphin/GC/USA/Card A/01-GALE-SuperSmashBros0110290334.gci`
  
  **NOTE:** You must also disable the "Enable Cheats" setting in Dolphin config. 20XXTE cannot be loaded alongside other codes.
</details>

# Starting Up
1. Make sure the game is powered off completely. Insert your 20XXTE memory card and power on the game.
2. Go to VS Mode > Name Entry
3. If loaded correctly, you will be taken back to the title screen with "20XX Tournament Edition" written across the top of the screen.
4. Enjoy 20XXTE!

# More Information
[20XXTE Usage Guide](http://www.20xx.me/guide.html)

[20XXTE FAQ](http://www.20xx.me/faq.html)

# Source Code
20XXTE can be compiled from source using [Melee GCI Compiler](https://github.com/dansalvato/melee-gci-compiler) version 2.0.0 or newer:

`python3 melee_gci_compiler.py -o 20XXTE.gci source/20XXTE.mgc`

Cloning this repo and compiling the source will always result in a byte-for-byte exact copy of the latest version of 20XXTE; no code "in between versions" is ever published to the main branch.

Also, porting the 20XXTE source code to Melee GCI Compiler (and this repo) is an ongoing project. That means the source files are currently full of binary data and assembled machine code. Over time, they will be replaced with documented versions of the original source code. Most changes to the main branch will be for the purpose of open-sourcing more parts of the project, and will not produce any changes to the compiled save file.

# Acknowledgements
Thanks for your interest in 20XX Tournament Edition. This project would not be possible without the hard work and dedication of Achilles, wParam, Magus, Zauron, and all of my other friends in the modding community whose names number too great to list. 20XXTE contains code that has generously been made freely available from these contributors.

20XXTE also contains Universal Controller Fix (UCF), which was developed and/or supported by: tauKhan, Kadano, UnclePunch, Dan Salvato, HRC Typo, and PracticalTAS.
