# New Bittboy & Pocket Go CFW Changelog

The next list is all the changes registered on the **custom firmware** version updates.

## Miyoo CFW 1.3.3 _(October 04, 2020)_

- **New Apps & Games**
  - New emulator Frodo2Go beta C64 emulator (note .d64 .t64 files only) thanks to pthalin.
  - New emulator ngpcemu neogeo pocket thanks gameblabla.
  - New emulator speccy spectrum thanks platformerAndroid.
  - New emulator crocods cpc  thanks pthalin.
  - New emulator added retro8 which is a PICO-8 emulator thanks to sauce.
  - New emulator Game&Watch NOTE to start game press the (sleep wake button & Y to start it)huge thanks to Steward-Fu for making this possible.
  - New emulator j2me java 0.0.2 emulator thanks pthalin.
  - New emulator msx  1.3.0 thanks pthalin.
  - New game heroes added thanks syzmor.
  - New game methane added thanks szymor.
  - New game stransball2 added thanks szymor.
  - New game just4qix added thanks to szymor & triforce.
  - New game MSX demo game The_Menace_from_Triton.permision given by author Santi Ontañón Villar thanks.
  - New game MSX demo game called BlockPuzzle permision given by author David -turbor- Heremans thanks.
  - New game added Western Bar cool shooting cowboy game (SELECT: exit game) thanks to Steward.
  - New game added NS.Shaft cool 2d platform game (SELECT: exit game) thanks to Steward.
  - New game MSX demo game we have got permission to add AlLIEN ATTACK PROMO DEMO ENHANCED EDITION by Marcos Daniel Blanco de Oliveira thanks.
  - New skin ported Nsdark to work switch theme skin s4ilence updated by harsh bhardwaj thanks to both.
  - New skin added New comicbook all artwork reworked by harsh bhardwaj thanks.
  - New skin added RetroWave all artwork reworked by harsh bhardwaj thanks.
  - New skin added Gameshow voted as the default theme by the community created by harsh bhardwaj thanks.

- **Updated Apps & Games**
  - Updated snes9x4d thanks m45t3r.
  - Updated pocketsnes thanks m45t3r.
  - Updated game Yatka to latest thanks szymor.
  - Updated gpsp_gameblabla v3 rumble updated thanks gameblabla.
  - Updated gpsp_rumble v4 thanks sauce Gameblabla
  - Updated mame4all.dge to latest thanks gameblabla.
  - Updated smsplusgx thanks gameblabla.
  - Updated Sorr game from v1.3.2 would not start.
  - Updated j2me java emulator to v0.0.3 with sound now thanks pthalin.
  - Updated to latest gambatte-dms thanks bardeci.
  - Updated msx emulator to v1.4.0 thanks pthalin.
  - Updated missing icons to NSdark skin for new releases other skins will be updated later.
  - Updated J2ME java emulator to bittboy-j2me_0.0.4. Fixed sound bug thanks pthalin.
  - Updated bittboy-msx emulator to v1.4.1 Minor fix for better sound thanks pthalin.
  - Updated speccy v0.1 remapped the buttons for pocketspeccy - so up a button,reset button quits now,CPU speed to 350 double the battery life,thanks platformerAndroid.
  - Updated snesadvance.dat has been placed in .snes9x4d.
  - Updated GPSP removed and replaced with GPSP Rumble as this is the better version of this emulator.
  - Updated C64 Frodo2Go emulator New features: Keyboard  (Start) Menu (R) Joystick port switch with indicator (Select) thanks to pthalin.
  - Updated C64 Frodo2Go v1.0.0 emulator New features: New: Snapshots with thumbnails (save/load of state) Add screenshot Massive code cleaning and optimization thanks to pthalin.
  - Updated C64 Frodo2Go v1.0.1 emulator Found a memory leak that causes it to hang randomly fixed thanks to pthalin.
  - Updated vectrex emulator updated as reported was corrupted in last cfw now fixed.
  - Updated Yatka game see below for changes v0.7"SRS wall kicking system, new implementation of easy spin (the old did not conform to Tetris Guideline),more dynamic controls,key configuration possible via modification of settings file,three new randomizers,new skins thanks to szymor.
  - Updated Fontigrid skin made by s4ilence updated by harsh bhardwaj thanks to both.

- **Other Updates & Changes**
  - New first boot logo changed to Miyoo CFW thanks Triforce & Dee.
  - New 2nd boot logo for Powkiddy devices added thanks Hi-ban.
  - libSDL_mixer-1.2.so.0.12.1 and timidity is installed in rootfs to allow the java app to have sound thanks dee & pthalin.
  - File added to all devices rootfs so developers can use this file to identify the type of device at runtime thanks pthalin.
  - V90 only L2 R2 buttons **will be activated in the next release**, for developers the Key Mapping is: L2 is Right ALT, R2 is Right SHIFT, thanks pthalin.
  - Cfw-info is just a file that can tell the current used device to an app.
  - New rom folders created for new emulators in roms.
  - Renamed all missing game names descriptions of games when scrolling in menu.

## Miyoo CFW 1.3.2 / PocketGo Only _(October 05, 2019)_

- Fixed fsck disk check was not working in v1.3.1
- New image size now 680mb zipped download :)
- Added new game reminiscence
- Added new game evil australians
- Added new game gnp
- Updated yatka game tetris clone
- Fixed FBA emulator not showing on home screen
- Added new icons for newer releases

## Miyoo CFW 1.3.1 _(September 23, 2019)_

