Marlin Ender-3 Firmware 1.1.9 (ABL Support)
=========================

This is a modified release of the latest Marlin Firmware version 1.1.9, using the stock Ender-3 configurations and added support for Auto Bed Leveling. Due to flash memory constraints on Melzi boards, several lesser used options have been disabled to create space for the ABL features.

ABL Sensor settings have been configured in accordance with the information found via the <a href="https://letsprint3d.net/2018/07/31/guide-how-to-setup-auto-bed-leveling-ender-3">Guide: How to Setup Auto Bed Leveling (Ender-3)</a>. If using another probe, mounting plate or any other changes are present, please make sure to adjust the values listed under <i>ABL Probe Configurations</i> as needed.

<i>Thermal Runaway Protection and Cold Extrusion Prevention are ENABLED. These are safety standards and default in the Marlin Firmware.</i>

Feature Changes
=========================

enabled AUTO_BED_LEVELING_BILINEAR</br>
enabled FIX_MOUNTED_PROBE</br>
enabled Z_SAFE_HOMING</br>

<h3>Memory Saving Options</h3>
enabled DISABLE_M503</br>
disabled SPEAKER</br>
disabled ARC_SUPPORT</br>
disabled EEPROM_CHITCHAT</br></br>

<b>Flash Memory Usage:</b> 98% (127 Kb)</br>
<b>Variable Memory Usage:</b> 29% (4.79 Kb)</br>

ABL Probe Configurations
=========================

X_PROBE_OFFSET_FROM_EXTRUDER -40</br>
Y_PROBE_OFFSET_FROM_EXTRUDER -10</br>
Z_PROBE_OFFSET_FROM_EXTRUDER 2</br>

LEFT_PROBE_BED_POSITION 10</br>
RIGHT_PROBE_BED_POSITION 170</br>
FRONT_PROBE_BED_POSITION 30</br>
BACK_PROBE_BED_POSITION 190</br>

Z_MIN_ENDSTOP_INVERTING true</br>
Z_MIN_PROBE_ENDSTOP_INVERTING true</br>