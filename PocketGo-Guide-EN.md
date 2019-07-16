# Pocket Go v1 Custom Firmware

Before working with this, we would like to express our gratitude to **Steward-fu** and the people mentioned on main page special thanks [here](https://github.com/TriForceX/NewBittboyCFW#special-thanks).

**This is still a beta and is still in development.**

## 1) Materials
1. Pocket Go v1
2. SD card of 8GB or more
3. Lastest CFW v3.9 Image [(Download)](https://www.dropbox.com/s/m2j56qx2utt9d6z/PocketGo_V1_CFW_v3.9_10-06-2019.img.7z?dl=0)
4. Install Partition Wizard [(Download)](https://www.partitionwizard.com/download.html)
5. Install win32diskimager [(Download)](https://sourceforge.net/projects/win32diskimager)
6. Install 7zip [(Download)](https://www.7-zip.org/download.html)
7. Optional Install SD Card Formatter [(Download)](https://www.sdcard.org/downloads/formatter)

## 2) Setup
![pocketgo-guide](https://user-images.githubusercontent.com/16083854/59299539-e0ebb600-8c5a-11e9-91bb-f9386ec71d1c.png)

1. If you are using the included SD you need to remove all partitions using _Partition Wizard_, _SD Card Formatter_ or _Windows Disk Management_.
   **Note:** SD Card need to be in _FAT 32_ format.
2. If the CFW file is compressed on **.7zip** just extract using _7zip_ before proceed.
3. Execute _win32diskimager_, select SD card, load the **.IMG** file and press **Write** button to proceed.
4. Once the image is burned on the SD card, open Partition Wizard and choose Disk Management.
5. Then right click on the _main_ partition and choose extend (Set it to the maximum) and apply.
6. Insert the SD into New Bittboy and turn it on. If it boots it is a success.

**Note:** If you have problems to access the "main" partition on Windows 7 or 8 please read [here](https://user-images.githubusercontent.com/16083854/61264146-7d710e80-a759-11e9-99e4-de446c032818.jpg)

**Enjoy!** :grin:
