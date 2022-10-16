# SwitchRoot-Q-Overclock
**WARNING!**<br />
**OVERCLOCKING TO 2.09ghz ACCELERATES BATTERY DEGRADATION GREATLY**<br />
**LIKE OTHER OC SCENARIOS, THIS WILL DEGRADE YOUR CPU FASTER**

## Introduction
**This repository contains TWRP flashable zips for Overclocking your CPU & RAM to clocks higher than SwitchRoots Performance Mode**<br />
**I will also include uninstaller flashable zips so you can go back to stock clock speeds if you have issues**<br />
**These kernels are built using the official [LineageOS](https://github.com/LineageOS/android) and [Switchroot](https://gitlab.com/switchroot/android) sources**

## Flashable Zips
**This is just an explanation on what each zip has/does**<br />
**(As of this commit, the zips have been updated for the April 8th 2022 SwitchRoot Release)**<br />

* 2091 OC.zip
    * This will flash an overclocked boot.img and edited power profile to enable a 2.091ghz overclock

* OC Uninstaller.zip
    * This will uninstall the overclocked boot.img, coreboot.rom, and power profiles

* Switchroot-Bootanimation.zip
    * This is a custom Switch boot animation made by MakinBacon!
    
The OC zip will overclock in both handheld and dock.

## CPU OC Installation
1. Flash the OC zip of your choice in TWRP (HOLD VOL+ while booting android)
2. Boot switchroot, enable Performance Mode & enjoy your overclock!
(Settings > System > Advanced > Display and Performance Configuration > Performance Mode)
3. If you previously had [**Magisk**](https://github.com/topjohnwu/Magisk/releases) installed, for now you will have to reflash it after flashing this zip in TWRP!

If you haven't already flashed [**Magisk**](https://github.com/topjohnwu/Magisk/releases) & want root, you can flash magisk after this OC zip

## RAM OC Installation (coreboot.rom)
1. Download the provided coreboot.rom
2. Copy it to your switchroot/android folder and confirm replace/overwrite
3. Boot Switchroot! Now you have overclocked RAM

## Custom Boot Animation (Not overclock related but its cool!)
1. Flash the Switchroot-Bootanimation.zip in TWRP (HOLD VOL+ while booting android)
2. Boot Switchroot! Now you have the custom boot animation made by MakinBacon!

[Here](https://cdn.discordapp.com/attachments/769349427948158976/975901552726405130/20220501_204904.mp4) is a rough video of what it looks like!
