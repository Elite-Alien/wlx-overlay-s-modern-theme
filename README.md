# Please Read
This is a wlx-overlay modification created by EliteAlien. This modification is free for anyone to use and modify. All I ask in return is, if you create anything, please share as I have shared to you. If you have any requests I can potentially add them within the limitations of this software. As wlx-overlay expands, adds new features, et cetera their could be many modifications to come.

## What you need installed to use all features
1) playerctl - Must be installed for media player buttons/controls to tap into mpris player functions & to collect the metadata information if using "player.yaml".
2) swayosd (optional) - This is currently not fully working. Though the mute options and toggles can be used. You just can't use the over 100%. wlx-overlay will not register the "--max-volume 153"
3) PulseAudio or Pipewire-Pulse. This is used to control the audio alternatively from the swayosd.

## How to install
1) Navigate to ~/.config/wlxoverlay
2) Download watch.yaml, player.yaml (optional read below), & mixers.yaml (optional read below).
3) Place those files into the folder in step 1.
4) Reload wlx-overlay and/or Steamvr or Monado.
5) Enjoy.

## Optional Yaml Requirements
1) If you do not wish to use mixers.yaml it can be removed, but you will need to modify the button with headphones on it. Either change it to something else or remove it completely.
2) If you wish to keep mixers.yaml, you may want to modify the mixers included in the mixers.yaml file. The buttons have, "pavucontrol", "mate-volume-control", "carla", "helvum", & "qpwgraph" out of the box.
3) If you do not wish to use player.yaml it can be removed, but you will need to modify the stop button and music-note button. Either change the music-note button to something else of remove it. As for the stop button, it has a command to close the player.yaml window that should be removed if not used.
4) When using the mixers.yaml. Aim at one of your desktops with one controller and press the buttons with the other, if your windows are setup to open where the mouse is located. Otherwise it should open where you have defined the Windows logic.

I created this out of pure desire to have a much clearner experience then what you get out of the box. I hope you enjoy this modification and please do share any modifications you have done, for all of us to enjoy.
