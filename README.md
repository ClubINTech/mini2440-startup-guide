Startup guide
=============

Toolchain
---------

* Download buildroot (http://buildroot.uclibc.org/)
* make mini2440_defconfig
* make

GCC is in output/host/usr/bin.
Change your path with this directory.

When you want to cross-compile, set these variables: 
CROSS_COMPILE=arm-linux- 
PATH with arm-linux-gcc

U-boot
------

Send the bootloader with s3c2410 (using the USB host interface)
u-boot in u-boot directory works fine for me
