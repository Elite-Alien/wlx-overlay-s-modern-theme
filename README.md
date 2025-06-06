# Please Read
This is a wlx-overlay modification created by EliteAlien. This modification is free for anyone to use and modify. All I ask in return is, if you create anything, please share as I have shared to you. If you have any requests I can potentially add them within the limitations of this software. As wlx-overlay expands, adds new features, et cetera their could be many modifications to come.

![image](https://github.com/user-attachments/assets/9121c6ad-c3e1-45d8-aedf-025bd3477f0e)

## What you need installed to use all features
1) playerctl - Must be installed for media player buttons/controls to tap into mpris player functions & to collect the metadata information if using "player.yaml".
2) swayosd (optional) - You will need to uncomment the "swayosd" commands under watch.yaml & add the comment to the pactl the same way as swayosd was.
3) PulseAudio or Pipewire-Pulse. This is used to control the audio alternatively from the swayosd.
4) WayVR (optional) - You will need to install WayVR from your packagemanager or build it. Then add the "wayvr.yaml" to your wlxoverlay config folder in order to use WayVR's Dashboard.

## How to install
1) Navigate to ~/.config/wlxoverlay
2) Download watch.yaml, player.yaml (optional read below), & mixers.yaml (optional read below).
3) Place those files into the folder in step 1.
4) Reload wlx-overlay and/or Steamvr or Monado.
5) Enjoy.

## Optional Yaml Requirements & Modifications
1) If you do not wish to use mixers.yaml it can be removed, but you will need to modify the button with headphones on it. Either change it to something else or remove it completely.
2) If you wish to keep mixers.yaml, you may want to modify the mixers included in the mixers.yaml file. The buttons have, "pavucontrol", "mate-volume-control", "carla", "helvum", & "qpwgraph" out of the box.
3) If you do not wish to use player.yaml it can be removed, but you will need to modify the stop button and music-note button. Either change the music-note button to something else of remove it. As for the stop button, it has a command to close the player.yaml window that should be removed if not used.
4) When using the mixers.yaml. Aim at one of your desktops with one controller and press the buttons with the other, if your windows are setup to open where the mouse is located. Otherwise it should open where you have defined the Windows logic.
5) WayVR Dashboard can be used or removed. If you do not have WayVR installed or just do not wish you use it, remove the three entries for it in the watch.yaml. You can search the comments, "# Dashboard toggle button", "# bottom row, of keyboard + overlays". You will find WayVR, WayVRLauncher, & WayVRDisplayList under these comments. Remove or comment all three out.
6) 12-Hour clock is used by default. You can change this if you wish. Find the comment "#----- Clocks -------" and each clock has a commented out "format". Remove the "#" and add one to the other "format". Then you will be using a 24 hour clock.

I created this out of pure desire to have a much clearner experience then what you get out of the box. I hope you enjoy this modification and please do share any modifications you have done, for all of us to enjoy.
