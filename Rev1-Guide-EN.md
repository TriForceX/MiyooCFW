# New Bittboy Rev 1 Custom Firmware

Before working with us, we would like to express our gratitude to **Steward-fu** and the people mentioned on main page special thanks [here](https://github.com/TriForceX/NewBittboyCFW#special-thanks).

**The photographs in the section were made using Steward-fu's photographic materials.**

https://steward-fu.github.io/website/handheld.htm

**You can click the next video to see the basics of the console modifications.**

[![click here](https://i.imgur.com/I3S12VG.png)](https://youtu.be/FjQquL3W99U)

## 1) Materials
1. New Bittboy - rev1 (early version)
2. SD card of 8GB or more
3. Knapping supplies (ironing, silverware)
4. Jumper cable (thin cable recommended)
5. Debian or Ubuntu environment computer

## 2) Work Order
1. Hardware mode (hwmod)
2. Building SPI flashing environment
3. SPI flashing
3. Burn image to SD card

## 3.1) Hardware Mod (hwmod)
1. Unscrew the 6 screws to release the case.\
![image 1](https://i.imgur.com/LHmhgJN.png)
2. Check the display area. If the LCD connector is not on the display, it is Rev2.\
![image 2](https://i.imgur.com/KuanR5A.png)
3. Remove resistors R75, R76, R78.
4. DM, DP solder joint (lead to ground).\
![image 3](https://i.imgur.com/B2DWSGW.png)
   - before work\
![image 4](https://i.imgur.com/lieDKbu.png)
   - After work
5. Ground the jumper wire on the 2nd pin of the SPI IC chip.\
![image 5](https://i.imgur.com/F0CPt0b.png)

## 3.2) Building SPI Flashing Environment
1. Install Debian or Ubuntu on your PC.
2. Run the terminal using an account with root privileges.
3. Enter in the following order:
   ```
   sudo apt-get install git-core
   ```
4. When the installation is complete, type in the following order:
   ```
   git clone https://github.com/steward-fu/f1c100s_sunxi-tools
   cd f1c100s_sunxi-tools
   make clean && make
   ```
   **Note:** If says you have invalid permissions use `sudo make install`

## 3.3) SPI Flashing
1. Connect New BittBoy to PC with USB.
2. Turn on the power while holding the jumper wire as shown in the picture.
3. Download the latest spi image from Steward-fu's github. https://github.com/steward-fu/miyoo_rel
   ```
   SPI Image File Name Example > miyoo_spi_hwmod_1bit_ghostkey_20190216.bin
   ```
4. Move downloaded SPI image to home.
5. Run the terminal.
6. Type the following:
   ```
   sudo sunxi-fel -p spiflash-write 0 SPI image .bin
   ex> sudo ./sunxi-fel -p spiflash-write 0 miyoo_spi_hwmod_1bit_ghostkey_20190216.bin
   ```
7. Wait until 100% is completed.
8. Disconnect the New BittBoy from the PC and turn off the power.
9. Assemble the New Bittboy main body and turn on the power.
10. If the following screen is displayed, it is success.\
![image 6](https://i.imgur.com/JxTEsDV.png)

# 3.4) Burning an Image to an SD Card
1. Download the latest MiOS image from Steward-fu's github. https://github.com/steward-fu/miyoo_rel
   ```
   MiOS image file name example > MiOS_v1.0_20190203.zip, MiOS_v1.0_20190203.z01, MiOS_v1.0_20190203.z02 ...
   ```
   **Note:** You can get an alternative more updated image/kernel from Christian Haitian repository [here](https://github.com/christianhaitian/BittBoyV1).
2. Remove all partitions of SD card and format it with FAT32 etc. (I used Windows Disk Management)
3. Download `win32diskimager` and install it.
   https://sourceforge.net/projects/win32diskimager/
4. Execute `win32diskimager`, select SD driver, load MiOS image and press **"Write"** button to proceed.\
![image 7](https://i.imgur.com/ut0wzto.png)
5. Once the image is burned, insert SD into New Bittboy and turn it on. If it boots like below, it is a success.\
![image 8](https://i.imgur.com/l0ZXpH7.png)

**Enjoy!** :grin:
