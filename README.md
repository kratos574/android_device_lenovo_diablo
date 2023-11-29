# android_device_lenovo_diablo
TWRP Device tree for Lenovo Legion Y90 - requires sm84xx-common repo


Blocking Checks

[✓] Correct screen/recovery size

[✓] Working Touch, screen

[✓] Backup to internal/microSD

[✓] Restore from internal/microSD

[✓] reboot to system (Only works using terminal)

[✓] ADB

Medium checks

[✓] update.zip sideload
 UI colors (red/blue inversions)
[✓] Screen goes off and on
 F2FS/EXT4 Support, exFAT/NTFS where supported
[✓] all important partitions listed in mount/backup lists
[ ] backup/restore to/from external (USB-OTG) storage (not supported by the device)
[✓] backup/restore to/from adb
[✓] decrypt /data
 Correct date (Have to set manually everytime booted)
Minor checks

[✓] MTP export
[✓] reboot to bootloader (Only works using terminal)
[✓] reboot to recovery (Only works using terminal)
[✓] poweroff (Only works using terminal)
[✓] battery level
[✓] temperature
[✓] encrypted backups
 input devices via USB (USB-OTG) - keyboard, mouse and disks (not supported by the device)
[ ] USB mass storage export
[✓] set brightness
[✓] vibrate
[✓] screenshot
[✓] partition SD card
