# ZX Spectrum HxC File Selector

![Downloads Badge][downloads-badge]
![Version Badge][version-badge]

![image](https://github.com/alexanderk23/zx-hxc-file-selector/assets/1713462/64bc45c5-b603-4397-b48e-a0829393d8f9)

**The ZX Spectrum HxC file selector** is designed to conveniently select and mount
disk image files on a **Gotek** flash drive directly from the ZX Spectrum.

The current version is designed to run on ZX Spectrums with Beta Disk Interface
and 128kb of memory. Support for other ZX Spectrum disk systems may be implemented
in future releases.

Gotek [HxC](https://hxc2001.com) or [FlashFloppy](https://github.com/keirf/flashfloppy)
firmware is required.

## Usage

**PLEASE BACK UP YOUR FLASH DRIVE CONTENTS BEFORE USE!**

Copy the **AUTOBOOT.HFE** and **HXCSDFE.CFG** files to the root folder of the USB drive.
Use the cursor keys and Enter (or the Kempston joystick) to navigate.
Pressing Enter/Fire on a disk image file mounts it to slot 1 and resets the machine to TR-DOS.

To return to the file selector, select slot 0 manually and reset the machine.

## Limitations

* Only FAT32 is supported.
* The current version is limited to 255 files per folder.
* Folders and files with names containing non-ASCII chars may not be displayed
correctly.

## Acknowledgments

* [Bizcat font](https://robey.lag.net/2020/02/09/bizcat-bitmap-font.html) by Robey Pointer
([CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/))
* [ZX0 decompressor](https://github.com/einar-saukas/zx0) by Einar Saukas

[downloads-badge]: https://img.shields.io/github/downloads/alexanderk23/zx-hxc-file-selector/total
[version-badge]: https://img.shields.io/github/v/release/alexanderk23/zx-hxc-file-selector
