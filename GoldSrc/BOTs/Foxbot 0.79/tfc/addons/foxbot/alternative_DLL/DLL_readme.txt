Some people have had problems running the newer Foxbot Windows releases.
I'm not sure what the cause is as I've yet to experience the problem.
As a backup plan I've made two versions of the Foxbot DLL.
If the normal one provided doesn't work for you, then please try the one
in this directory.
You can either rename it to FoXBot.dll and copy it over, or change the line in
/tfc/addons/metamod/plugins.ini
from:
win32 ../tfc/addons/foxbot/FoXBot.dll
to:
win32 ../tfc/addons/foxbot/alternative_DLL/FoXBot_alt.dll

Sorry about any problems encountered.
Zybby.