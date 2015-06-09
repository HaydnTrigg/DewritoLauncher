Dewrito Launcher Changelog
=====================

0.4.6:
-  Added in new options in settings menu
-  Added Browser support (Awesomium)
-  Added animations for verifying files and Errors
-  Application is now borderless (no windows titlebar)
-  Custom messageboxes, progress bar, and minimize/close items added
-  Launcher will give option to restart application automatcally after update
-  Added new scrollbar for changelog
-  Tons of new settings
-  Player Customization tab for pimping your spartan
	
0.4.5:
-  The "Primary Weapon" and "Secondary Weapon" gametype options are no longer
  overridden by the Battle Rifle
-  Most weapons (including colored ones) have been added to the gametype options
-  Fixed the "Weapons on Map" gametype option
-  Fixed some issues people were having with the launcher

0.4.4:
-  Added new Launcher
-  Added launcher check (game has to be started through launcher now)
-  Cleaned up main menu
-  Implemented showing ElDewrito version on main menu
-  Fixed bug with debug logging causing crashes
-  Added playername limit of 15 characters
-  Removed hash check on preferences.dat to prevent file corruption
-  You can now spawn any AI through effects, instead of just creatures (thx Lord
  Zedd!) (however there are still problems to be fixed..)

0.4.3:
-  Removed respawn menu, fixes the respawn glitch but there's currently
  no respawn timer showing (still counts down though, timer will be shown again in
  later version)
-  No longer locks game input when game ends, you can still move around until the
  podium screen is shown
-  Game will now only connect/allow connections from people with the same
  ElDewrito version
-  show_ui command should be fixed
-  Version stuff fixed, shows the ElDewrito version in the console and watermark
  now

0.4.2:
-  Disables autoaim/aimassist for mouse users, controller still has it enabled
-  Displays scores correctly on podium screen

0.4.1:
-  Temporary fix for the ElDewrito console thread hogging CPU, now locked to
  running at 60 updates per second
-  Some improvements to the scoreboard hooks

0.4.0 (Initial Release):
-  Patch Game_GetPlayerName function to use name from our DLL
-  Set username to a random username
-  "name" command to set their username, saves/loads it from playername.txt
-  Patch to allow pressing X to show game options inside lobby
-  Hook Forge button handler code to fix switching menus with keyboard
-  Hook scoreboard/podium to show player names
-  Various weapons rebalanced to mirror the Halo 3 values
  -  Sniper and beam rifle damage changed from 130 to 80
  -  Brute Chopper and Gauss cannon projectile damage fixed
-  Some other VFSL changes?

pre- 0.4.0:
-  Hook to load H3UI on game start (based on same code/method Halo 3 loads it)
-  Hook XNet functions to fix system link, by using system link data to match IPs to
  XNet addresses
-  Hook MatchmakingLeaveQueue SSL function to show the H3 pause menu
-  Added Johnson to the main menu
-  Fixed bug with Forge editor rotation using controller