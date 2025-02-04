# OpenWrt images for the NanoPi R3S/R4S/R5S

## Features
- Created from official builds using OpenWrt's imagebuilder.
- Includes LuCI interface w/ HTTPS support.
- Full Docker compatability using 'firewall', 'iptables-legacy' and 'ip6tables-legacy'.
- Auto-expands "/" partition on boot to fill microSD or eMMC.
- \[WIP\] Restores "user" packages on sysupgrade (when '-k' option is used).
- No extra packages or bloatware.

## Usage

1. Write image to microSD card

```shell
dd if=openwrt-*-sysupgrade.img of=/dev/diskX
```
