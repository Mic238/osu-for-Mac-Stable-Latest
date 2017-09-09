# osu! for Mac Stable (Latest)

### Step to Install:
1. Download zip from this page (188.6M), it should be sitting in Download folder, move the game to /Application if you're newly install. DON'T MOVE/REPLACE THE GAME TO /Application IMMEDIATELY IF YOU'RE UPDATING FROM OLD CLIENT!!
2. Open the app for the first time.
   If prompted the app is from unidentify developer, go to System Pref - Security - click Open Anyway and try again. 
   If prompted Gecko package is not installed, click cancel.
   osu! will take a while to download and install itself. The game will start automatically when it finishes.

---------------------------
### Next For New players:
1. Go to setting - full screen mode - turn it off.
2. Login, change the settings, download beatmaps, Enjoy!
3. Move the game to /Application folder if you haven't done so.
4. Beatmaps folder locates at right click osu!.app - show package content - drive_c - Program Files - osu! - Songs

----------------------------
### Next For Update players:
1. Exit the game right after it loads, don't login or touch any settings
2. For both old client (at /Application/osu!) and new client (at ~/Downloads/osu!), right click - show package content - drive_c - Program Files - osu!
3. Hold command key and select all the following folders/files in the old client, then drag them to the new client while holding option key. Check apply to all and click replace when prompt. Be very careful of the direction of movement is from old to new (there is no undo if you get the direction wrong, everything will be lost) and it's copying the actual file (indicate by a green plus sign). If a symlink is created accidently (a small arrow at the corner), simply redo this step.
	1. Folders: Data, Songs, Skins
	2. Files: collection.db, presence.db, scores.db, osu!.db, osu!.cfg, osu!.YourUsername.cfg
4. Go to setting - full screen mode - turn it off if it's on (solid circle).
5. Play a few games, if there are no major bugs and you're happy with it, you can move the game to /Application and replace the old client from now. If you want to stick with the old one, trush the new client if you like.

---------------------------
### Testing Environment:
Mac Mini (Late 2014) 2.6GHz, 8G Memory, 256G SSD, MacOS High Sierra Public Beta 8, Wrapper Wineskin-2.6.2, Engine WS9Wine2.12

---------------------------
### A Little Bouns for all:
To move the beatmaps faster, open terminal and type this command follow by return:
* echo "alias osu='mv ~/Downloads/*.osz /Applications/osu\!.app/drive_c/Program\ Files/osu\!/songs'" >> .bash_profile

Restart terminal and from now on, you can simply type "osu" in the terminal to move all newly download beatmaps from download folder to game beatmap folder, don't forget to fn+f5 to refresh the game list
