# New Bittboy & Pocket Go CFW Changelog

The next list is all the changes registered on the **custom firmware** version updates.

## Bittboy CFW 4.0 _(July 17, 2019)_
- Minor update, installation simply unzip and overwrite into the main folder do not delete anything only overwrite
- GAMEBOY: New gambatte version (20190621) - Thanks surkow and hi-ban
  - Adds an 'auto' palette setting. Palette with the same name as the loaded rom will be automatically loaded
  - See pastebin link below for more information on using this feature
- GB(Rumble): (fix) Included correct rumble version of gambatte - Thanks steward
  - This version of gambatte supports rumble (on games that originally supported rumble), but has less features than the main gambatte port
- MIDNIGHTWILD: New Game Port! MidnightWild (Arduboy game) - Thanks crait
- NES: Updated FCEUX emulator - Thanks Scooterpsu

## PocketGo CFW 1.1 _(July 16, 2019)_
- COMMANDER: Updated with improved button mapping - Thanks scooterpsu
- GAMEBOY: Updated gambatte (20190621) - Thanks surkow and hi-ban
  - Adds an 'auto' palette setting. Palette with the same name as the loaded rom will be automatically loaded
  - See wiki for more information on using this feature
- GB(Rumble): (fix) Included correct rumble version of gambatte - Thanks steward
  - This version of gambatte supports rumble (on games that originally included rumble), but has less features than the main gambatte port. Rumble is currently extremely weak on pocket-go.
- GMENU2X: (Main Menu) Updated with improved button mapping, layout improvements - Thanks scooterpsu
  - Press 'B' to exit from the ROM selector (previously 'Start')
  - Press 'X' to move up one level in the folder structure 
- GMENU2X: (fix) Grid theme set as default skin
- MEGADRIVE: Updated picodrive emulator - Thanks scooterpsu
- MIDNIGHTWILD: New Game Port! Midnight Wild (Arduboy game) - Thanks crait
- MISC: Default button mapping fixes: Included config files for GAMEBOY, GBA, NES, MEGADRIVE, PS1 and GB(ohboy)
- MISC: Speaker/headphone buzzing noise greatly reduced - included PWM fix - Thanks BytePorter
- NES: Updated FCEUX emulator - Thanks scooterpsu
- SNES: Updated snes9x4d emulator - Thanks scooterpsu

## Bittboy CFW 3.9 / PocketGo CFW 1.0 _(June 10, 2019)_ 
- PokéMini: New Emulator Added! Pokemon Mini (pokemini emulator) - Thanks scooterpsu
- GamBatte: Updated and sorted the included palettes - Thanks 2TMAU5 
  - See wiki for information on using more of the included palettes
- SMS/GG: SMS Plus GX emulator updated with input remapping support - Thanks sauce
- SNES: Optimised SNES9X - Thanks scooterpsu
  - Save location updated from '.snes96_snapshots' to '.snes9x4d'. If upgrading move old save files
- Heretic: Shareware datafile included
  - To play full version, copy HERTIC.WAD to 'games\hheretic'
- Hexen: Fix - Game now runs fullscreen - thanks scooterpsu
- Hexen: Shareware datafile included
  - To play full version, copy HEXEN.WAD to 'games\hhexen'
- Strife: New Game Added! Chocolate Strife - Thanks scooterpsu
  - Requires the retail STRIFE1.WAD datafile to be copied to 'games\ccdoom'
- Skin: New default skin: Grid theme. Updated with new font, additional wallpapers and other improvements - Thanks 2TMAU5


## Bittboy CFW 3.8 _(May 13, 2019)_
- LYNX: New Emulator Added! Atari Lynx (Handy Emulator) - Thanks Sauce
 - Place ROMs in /roms/LYNX/ 
- DOS: Now boots to LaunchBox for MS-DOS SE 2.0
  - Included Commander Keen shareware episode 1 "Marooned on Mars"
  - See wiki for information on usage and adding additional games 
