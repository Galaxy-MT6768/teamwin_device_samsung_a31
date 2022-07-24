# Samsung Galaxy A31 [SM-A315G] - Team Win Recovery Project
[Telegram Support Group](https://t.me/a31nsxx)
```diff
- TWRP Status: Bugfixing, experimental, unstable. 
- Releases tagged as "Pre-release" are considered experimental and may cause more unexpected stuff than the latest release, nobody is forced to support your in older releases.
```

Run ``chmod +x device/samsung/a31/mkbootimg`` to avoid building issues.
### Special thanks to:
> [TeamWin](https://github.com/TeamWin) for the Recovery Project.
> 
> [Physwizz](https://github.com/physwizz) for his [a315g kernel](https://github.com/physwizz/a315g).
>
> [Zillion](https://github.com/DevZillion) for doing the device tree.

### How to install
> Flash the latest .tar release from [releases](https://github.com/Galaxy-MT6768/android_device_samsung_a31nsxx/releases), it may require Magisk patched vbmeta.img
> 
> Hold the recovery combination (Volume Up + Power) while the .tar is flashing via the odin tool.
> 
> When booted up into twrp got to ``Advanced > Terminal`` and type ``multidisabler --all``, if you want to keep your unlock pattern/pin type ``multidisabler --disable-stockrec-override`` instead.
> 
> After that go to ``Wipe > Format Data``, all your data will be lost.
> 
> You can now boot into your system and do whatever you want.
