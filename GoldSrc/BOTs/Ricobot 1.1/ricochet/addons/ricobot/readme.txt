*** ADAPTED FROM HPB BOT README FILE ***

Ricobot - a simple bot for Ricochet
by Wei Mingzhi alias Whistler
(http://yapb.bots-united.com)
Readme File

This software is based on HPB bot Template #3 by botman
(http://www.planethalflife.com/botman).


How to start the game:

Click on "Custom game", then click on "Ricochet", then click on "Activate".
Click on "Done", then click on "Multiplayer".  Click on "LAN game", then
click on "Create game".  Click on the map name that you wish to play then
click on "OK" to start the game.

Bots will automatically be added to the game using the "bot.cfg" file
found in the ricochet directory.  If you wish to change the number of
bots that are created automatically you can edit the bot.cfg file using
any text editor (like Notepad).


How to change the default names of the bots:

The names come from a text file called "bot_names.txt".  You will find
this file in the Ricochet folder.  Edit this file with any text editor
(like Notepad) and add or delete names.  The bot names can be up to 32
characters long and you can have a maximum of 100 names total.  Each name
should be on a separate line with no leading spaces.


How to create map specific bot.cfg files:

You can create a bot.cfg file that has specific commands for each map by
creating a text file in the "maps" directory.  The file name should begin with
the same name as the map followed by "_bot.cfg" (for example
maps\rc_arena_bot.cfg or maps\rc_deathmatch_bot.cfg). The commands contained
in the map specific bot.cfg file are the same as the ones found in the
default bot.cfg file (the one found in the ricochet directory).  If a map
specific bot cfg file does not exist then bots will be respawned based on how
many bots were in the previous level.  You can specify the name and skill of
the bots for each map using these map specific bot.cfg files (by
specifying them in the "addbot" command).  When the server is started, if a
map specific config file exists for the first map then it will be used to
spawn the bots.  If a map specific bot.cfg file does not exist for the
first map then the bot.cfg file (in the ricochet directory) will be used to
spawn the bots.  It is important to note that the bot.cfg file found in
the ricochet directory will only be executed ONCE (on the first map if no map
specific bot.cfg file exists).  In other words, the bot.cfg file is
only executed once for the first map, from then on only map specific
bot.cfg files will be executed.


Common questions:

Q: Will I be able to play Ricochet on the Internet or on a LAN with the bot
   installed ?
A: Yes ! You can join a network game over the Internet or on a LAN without
   having to uninstall the bot.  You cannot spawn bots when connected to
   an Internet server, but you can spawn bots on a LAN if you are running the
   server.

Q: Do I need waypoints to play with the Ricobot ?
A: No, the bots are able to do unwaypointed movement. However, they just jump
   from one platform to another randomly. Currently they can't find a path
   to somewhere or get powerups on purpose.


Available console commands:

addbot <name> <skill> - add a bot.
observer <0/1> - turn on/off observer mode, in which bots won't shoot at
                 human players.
botskill <1/2/3/4/5> - change default bot skill.
botdontshoot <0/1> - when this is turned on, bots won't shoot at anyone.
bot_chat_percent <value> - change the percent of bots chatting when they
                 get killed.


Running the bot on Dedicated servers:

When running a dedicated server the bot commands that are normally
available from the client console screen are disabled.  To create a bot you
must use the server command "bot" with parameter "addbot" (you can also
provide additional parameters like as shown in the bot.cfg file).  To use
the "bot" server command you would use one of the following commands on the
dedicated server command line...

bot addbot
bot addbot Da_Killer
bot addbot Da_Killer 4

You can use the "kick" command to remove a bot.  When using the dedicated
server, bot will also be automatically spawned using the bot.cfg file.