- GAMEBOY: Included additional gambatte palettes - Thanks MrRobotSK 
- GBA: Modfied GPSP control mapping screen text 
- NEOGEO: Enabled gmenu ROM selector. Fixed issue causing the emulator to quit unless a game was first selected using the internal gngeo ROM selector 
- NEOGEO: ROM selector will display game name rather than zip file name (added alias file) - Thanks scooterpsu 
- SNES: SNES button mapping now correctly matches SNES controller face button layout - Thanks scooterpsu 
- SOD: Corrected loading of included shareware datafiles - Thanks scooterpsu 
- SOD: Added new version of Spear of Destiny with support for retail/full datafiles - Thanks scooterpsu
  - See wiki for retail version setup information
- WOLF3D: Added new version of Wolfenstein 3D with support for retail/full datafiles - Thanks scooterpsu
  - See wiki for retail version setup information
- MPLAYER: Configuration updated with new features - Thanks scooterpsu
  - Control volume and backlight brightness without exiting
  - Non-4:3 video is no longer stretched
  - Automatically resume videos where you left off
- SKIN: (From CFW3.7) Added 'Grid Theme' - Thanks 2TMAU5
  - When using this skin, set 'Section Bar Position' to 'Bottom' and select a wallpaper with a name beginning with 'GRID' from within the skin section of gmenu
- SKIN: Corrected loading of some missing icons in oldboy skin (where available) 
- GMENU: Default backlight timeout increased from 30 to 90 seconds

## Bittboy CFW 3.7 Beta 2 _(May 13, 2019)_
- New kernel added fix screen issue (v3 owners only) got where the top portion of the screen would show up on the bottom thank's to da1writer & Steward
- Added new gambatte release from Hiban thanks.
- To shut down safely: From the main menu hold the 'R' button and press 'A' to shut down. Flick the power switch once the screen goes black' and maybe extend default screen timeout before it goes off

## Bittboy CFW 3.7 Beta 1 _(May 09, 2019)_

