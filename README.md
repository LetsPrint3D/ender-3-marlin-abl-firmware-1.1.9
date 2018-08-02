Marlin Ender-3 Firmware 1.1.9 (ABL Support)

This is a modified release of the latest Marlin Firmware version 1.1.9, using the stock Ender-3 configurations and added support for Auto Bed Leveling. Due to flash memory constraints on Melzi boards, several lesser used options have been disabled to create space for the ABL features.

ABL Sensor settings have been configured in accordance with the information found via the <a href="https://letsprint3d.net/2018/07/31/guide-how-to-setup-auto-bed-leveling-ender-3">Guide: How to Setup Auto Bed Leveling (Ender-3)</a>. If using another probe, mounting plate or any other changes are present, please make sure to adjust the values as needed.

Feature Changes
=========================

enabled AUTO_BED_LEVELING_BILINEAR

enabled FIX_MOUNTED_PROBE

enabled Z_SAFE_HOMING


disabled SPEAKER

disabled ARC_SUPPORT

disabled EEPROM_CHITCHAT