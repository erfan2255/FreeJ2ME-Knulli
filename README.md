# FreeJ2ME on Knulli
FreeJ2ME is a free and open source J2ME emulator with a focus on Java games. It is ready to run on Knulli H700 RG35xx family using Libretro and RetroArch

Play java games on rg35xx h700 device

It was tested exclusively on the RG35XX Plus & H

Note: Knulli OS is required to be installed
<!-- INSTALLATION -->
## Installation

1- Download knulli_patch_20240721.tar.gz.sh and throw it in roms/ports and start from there directly (it works on both ext4 & exfat)

2- Dont Panic! be patient and wait for process to be finished successfully

3- System reboots and then you can grab your game.jar into j2me folder that has created in `/roms/j2me`

4- I highly suggest to go for 320x240 resolution for full screen experience in games

5- Default resolution of j2me core is `240x320` so to change res, after first run of java game, j2me config will be created in:
  ```sh
/userdata/system/configs/retroarch/retroarchcustom.cfg
  ```
 then look for freej2me script and change res to `320x240` also if you had frame issue in games limit fps to 30 or 15. (I used odcommander to edit lines)
 
<b> Enjoy! </b>

patch from [4pda](https://4pda.to/forum/index.php?showtopic=1079913&st=9580#entry131374113)

Follow [CoreLand](https://youtube.com/@coreland2) on Youtube
<!-- SCREENSHOTS -->
## Screenshots
| ![system menu](https://raw.githubusercontent.com/erfan2255/FreeJ2ME-Knulli/main/screenshots/menu.png) | ![plants vs zombie](https://raw.githubusercontent.com/erfan2255/FreeJ2ME-Knulli/main/screenshots/pvz.png) |
| -- | -- |
| ![gangstar rio](https://raw.githubusercontent.com/erfan2255/FreeJ2ME-Knulli/main/screenshots/gngr.png) | ![prince of persia classic](https://raw.githubusercontent.com/erfan2255/FreeJ2ME-Knulli/main/screenshots/pop.png) |
