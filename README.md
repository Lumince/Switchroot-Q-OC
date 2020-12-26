# SwitchRoot-Magisk-Q

## Introduction

**This repository contains magisk patched boot.img's for the switchroot-Q project along with their respective tegra210-icosa.dtb's**<br />

## Installation

> If you wish to patch your own boot.img, follow `Patch Boot.img`<br />
If you wish to use the files that I have provided here to boot Magisk on your switchroot-Q installation, follow `Flash Images`<br />

> **Patch Boot.img**<br /> You will need your own boot.img. You can either get this from your lineage.zip or from `out/target/product/rom/boot.img`<br />
1. Boot Android & install the latest Magisk Manager APK [Latest Here](https://github.com/topjohnwu/Magisk/releases)
2. Plug your switch in and move your boot.img to your downloads folder
3. Open Magisk Manager > Settings Icon > Update Channel > Beta
4. Press Install next to Magisk > Enable RecoveryMode in options > Select and Patch a File > Select your boot.img
5. Boot TWRP & flash the `magisk_patched.img` to your boot partition 

> **Flash Images**
1. Place `boot_nOC_patched.img &  tegra210-icosa-nOC.dtb` or `boot_OC_patched.img &  tegra210-icosa-OC.dtb` in switchroot/install on your switchroot partitioned sd card.<br />
2. Rename the boot image to `boot.img` & the DTB to `tegra210-icosa.dtb`
3. Boot Hekate
4. Navigate to Partition SD card and press `Flash Android`
5. Boot switchroot and enjoy root access!
