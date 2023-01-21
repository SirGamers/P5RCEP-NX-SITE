# Dumping the Game

### Transferring Files

{% hint style="info" %}
Removing the SD card will require you to reboot the Switch, and therefore repeat the steps to enter RCM mode and send the payload over USB. To avoid doing that, keep your Switch in sleep mode rather than powering it off. If you want to change the files on your SD card, you can do it wirelessly via FTP homebrew.
{% endhint %}

To set up FTP...

1. Download [`ftpd.nro`](https://github.com/mtheall/ftpd/releases/download/v3.1.0/ftpd.nro) and place it in the /switch/ folder of your SD card.
2. On PC, install a [program such as Filezilla](https://filezilla-project.org/download.php?type=client).&#x20;
3. Connect your Switch to the same network as your PC.&#x20;
4. Launch the FTP-D homebrew via the Album icon on the home menu.
5. Simply enter the IP and port shown onscreen in your client and connect to begin transferring files.

### Dumping Files

In order to create your own mods, or merge existing mods using a Mod Manager, you'll want a copy of the game's files. The files are about 15 GB in total, so make sure you have enough space free on your SD card.

1. Download [`nxdumptool.nro`](https://github.com/DarkMatterCore/nxdumptool/releases/download/v1.1.15/nxdumptool.nro) and place it in the `/switch/` folder of your SD card.
2. Launch the NXDumpTool homebrew via the Album icon on the home menu.
3. Select P5R and dump RomFS content to SD card. This can take quite some time.
4. Once the files are dumped, copy them to PC.
5. If the `ALL_USEU.CPK` file was split up due to the SD Card being formatted as FAT32...
   1. Download and run [HxD](https://mh-nexus.de/en/downloads.php?product=HxD20).
   2. Go to `Tools` > `File Tools` > `Concatenate`
   3. Select each of the files in the `ALL_USEU.CPK` folder and make sure they're listed in order
   4. Save the `ALL_USEU.CPK` file somewhere on your PC.
6. Put these files in a folder, we will use this later.
