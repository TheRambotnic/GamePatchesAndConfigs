# Game Patches, Fixes and Configs
This personal repository is meant to store all configs and patches for games I really love and am still playing or would like to return to at some point. Should also mention that these settings were tested on PC containing a Nvidia GT 1030 GPU and Intel i5-9400F CPU because I'm broke. **WINDOWS USERS ONLY!**

| Table of Contents 										|
|-----------------------------------------------------------|
| [1. Folder names](#folder-names) 							|
| [2. Patches](#patches) 									|
| [3. Mods](#mods) 											|
| [4. Bots](#bots) 											|
| [5. Steam launch parameters](#steam-launch-parameters)	|

## Folder names
Each root folder represents the name of the engine, and inside each one is a folder with the name of the game made with said engine. Most of the files are configuration and keybinds, but sometimes they can include actual patches.

There's also certain folders that contain complex names with brackets. Whatever files are inside of them, you must place them in the correct path inside of your computer.

**EXAMPLE:**
* idTech
	* DOOM (2016)
		* [%USERPROFILE%] [Saved Games] [id Software] [DOOM] [base]

The above example would correspond to Windows Explorer's path: `%USERPROFILE%/Saved Games/id Software/DOOM/base` for DOOM (2016)'s config files.

**One last thing:** some files could not be added to the repository due to file size, so I'll be linking them below.

## Patches
Please note that the majority of these patches are meant to be used with Steam.

* **Build**
	* Duke Nukem 3D
		* [EDuke32 Sourceport](https://www.eduke32.com/)
	<br/><br/>

	* Blood
		* [NBlood Sourceport](https://github.com/nukeykt/NBlood/) (Replace `anuket_x64.exe` with `nblood.exe`)
	<br/><br/>

	* Shadow Warrior
		* [Raze3D Sourceport](https://github.com/coelckers/Raze) (Replace `sw.exe` with `raze.exe`)
	<br/><br/>

* **Havok 2.0**
	* Painkiller: Black Edition
		* [Ultimate Community Patch RC3](https://drive.google.com/drive/u/0/folders/1cGoS4fiQLHw3v-EVVFcIoEDOb27SQgu6) - If that link doesn't work, try [this one](https://steamcommunity.com/sharedfiles/filedetails/?id=1789104850)
	<br/><br/>

* **idTech**
	* Quake
		* [Quakespasm Spiked Sourceport](https://triptohell.info/moodles/qss/) (Replace `glquake.exe` with `quakespasm-spiked-win64.exe`)
		* [Mission Packs 1 and 2: Scourge of Armagon + Dissolution of Eternity](https://drive.google.com/drive/u/0/folders/1REJwcdmbCA2CsaiFaBe4syKKPF9Lx8ji)
		<br/><br/>

	* Quake II
		* [Yamagi Quake II Sourceport](https://www.yamagi.org/quake2/) (Replace `quake2.exe` with `yquake2.exe`)
		* [KMQuake II Sourceport and Patches](http://www.markshan.com/knightmare/)
		* [Mission Packs 1 and 2: The Reckoning + Ground Zero](https://drive.google.com/drive/u/0/folders/12rMNDkdzS7j3xO1osFP4Nl80-PjFvYzW)
		<br/><br/>

	* Return to Castle Wolfenstein
		* [Patch 1.42d](http://kmq2.toastednet.org/downloads/rtcw-sp-1.42d-win32-bin.zip)
		<br/><br/>

* **GoldSrc**
	* Half-Life
		* [Xash3D FWGS Sourceport](https://github.com/FWGS/xash3d-fwgs/)
		<br/><br/>

* **Source**
	* Half-Life 2
		* [QoL Improvements](https://drive.google.com/drive/u/0/folders/1QIhGnVIUntIBv5rkHvFDgDTcuYnwyowK)
	<br/><br/>

* **Unreal**
	* Unreal Gold
		* [OldUnreal's Patch 227i](https://www.oldunreal.com/downloads/unreal/oldunreal-patches/)
	<br/><br/>

	* Unreal Tournament
		* [Direct3D 10 Renderer](http://kentie.net/article/d3d10drv/)
		* [OldUnreal's Patch 469b](https://github.com/OldUnreal/UnrealTournamentPatches/releases/tag/v469b)
		* [foxWSFix99](https://github.com/alexstrout/foxWSFix-UT99)
	<br/><br/>

## Mods
These are some mods that I really enjoy and figured I might link them here

* **Blood**
	* [Death Wish](https://www.moddb.com/mods/death-wish-for-blood)
	<br/><br/>

* **Quake**
	* [Alkaline](https://www.quaddicted.com/reviews/alkaline.html)
		* [1.1 Patch](https://www.quaddicted.com/reviews/alkaline1.1.html)
	* [Dimension of the Past](https://www.quaddicted.com/reviews/dopa.html)
	* [Dwell - Episode One](https://www.quaddicted.com/forum/viewtopic.php?id=781)
	* [Slayer's Testament](https://www.moddb.com/mods/slayers-testament)
	* [Copper](http://lunaran.com/copper/)
	* [Underdark Overbright](https://www.quaddicted.com/reviews/udob_v1_1.html)
	<br/><br/>

* **Half-Life:**
	* [Azure Sheep](https://www.moddb.com/mods/azure-sheep)
	* [Brutal Half-Life](https://www.moddb.com/mods/brutal-half-life)
	* [Half-Life: Black Ops](https://www.moddb.com/mods/black-ops)
	* [Half-Life: Delta](https://www.moddb.com/mods/half-life-delta)
	* [Half-Life: Field Intensity](https://www.moddb.com/mods/field-intensity)
	* [They Hunger](https://www.moddb.com/mods/they-hunger)
	* [Residual Point + Residual Life](https://www.runthinkshootlive.com/posts/residual-life/)
	* [Gunman Chronicles](https://www.moddb.com/games/gunman-chronicles)
	* [Sweet Half-Life](https://www.moddb.com/mods/sweet-half-life)
	* [Poke646](https://www.moddb.com/mods/poke646-anniversary-edition)
	* [Signal Lost](https://www.moddb.com/mods/signal-lost)
	<br/><br/>

## Bots
There are 3 bots for **GoldSrc**:
* CSBot 1.50 (for Counter-Strike 1.6)
* [FoxBot](https://github.com/APGRoboCop/foxbot) (for Team Fortress Classic)
* [Parabot](https://github.com/nekonomicon/Parabot/) (for Half-Life and Deathmatch Classic)

**Dependencies**
* [Metamod](http://metamod.org)

To install them, simply extract their contents into Half-Life's folder in your Steam directory.

**DISCLAIMER:** Please note that you CANNOT play Half-Life's singleplayer campaign when using Parabot. It is recommended that you make a backup copy of your `liblist.gam` file inside `<Your Steam Directory>/Half-Life/valve/`. To play the singleplayer campaign, simply replace Parabot's `liblist.gam` file with the one you backed up.

## Steam launch parameters
To use these: right click the game > Properties > Launch Options

- AMID EVIL: `-nosplash -USEALLAVAILABLECORES -heapsize 2097152`
- BioShock: `-nointro`
- DOOM: `+set com_skipIntroVideo 1 +set r_skipFog 1 +vt_maxAniso 1 +r_shadowAtlasWidth 32 -USEALLAVAILABLECORES -heapsize 2097152 -sm4`
- Half-Life (and general GoldSrc Engine games): `-noforcemaccel -noforcemparms -noforcemspd -w [MONITOR WIDTH] -h [MONITOR HEIGHT] -nomsaa -nofbo +gl_vsync 0 +fps_max 72 +fps_override 1 +rate 20000 +cl_cmdrate 106 +cl_updaterate 101`
	- If using Xash3D, replace `-w` and `-h` with `-width` and `-height` respectively, and add `-console` to enable the console
- Half-Life 2 (and general Source Engine games): `-novid -nojoy -w [MONITOR WIDTH] -h [MONITOR HEIGHT] -high +mat_motion_blur_percent_of_screen_max 0 +mat_postprocess_enable 0`
- Quake (using QuakeSpasm Spiked): `-fitz -sndspeed 44100 -heapsize 1024000 +g_showintromovie 0`
- Wolfenstein The New Order: `+set com_skipIntroVideo 1 +set com_allowConsole 1 +cvaradd r_skipPostProcess 1 +cvaradd r_skipFog 1 +cvaradd r_skipFlares 1 +cvaradd r_skipSunFlares 1 +cvaradd r_skipGodRays 1`