- CFW version re-naming on New BittBoy to go with PocketGo v1.3.1
- New game GNP 
- Added PocketSNES snes emulator
- Changes to rootfs files to save more memory
- Correct version of bittboy circuitdude added
- Correct version of bittboy midnightwild added
- Profiled coleco shortcut to start screen
- New game yatka tetris clone
- New game xrick 2d platformer
- New game hocoslamfy flappy bird clone
- Added dingux-msx emulator
- Changed back to older release of GPSP GBA emulator
- New icons for default Font Grid theme added for the newer releases
- New zimage 
  - Fixes menu so you can press it in Outrun while pressing other keys
  - This means the default shortcuts change changed, see wiki for more info
- New miyoo_daemon v0.0.5
- Added screenshot functionality
  - Screenshots end up in main/screenshots
- **Note**: The link to FBA was missing somehow on PocketGo and Bittboy latest versions so can easily be added manually. This will be fixed on the next CFW.


## Bittboy CFW 4.2 / PocketGo CFW 1.3 _(August 21, 2019)_

- Gmenunx hold select & L will change volume up or down hold select & R will change backlight up down.
- Added latest fceux nes emulator (miyoofcfceu_20190807_by_koroneo) much better performance thanks to koroneo
- Added uae4all amiga emulator thanks to jamesofarrell
- Added vectrex emulator You need to have a copy of Minestorm in .vecxemu and name the file rom.dat.Otherwise it won't run as Minestorm also contains worth of 1kb of BIOS functions used by most games thanks to sauce.
- Added Circuit Dude game thanks to @crait
- Added chocolate-doom-modlaunch doom mods (Copy Doom 2 retail wad to /games/ccdoom (in main partition) with the filename Doom2.wad.) thanks to scooterpsu
- Updated gpsp_gameblabla_v3_rumble_mapping.zip thanks to sauce this is now the main GPSP emulator.
- Added comic-book skin HUGE THANKS TO Segich & SimplEasy FOR ARTWORK
- Updated SORR to v5.1 & now you can exit properly in game menu :)
- Updated fontigrid theme for new emulators & games thanks s4i
- Updated ST-SDL Terminal Emulator changed some of the key mappings in order to type faster, like Start is Enter and Select is Tab, also Reset now closes the program by Benob, Ported by SantX27 thanks.
- New miyoo_daemon 0.0.3 added battery detection. Once the battery gets below 3.55v the screen will flash every minute or so. The value can be adjusted by creating /mnt/.batterylow.conf. The default value is 3550.thanks to jamesofarrell
- updated edits to the bootup we have now hidden terminal screens on boot and when switching games etc so it looks clean the colors can be changed also see below default terminal color is same as bootlogo color.
- changed init script to silent output.
- Added custom terminal colors. Edit "/main/kernel/colors" to update them"
- New FB Driver for v3 v3.5 & pocketgo (version bug fixes) thanks to jamesofarrell
- New Zimage for all devices  (hold menu instead of select when adjusting brightness in game it stops the conflict in same games when you need to use select + something)
  - Disable Bootlogo
  - Disable Android specific code
  - Enable Squashfs support
  - Disable the kernel's NTFS code.
  - Set the block scheduler to deadline.
  - Disable Make rodata strictly non-executable
  - Enable experemental FPU code
  - Enable BLK_DEV_LOOP for OPK support


## Bittboy CFW 4.1 _(August 08 & 13, 2019)_

- New full image release due to some major changes to rootfs this is a full install and no upgrade available this time thank you all enjoy.
- Merged with latest GmenuNX release new features and better future support thanks ping_flood.
- Latest screen tearing fix & for some people experiencing distortion, thanks Roast (Only for Bittboy v3 and v3.5)
- Added sd sync patch fixes the forced shutdown corruption problem thanks SantX27 
- Gambatte has been updated Changes:below thanks Hi-Ban
  - Added an option to switch between mono and stereo sound. Default option (and recommended one) is Mono.
  - Removed L/R menu hotkeys for most devices. Now only the power/suspend button calls the menu.
- Added new fceux nes emulator much better performance thanks to koroneo
- Added new game Midnight Wild game thank's to @crait 
- Added comic-book theme for new gmenuNX ported by Jutleys to bittboy thanks to segich & simpleasy
- Added fontigrid theme for new gmenuNX support thanks s4i
- Added ST-SDL Terminal Emulator by Benob, Ported by SantX27 thanks.
- FBA added new fba release for arcade games thanks to Hank, see wiki for more info
- New daemon from jamesofarrell, see wiki for more info

## PocketGo CFW 1.2 _(August 01, 2019)_
- Merged with latest GmenuNX release new features and better future support thanks ping_flood
- Replaced the NXHope logo with image from Hi-Ban pocketgo logo thanks Hi-ban & scooterpsu
- New daemon from jamesofarrell thanks, see wiki for more info
- Replacement kernel from dee with shoulder button hotkeys (Start+button) removed thanks dee
- Latest screen tearing fix & for some people experiencing distortion thanks koroneo & Roast
- Added SD sync patch fixes the forced shutdown corruption problem thanks SantX27 
- Gambatte has been updated Changes:below thanks Hi-Ban
  - Added an option to switch between mono and stereo sound. Default option (and recommended one) is Mono
  - Removed L/R menu hotkeys for most devices. Now only the power/suspend button calls the menu
- Added new fceux nes emulator much better performance thanks to koroneo
- Added fontigrid theme for new gmenuNX support thanks s4i
- Added ST-SDL Terminal Emulator by Benob, Ported by SantX27
- FBA added new fba release for arcade games thanks to koroneo, see wiki for more info

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