[RetroMounter](https://github.com/xunker/retromounter)
============

Read and write retrocomputing disk images with ease using a Raspberry Pi or similar SBC.

IMPORTANT
---------

This is currently a proof-of-concept and breaking changes will happen often without advance notice
and without migration strategies.

Do not expect useful version numbers or a meaningful changelog for quite some time.

## Purpose

TBA

## Supported File Systems

* Apple
  - HFS & HFS+
    * Apple Hierarchical File System, introduced in Macintosh System 2.1
    * Apple Hierarchical File System Plus, introduced with MacOS 8.1
  - MFS
    * Macintosh File System, for original Macintosh 128K, 512K, and MacXL
  - ProDOS
    * Apple II ProDOS for 8-bit (Apple II) and 16-bit (Apple IIgs)
  - DOS 3.3
    * Apple II DOS 3.3 for 8-bit Apple II
* HP
  - HFS/HPFS
    * High Performance File System for early HP/UX systems
  - JFS/VxFS
    * Journaling File System/Veritas File System for later HP/UX 10 and 11 systems
* Microsoft
  - FAT12
    * Floppy Disk (360KB to 2.88MB) Images
  - FAT16, FAT32, exFAT
    * Hard Drive Images
  - NTFS
    * Versions 1.0-3.1

## Administrative

### License

GNU GPLv3

### Author

[M Nielsen](https://github.com/xunker), 2024

### URL

https://github.com/xunker/retromounter

### Thanks

* Boot Script
  - https://gitlab.com/JimDanner/pi-boot-script/
  - https://github.com/rcapecce/RPI-Unattended-Install-on-Startup
* Ansible
  - https://github.com/motdotla/ansible-pi
  - https://github.com/glennklockwood/rpi-ansible

TBA