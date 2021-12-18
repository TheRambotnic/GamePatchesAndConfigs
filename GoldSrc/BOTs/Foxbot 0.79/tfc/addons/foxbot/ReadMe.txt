=================================
   FoxBot v0.77 For TFC
   http://www.foxbot.net
   And: http://www.omni-bot.com
=================================

Introduction
============

Foxbot is primarily a bot for the Half-Life mod Team Fortress Classic(AKA TFC).
The bots can build Sentry guns, capture flags, defend the base and basically
fight for victory in TFC.

There is a bit of a learning curve with the installation and configuration
of many Half-Life bots such as Foxbot.
If you have any problems please check out the documentation included and/or
the Foxbot websites(you can try the links shown at the top of this page).

________________________________________


Contents
========

1 - Installation Guide
2 - Installation Troubleshooting
3 - Other Information
4 - License Agreement
5 - Contacting the developers
6 - Credits

________________________________________


1 - Installation Guide
======================

The Windows version of Foxbot often comes in two flavours: a setup
program that tries to install everything for you, or a simple .zip file
that you should extract to the right directory.

If you are using a retail(boxed copy of Half-Life),
Install/extract to: C:\Sierra\Half-Life\

If you are using a listen server(Steam version),
Install/extract to: C:\Program Files\Steam\SteamApps\your@email.com\team fortress classic\

If you are using a dedicated server(Steam version),
Install/extract to: C:\Program Files\Steam\SteamApps\your@email.com\dedicated server\

If you are using the standalone server,
Install/extract to: C:\HLserver\

Whatever version of TFC you're running the basic idea is the same - install
or extract to the directory above the \tfc\ directory.

Here's an example of a working installation with the boxed copy of Half-Life:
C:\Sierra\Half-Life\tfc\                 (the main tfc directory)
C:\Sierra\Half-Life\tfc\addons\foxbot\   (the main Foxbot directory and it's contents)
C:\Sierra\Half-Life\tfc\addons\metamod   (the main Metamod directory and it's contents)

________________________________________


2 - Installation Troubleshooting
================================

If you are sure you've installed the Foxbot files in the right places,
but are still not seeing any bots then here are some things you can try.

In the main tfc directory is a text file called liblist.gam which
Half-Life uses in order to run mods such as Metamod, and Foxbot.
If it contains the line:
   gamedll "dlls\tfc.dll"
Then you should replace it with these two lines:
   //gamedll "dlls\tfc.dll"
   gamedll "addons\metamod\dlls\metamod.dll"

If you get a badf load error then it could mean that Metamod could not find
the Foxbot dll file with the path specified in plugin.ini.
plugin.ini is located in the tfc\addons\metamod directory.
If you open plugin.ini you'll probably see a line such as:

win32 ../tfc/addons/foxbot/FoXBot.dll

You can then check that this line is pointing out the right location of
the Foxbot.dll on your machine.

There is also more detailed information on Foxbot installation in the included
HTML help files.

________________________________________


3 - Other Information
=====================

Some tricks with FoxBot's file system.
Simply renaming a folder in the mods folder will disable that function.
Don't want to edit 50 bot config files to take out all the addbots commands?
Just rename the config folder to configs_ and they will be ignored.

If you have any other questions you can check out the HTML help included
as well.

________________________________________


4 - License Agreement
=====================

FoxBot is programmed and headed by Redfox.
Redfox takes no responsibility of any damage that may occurs because
of FoxBot on your computer (hasn't happened before).
FoxBot comes with no guaranteed support or warranty of any kind.
FoxBot is free under this agreement

- You may distribute FoxBot on a retail CD with proper recognition
  but contact us, we want to know!
- You can not attempt to de-compile FoxBot or deface it in any manner.
- You can not try to disguise FoxBot and pass it as your own.
- You can not hold any staff member liable for ANY damage FoxBot may cause.
- You can not sell or make a profit off of FoxBot.
________________________________________


5 - Contacting the developers
=============================

Email: polices@_REMOVE_ME_foxbot.net if you have any questions.
FoxBot's website: http://www.foxbot.net/
FoxBot's Forums: http://forums.foxbot.net/

You may find that the Foxbot website listed above is a bit inactive so a new
download area for the latest Foxbot releases, and a Foxbot forum can also be
found at the Omni-bot website:
www.omni-bot.com

________________________________________


6 - Credits
===========

Foxbot has been developed by:

Tom, Aka RedFox
Jordan, Aka FURY
Jeremy, Aka DrEvil
Paul, Aka GoaT_RopeR
Grubber
Yuraj
Richard, Aka Zybby

Thanks go to the Omni-bot developers for giving Foxbot a new home,
and to the Foxbot forum users for feedback and support.
