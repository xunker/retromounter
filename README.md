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

### Initial MVP

HFS is the original focus of retromounter, as MacOS removed removed support for HFS with Catalina
(10.15, 2019). Even though HFS+ is supported currently (MacOS Sonoma, v14.4.1), I expect read/write
support to be dropped by 2026.

And, of course, Windows never had native support for either HFS or HFS+, so support for both is helpful.

* Apple
  - HFS (Hierarchical File System)
    * introduced in Macintosh System 2.1 (September, 1985)
    * removed in MacOS Catalina (10.15, 2019)
  - HFS+ (Hierarchical File System Plus)
    * introduced with MacOS 8.1 (January 19, 1998)
    * Still supported R/W as of MacOS Sonoma (v14.4.1)

### Follow-Up

The majourity of file systems here are because they are natively supported in the Linux kernel or by
modules, so support is basically free.

The outliers are ProDOS, Apple DOS 3.3, and MFS, which do not yet have support as native, mountable file
systems in Linux.

* Apple
  - ProDOS and DOS 3.3
    * Apple II ProDOS for 8-bit (Apple II) and 16-bit (Apple IIgs)
    * Apple II DOS 3.3 for 8-bit Apple II
  - MFS
    * Macintosh File System, for original Macintosh 128K, 512K, and MacXL
* Microsoft
  - FAT12
    * Floppy Disk (360KB to 2.88MB) Images
    * support built-in to Linux
  - FAT16, FAT32, exFAT
    * Hard Drive Images
    * support built-in to Linux
  - NTFS
    * Versions 1.0-3.1
    * Available as a kernel module
* Linux (support built-in to Linux)
  - ext2, ext3, ext4
  - btrfs
  - Reiserfs
* ISO-9660 (High Sierra, Joliet, Rock Ridge)
  - support built-in to Linux
* UDF (DVD)
  - support built-in to Linux

## Administrative

TBA

### License

GNU GPLv3

### Author

[M Nielsen](https://github.com/xunker), 2024

### URL

https://github.com/xunker/retromounter

### Sources / References / Thanks

TBA