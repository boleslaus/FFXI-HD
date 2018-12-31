Mega Update Bundle - By Amelila (nebula0024)
UPDATED: November 9, 2018

[If viewing this document with Notepad, ensure Word Wrap is enabled]

This DAT bundle can be used as a stand-alone installer or an update package for existing mods.
**Best viewed with FFXI Custom ReShade Preset. Instructions further below**

******************
IMPORTANT
******************

The DAT files found within the ROM, ROM2 and ROM3 folders can be copied directly to your
FFXI installation directory, or used with the Ashita3 DAT Loader.

The DAT files found within the Mog Houses, Ru'Aun Gardens and San d'Oria Shops folders
MUST BE COPIED TO YOUR FFXI INSTALLATION DIRECTORY. Do not used the Ashita3 DAT Loader
with these files or they may not load correctly. This is because the game dynamically loads
these files on demand, so the DAT Loader may not catch them in time.


The Valkurm Dunes gets very bright and I have no way to control this. The way I have
retextured this zone gives it far more detail in the morning, late afternoon/evening and night.
Regardless of my work, things are going to get blown-out with-or-without the Shaders plugin
enabled. If the Shaders plugin is too bright, simply press SHIFT+F2 to bring up the configuration
menu to adjust the Bloom/HDR settings. You can also create a new Preset for the Dunes, or
simply bind SHIFT+F12 to disable/enable the plugin altogether (I find that one particularily useful).

Also, many of the stock UV maps in the Valkurm Dunes were designed to join up together with
low-resolution textures that have completely white sand between them. Thus, certain
high-resolutiontextures may have a slight mismatch between them. I have done my best to 
account for this, and I'm sure it will improve over time.


======================
Installation
======================
[Optional] If you are running Ashita3 with the drawdistance plugin, type /drawdistance setworld 20 when logged in
[Optional] This HQ texture pack is best viewed with my ReShade preset. See the optional instructions towards the
           bottom to learn how to configure ReShade for FFXI.

Method #1:
----------
1) Navigate to your FFXI directory. This is typically \Program Files (x86)\PlayOnline\SquareEnix\FINAL FANTASY XI\
2) [OPTIONAL BUT RECOMMENDED]Make a backup copy for each of the DAT files found within this pack somewhere *outside* your FFXI Installation directory.
3) Copy-and-Paste the three ROM folders (ROM, ROM2, ROM3) as well as the DAT files found within the other
   folders (Mog Houses, Ru'Aun Gardens, etc...) directly into your FFXI install directory.
   When prompted, overwrite the existing files.
4) Enjoy!


Method #2:
----------
This method requires Ashita3 and does not require you to replace the original DAT files in your install directory.
Download it here: http://ashita.atom0s.com/

1) Configure Ashita3 to run with FFXI. There are instructions on the site above.
2) With Ashita3 running, select Plugins on the left.
3) Install the Dats plugin, then close Ashita3
4) Navigate to your Ashita3 install directory, open the Scripts folder and then open Defaults.txt
5) Within the # Load Common Plugins section, be sure /load Dats is added to the list as the FIRST plugin to load!
6) Again, within your Ashita3 install directory, open the plugins folder
7) Create a new folder labeled dats
8) Copy-and-Paste the three ROM folders (ROM,ROM2,ROM3) inside the dats folder
9) Copy-and-Paste the DAT files found within the other folders (Mog Houses, Ru'Aun Gardens, etc...)
   directly into the appropriate folders within your FFXI installation directory (required).
10) Launch Ashita3 and enjoy!


======================
OPTIONAL: ReShade
======================

NOTE: I have only tested this for use with Ashita3 - http://ashita.atom0s.com
 - ReShade should run perfectly fine with Retail or Windower, but it is untested.
 - Retail users will likely need to follow the instructions below but instead point to POL.EXE found in \Program Files (x86)\PlayOnline\SquareEnix\PlayOnlineViewer
 - Windower users will likely need to follow the instructions below but instead point to windower.exe or the original POL.exe

-------------
Ashita3
-------------
1) Install and configure Ashita3
2) Run ReShade_Setup_3.1.0.exe found in this Mod Pack ---> If your Antivirus flags this file, IT IS SAFE TO RUN. Disable your Antivirus Shields, if necessary.
   You can also download and install ReShade directly from https://reshade.me if you prefer.
3) Point ReShade to POL.EXE found in \Ashita\ffxi-bootmod
4) Select Direct3D 9. If prompted to download default shaders, please do so!
5) When complete, you may close ReShade Setup.
6) Copy d3d8.dll and FFXI - ReShade Preset.ini to your \Ashita\ffxi-bootmod folder
7) Launch Ashita3 and play! When prompted to configure ReShade, be sure to select the FFXI - ReShade Preset.

**To configure ReShade from within FFXI, press SHIFT+F2 to open the configuration menu. I would also recommend binding something like SHIFT+F12
  from within the configuration tool to enable or disable the plugin**

NOTE: Sometimes opening and closing the ReShade menu from within FFXI can bork your controller. To fix this, simply click outside of the FFXI window or ALT-TAB
      to something else and then back to FFXI.
