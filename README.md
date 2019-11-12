# MPCNC-TFT35-V2.0
Custom firmware for the BigTreeTech TFT35 V2.0 for use with the MPCNC

See the BigTreeTech <a href="https://github.com/bigtreetech/BIGTREETECH-TouchScreenFirmware">directions</a> for how to modify and install.

Features:
* CNC focused screen options
* Laser settings use the fan outputs to control the laser
* Designed to guide you through the process including homing if your CNC has end stops
* Move to move the tool to the starting location
* Job Setup to zero the axes as required
* Cut to run the CNC operation including babystepping for Z while it is running

Basic install directions:
1. Download the repo
2. If not editing, copy all the files from the "Copy to SD Card root directory to update" an SD card
3. Put the SD card in the TFT35 V2.0
4. Reset the TFT. You should see one update for the firmware; then another for the fonts and icons.

Use this firmware in conjunction with the MPCNC SKR 1.3 <a href="https://github.com/BlomsD/MPCNC-SKR1.3-TMC2208UART">firmware posted here</a>.

Troubleshooting:
* If it isn't updating your firmware there is a decent chance your bootloader if wrong (mine was). You'll need the <a href="https://github.com/bigtreetech/BIGTREETECH-TouchScreenFirmware/tree/master/TFT35_V2%20Bootloader%20fix">bootloader</a> and slink utility. See this <a href="https://github.com/bigtreetech/BIGTREETECH-TouchScreenFirmware/issues/24#issuecomment-550535410">post for more information</a>.

Changelog:
* 12NOV2019 - V1.0 - Initial commit.

Example:
<img src="https://imghst.gpsfiledepot.com/1573595052.jpg" width="400">

Resources:
Thanks to <a href="https://www.youtube.com/channel/UCbgBDBrwsikmtoLqtpc59Bw">TeachingTech on YouTube</a> for the idea with his LowRider2 TFT firmware.
