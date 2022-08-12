# Samsung Galaxy A31 [SM-A315G/F] [a31nsxx & a31xx] - Team Win Recovery Project
[Telegram Support Group](https://t.me/a31nsxx)
```diff
- TWRP Status: Bugfixing, experimental, unstable. 
- Releases tagged as "Pre-release" are considered experimental and may cause more unexpected stuff than the latest release, nobody is forced to support your in older releases.
```
Set the ``TW_CUSTOM_THEME``flag for a custom theme.

Build with twrp-11 to avoid the recovery.img being bigger than the partition.

Run ``chmod +x device/samsung/a31/mkbootimg`` to avoid building issues.
### Special thanks to:
> [TeamWin](https://github.com/TeamWin) for the Recovery Project.
> 
> [Physwizz](https://github.com/physwizz) for his [a315g-S kernel](https://github.com/physwizz/a315g-S) (ligther version was used on this tree).
>
> [Zillion](https://github.com/DevZillion) for doing the device tree.

### How to install
> Flash the latest .tar release from [releases](https://github.com/Galaxy-MT6768/android_device_samsung_a31nsxx/releases), it may require Magisk patched vbmeta.img
> 
> Hold the recovery combination (Volume Up + Power) while the .tar is flashing via the odin tool.
> 
> Flash any multidisabler that has been tested on a31. 
> 
> You can now boot into your system and do whatever you want.

### Working Features List
>
> - [x] Critial Partitions fail to unlock
>
> **Blocking checks**
> - [x] Correct screen/recovery size
> - [x] Working Touch, screen
> - [x] Backup to internal/microSD
> - [x] Restore from internal/microSD
> - [x] reboot to system
> - [x] ADB
>
> **Medium checks**
> - [ ] update.zip sideload
> - [x] UI colors (red/blue inversions)
> - [x] Screen goes off and on
> - [x] F2FS/EXT4 Support, exFAT/NTFS where supported
> - [x] all important partitions listed in mount/backup lists
> - [x] backup/restore to/from external (USB-OTG) storage
> - [x] backup/restore to/from adb (https://gerrit.omnirom.org/#/c/15943/)
> - [ ] decrypt /data
> - [x] Correct date
>
> **Minor checks**
> - [ ] MTP export
> - [x] reboot to bootloader (download)
> - [x] reboot to recovery
> - [x] poweroff
> - [x] battery level
> - [x] temperature
> - [ ] encrypted backups
> - [x] input devices via USB (USB-OTG) - keyboard, mouse and disks
> - [ ] USB mass storage export
> - [x] set brightness
> - [x] vibrate
> - [x] screenshot
> - [ ] partition SD card
