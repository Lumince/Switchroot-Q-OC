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
* OC Uninstaller.zip
    * This will flash a non-overclocked boot.img, coreboot.rom, and power profile
	
* 1887 OC.zip
    * This will flash an overclocked boot.img and edited power profile to enable a 1.887ghz overclock
	
* 1989 OC.zip
    * This will flash an overclocked boot.img and edited power profile to enable a 1.989ghz overclock

* 2091 OC.zip
    * This will flash an overclocked boot.img and edited power profile to enable a 2.091ghz overclock

These zips will overclock in both handheld and dock.

## Installation
1. Flash the OC zip of your choice in TWRP
2. Boot switchroot, enable Performance Mode & enjoy your overclock!
(Settings > System > Advanced > Display and Performance Configuration > Performance Mode)

If you haven't already flashed [**Magisk**](https://github.com/topjohnwu/Magisk/releases) & want root, you can flash magisk after this OC zip
