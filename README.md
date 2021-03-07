# Gentoo on ESPRESSObin

This repository contains my configuration files and other useful tools for running Gentoo on the Marvell ESPRESSObin SBC (v5, 2 GB).
The system is configured to boot from a SSD instead of the usual micro SD card, for increased reliability.
It is configured to bridge all the Ethernet interfaces together with two WiFi access points (2.4 GHz and 5 GHz).

# Building

See the "usr/src/INSTALL" file for instructions on how to build the kernel and bootloader.
The cross-arm-linux-gnueabi toolchain is only required for building the toolchain and can be ignored otherwise.
