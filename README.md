# Game Patches, Fixes and Configs
This personal repository is meant to store all configs and patches for games I really love and am still playing or would like to return to at some point. Should also mention that these settings were tested on a Nvidia GT 1030 GPU because I'm broke. **WINDOWS USERS ONLY!**

| Table of Contents 							|
------------------------------------------------|
| [1. Folder names](#folder-names) 				|
| [2. Patches and stuff](#patches-and-stuff) 	|
| [3. Bots](#bots) 								|

## Folder names
Each root folder represents the name of the engine, and inside each one is a folder with the name of the game made with said engine. Most of the files are configuration and keybinds, but sometimes they can include actual patches.

There's also certain folders that contain complex names with brackets. Whatever files are inside of them, you must place them in the correct path inside of your computer.

**EXAMPLE:**
* idTech
	* DOOM (2016)
		* [%USERPROFILE%] [Saved Games] [id Software] [DOOM] [base]

The above example would correspond to Windows Explorer's path: `%USERPROFILE%/Saved Games/id Software/DOOM/base` for DOOM (2016)'s config files.

**One last thing:** some files could not be added to the repository due to file size, so I'll be linking them below.

## Patches and stuff
Please note that the majority of these patches are meant to be used with Steam.
* **Build**
	* Duke Nukem 3D - [EDuke32 Sourceport](https://www.eduke32.com/)
	* Blood - [NBlood Sourceport](https://github.com/nukeykt/NBlood/)
		* [Death Wish](https://www.moddb.com/mods/death-wish-for-blood)
	* Shadow Warrior - [Raze3D Sourceport](https://github.com/coelckers/Raze) (Replace `sw.exe` with `raze.exe`)
	<br/><br/>

* **Havok 2.0**
	* Painkiller: Black Edition - [Ultimate Community Patch RC3](https://drive.google.com/drive/u/0/folders/1cGoS4fiQLHw3v-EVVFcIoEDOb27SQgu6)
		* If the above doesn't work, try this [link](https://steamcommunity.com/sharedfiles/filedetails/?id=1789104850)
	<br/><br/>

* **idTech**
	* Quake - [Quakespasm Spiked Sourceport](https://triptohell.info/moodles/qss/) (Replace `glquake.exe` with `quakespasm-spiked-win64.exe`)
		* [Alkaline](https://www.quaddicted.com/reviews/alkaline.html)
			* [1.1 Patch](https://www.quaddicted.com/reviews/alkaline1.1.html)
		* [Dimension of the Past](https://www.quaddicted.com/reviews/dopa.html)
		* [Dwell - Episode One](https://www.quaddicted.com/forum/viewtopic.php?id=781)
		* [Slayer's Testament](https://www.moddb.com/mods/slayers-testament)
		* [Mission Packs 1 and 2: Scourge of Armagon + Dissolution of Eternity](https://drive.google.com/drive/u/0/folders/1REJwcdmbCA2CsaiFaBe4syKKPF9Lx8ji)
		* [Copper](http://lunaran.com/copper/)
		* [Underdark Overbright](https://www.quaddicted.com/reviews/udob_v1_1.html)
		<br/><br/>

	* Quake II - [Yamagi Quake II Sourceport](https://www.yamagi.org/quake2/) (Replace `quake2.exe` with `yquake2.exe`)
		* [Mission Packs 1 and 2: The Reckoning + Ground Zero](https://drive.google.com/drive/u/0/folders/12rMNDkdzS7j3xO1osFP4Nl80-PjFvYzW)
		<br/><br/>

	* Quake II - [KMQuake II Sourceport and Patches](http://www.markshan.com/knightmare/)
	<br/><br/>

* **Source**
	* Half-Life 2 - [QoL Improvements](https://drive.google.com/drive/u/0/folders/1QIhGnVIUntIBv5rkHvFDgDTcuYnwyowK)
	<br/><br/>

* **Unreal**
	* Unreal Gold - [Patch 227i](https://www.oldunreal.com/downloads/unreal/oldunreal-patches/)
	* Unreal Tournament - [Direct3D 10 Renderer](http://kentie.net/article/d3d10drv/)

## Bots
There are 3 bots for **GoldSrc**:
* CSBot 1.50 (for Counter-Strike 1.6)
* FoxBot 0.79 (for Team Fortress Classic)
* Parabot 0.91 (for Half-Life and Deathmatch Classic)

To install them, simply extract their contents into Half-Life's folder in your Steam directory.

**DISCLAIMER:** Please note that you CANNOT play Half-Life's singleplayer campaign when using Parabot. It is recommended that you make a backup copy of your `liblist.gam` file inside `<Your Steam Directory>/Half-Life/valve/`. To play the singleplayer campaign, simply replace Parabot's `liblist.gam` file with the one you backed up.