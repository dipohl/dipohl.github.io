---
layout: default
title: Supported RAID Controllers
---

# Checking disks behind RAID controllers

RAID controllers typically simulate a (logical) disk for each array of (physical) disks to the OS. Access to SMART functionality relies on ATA or SCSI pass through I/O controls providing direct access to each physical disk. But the standard I/O controls available are usually not designed to make this distinction between logical and physical disks. Therefore, smartmontools has to use vendor specific I/O controls. Support for disks behind RAID controllers is highly dependent on both platform and controller type. 

| RAID-Controller | Linux | FreeBSD | Windows |
| --------------- | ----- | ------- | ------- |
| LSI 3ware SATA RAID controller | `-d 3ware,N /dev/twX` ([^1]) | `-d 3ware,N /dev/twX` ([^2]) | `/dev/sdX,N` ([^3]) |

:warning: Smartmontools have no access to disks thru these RAID controllers on NetBSD, OpenBSD, MacOS and Solaris.

[^1]: 3ware RAID controllers are supported on Linux since smartmontools release 5.1-18. Support for char devices /dev/twX was added in release 5.33.
[^2]: 3ware support on FreeBSD is available since release 5.33, multiple controller and char device support was added in release 5.36.
[^3]: 3ware 9000 series only (added in release 5.37), requires Windows driver 9.4.0 or later. For older controllers, smartctl and smartd provide limited SMART support through `tw_cli` tool, see man page. Initially the SMART support was added only to the 32-bit Windows driver. With recent driver versions SMART access works on 64-bit Windows 7 (see <a class="ext-link" href="http://sourceforge.net/mailarchive/forum.php?thread_name=20110420135554.701c2163%40linux.localdomain&forum_name=smartmontools-support"><span class="icon"></span>mailing list</a>) but not on 64-bit XP/2003 (see ticket <a class="ext-link" href="https://trac.smartmontools.org/ticket/172"><span class="icon"></span>~~#172~~</a>).
