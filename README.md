Recovery Device Tree for Samsung Galaxy A15 4G (A15)
The Galaxy A15 4G is a budget range smartphone from Samsung, Released 2023, December 11. This project is licensed under the terms of the GNU GPLv3

## Device spefication (briefly)
|Basic               |Spec Sheet                                                    |
|--                  |--                                                            |
|CPU                 |Octa-core (2x2.2 GHz Cortex-A76 & 6x2.0 GHz Cortex-A55)       |
|Chipset             |MediaTek Helio G99 (MT6789)                                   |
|GPU                 |Mali-G57 MC2                                                  |
|Codename            |A15                                                           |
|Memory              |4/6/8GB RAM                                                     |
|Android Version     |14/15                                                            |
|Storage             |128/256GB                                                     |

## Situation
- [X] Backup to internal
- [X] Restore from internal
- [X] /data encryption (multidisabler)

Medium checks
- [X] update.zip sideload
- [X] UI colors (red/blue inversions)
- [X] Screen goes off and on
- [X] F2FS/EXT4 Support, exFAT/NTFS where supported
- [X] all important partitions listed in mount/backup lists
- [X] backup/restore to/from external (USB-OTG) storage
- [X] backup/restore to/from adb (https://gerrit.omnirom.org/#/c/15943/)
- [ ] decrypt /data (multidisabler)
- [X] Correct date

Minor checks
- [X] MTP export
- [ ] reboot to bootloader
- [X] reboot to recovery
- [X] poweroff
- [ ] battery level
- [X] temperature
- [X] encrypted backups
- [X] input devices via USB (USB-OTG) - keyboard, mouse and disks
- [X] USB mass storage export
- [X] set brightness
- [X] vibrate
- [X] screenshot
- [ ] partition SD card

### Device picture
![Samsung Galaxy A15 4G](https://fdn2.gsmarena.com/vv/bigpic/samsung-galaxy-a15-lte-.jpg)