- Borders and palette files for gambatte and ohboy moved (fixes these not being available in the emulator's setting)
- Config file for picodrive included. Default mapping B=A, A=B, TA=C, can be configured in the emulator's settings menu. (Fixes issue with all 3 buttons not being mapped by default)
- Emulator titles renamed
- Emulator list sorting changed. Sort order can be configured by renaming the files within 'gmenu2x\sections\emulators'. All files begin with a number (eg '01-gambatte'), change numbering to change display order.
- Set default ROM path for some emulators, see emulator info on wiki
- 2 emulator executables renamed to work with skin icons ('\emus\gambatte\gambatte-bittboy' to 'gambatte','\emus\gpsp_gameblabla\gpsp' to 'gpsp_gameblabla')
- Icon files for emulators renamed to correctly load when skin is changed (fixes skins using default skin icons rather than their own for many emulators)
- Removed non-functional emulator shortcut files in 'gmenu2x\sections\emulators'
- Removed Older Sega Master System emulator. SMS Plus GX is now the default emulator for SMS and Game Gear.

## Bittboy CFW 3.6 _(May 02, 2019)_

- Support for V2 & V3 users
- Added Fontes amazing skin thanks Fontes
- Added custom pallets for ohboy thanks 2tmau5
- Added custom borders for gambatte thanks da1writer
- Added new build of gambatte thanks Hi-ban
- Added polish translation to gmenu2x thanks Macmmm81
- New wallpapers added from competition winners thank you all
- New wallpapers added from Fontes thank you
- Skin colors can now be changed from the settings thank you cutbot001
- New bittboy boot logo thank you to both Hi-ban and scooterpsu for helping implement the logo.
- Added MPLAYER supports 320x240 30fps h.264 with fast decode thanks sauce.
- Updated new build of gambatte again thanks Hi-ban 28/4/19
- Added spear of destiny full your need your own backup files thank to scooterpsu
- Added new skin SFC thanks to simpleasy for all the new icons.
- Fat32 corruption fix implemented thanks to scooterpsu
- Added new icons for Fontes theme thanks to Fontes for the missing disk icons

## Bittboy CFW 3.5 _(April 11, 2019)_

- Updated gpsp_20190409.zip Support rumble feature thanks steward
- Added gambatte_sdl_20190409.zip Support rumble feature thanks steward
- Added port of SMS Plus GX. This is based on sauce improved fork with several fixes thanks sauce
- Added gpsp_gameblabla_v2_remapping.zip thanks sauce
- Added custom_pallets_pack_v1 to stewards gambattle release.

## Bittboy CFW 3.4 _(March 28, 2019)_

- Added pang game Porting from RS97 source thanks steward
- Updated gmenu2x Fix suspend issue (issue: GMenu2X is always in work mode when PoweroffTimeout value is equal to zero) thanks steward
- Fixed gmu Fix backlight issue (issue: failed to turn off backlight LED when sleep) thanks steward
- Updated gpsp_Remap buttons (Miyoo_B:GBA_L, Miyoo_TB:GBA_R) Support L and R buttons (hardware mod) thanks steward
- Added wqx porting from Android source thanks steward
- Updated new gambattle release thanks Hi-ban
- Added how to update beta releases pdf guide inc with the beta releases thanks to Alexai

## Bittboy CFW 3.3 _(March 23, 2019)_

- Added hheretic port thanks steward
- Added hhexen port thanks steward
- Added king of fighters thanks steward
- Added ROTT thanks steward
- Updated skin megaskinKCH2019 thanks cut1001
- Updated gmenu2x fix backlight issue and change poweroff timeout setting thanks steward.

## Bittboy CFW 3.2 _(March 20, 2019)_

- Added mame4all arcade emulator thanks steward
- Update mame4all Updated cheat.dat & Fix rom list issue (issue: cursor disappaear when too mamy roms put in folder thanks steward
- Add new skin megaskinKCH2019 thanks cut1001
- Update fceux optimise code thanks steward.
- Added bard thanks steward
- Gngeo updated game fixes thanks steward
- Added liero thanks steward
- Updated mame4all bug fixes thanks steward

## Bittboy CFW 3.1 _(March 14, 2019)_

- Fixed quake not starting changed set cpu 702mhz 
- Added wonderswan emulator back thanks sauce 
- Added gamebattle gb emulator (B => quick save,TB => quick load) thanks steward *swapped to gpsp_gameblabla to fix input lag problems thanks sauce 
- Fixed gambattle emulator (change A and B button, remove hotkey for both quick save/load) thanks steward 
- Music player gmuplayer (A: add into play list START: change tab page SELECT -> START: exit R Menu: blank screen R(START + A): turn screen on) thanks steward. 
- Added wizwrite thanks steward 
- Added new game tombstone thanks steward 

## Bittboy CFW 3.0 _(March 08, 2019)_

- Supports V1 & V2 (V1 users must Hard mod only)
- 1 image to flash for both V1 & V2 now
- For v1 bittboy, it needs 4bit hardware mod
- For v2 bittboy, no hardware mod required
- R is power button
- TA TB  page down page up
- Press R will into suspend mode
- Press R again will back to normal
- Hold 10seconds will pop shutdown dialog thanks Steward
- Added sharware files for quake
- Added shareware files fore quake 2

## Bittboy CFW 2.0 _(March 06, 2019)_

- Latest framebuffer fix thanks to steward
- Latest zImage fix thanks to steward
- Updated fceux for LoadState/SaveState issue
- Added asciiportal game thanks steward
- Cavestory game thanks sauce
- Added cdogs game thanks steward
- Added digger game thanks steward
- Added mr drillux game thanks steward
- Added sorr game thanks steward
- Added openbor emulator thanks steward
- Added opentyrian game thanks sauce
- Added stella emulator thanks sauce
- Added openbor update fixed color issue thanks steward
- New zimage fixed headfone sound problems thanks steward.

## Bittboy CFW 1.0 _(February 25, 2019)_

- Latest framebuffer fix thanks to steward
- Latest zImage fix thanks to steward
- Added cannonball thanks to sauce
- Added dosbox thanks to steward
- Added gngeo thanks to steward
- Updated gpsp thank to steward
- Added oswan thanks to sauce
- Updated ohboy with templates thanks to steward
- Updated pcsx_rearmed thanks to steward
- Ccdoom updated for full screen thanks to steward
- Added quake port thanks to sauce
- Added quake 2 port thanks to sauce
- Added sdlpal_v2 thanks to steward
- Added wolf3d port thanks to steward
- Updated gmenunx thanks to pingflood steward