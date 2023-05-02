---
layout: default
title: Supported RAID Controllers
---

# Checking disks behind RAID controllers

RAID controllers typically simulate a (logical) disk for each array of (physical) disks to the OS. Access to SMART functionality relies on ATA or SCSI pass through I/O controls providing direct access to each physical disk. But the standard I/O controls available are usually not designed to make this distinction between logical and physical disks. Therefore, smartmontools has to use vendor specific I/O controls. Support for disks behind RAID controllers is highly dependent on both platform and controller type. 

| RAID-Controller | Linux | FreeBSD | Windows |
| --------------- | :---: | :-----: | :-----: |
| LSI 3ware SATA RAID controller | `-d 3ware,N /dev/twX` [^1] | `-d 3ware,N /dev/twX` [^2] | `/dev/sdX,N` [^3] |
| Areca SATA[/SAS] RAID controller | `-d areca,N[/E] /dev/sgX` [^4] | `-d areca,N[/E] /dev/arcmsrX` [^11] | `-d areca,N[/E] /dev/arcmsrX` [^12] |
| HighPoint RocketRAID SATA RAID controller | `-d hpt,L/M/N /dev/sdX`[^5] | `-d hpt,L/M/N /dev/hptX` [^6] | - |
| CCISS (HP/Compaq Smart Array Controller) | `-d cciss,N /dev/sgX` [^7] | `-d cciss,N /dev/cissX` | - |
| LSI MegaRAID SAS RAID controller Dell PERC 5/i,6/i controller | `-d megaraid,N /dev/sdX` [^8] | `/dev/passX, -d megaraid,N /dev/mrsasX` [^9] | `/dev/csmiX,N` [^13] |
| Intel ICHxR RAID (Intel Rapid/Matrix Storage) | `/dev/sdX` | `/dev/adX` | `/dev/csmiX,N`[^10] |
| Adaptec SAS RAID controller (devices supported by <a class="ext-link" href="https://www.kernel.org/doc/Documentation/scsi/aacraid.txt"><span class="icon"></span>aacraid driver</a>) | `-d aacraid,H,L,ID /dev/sdX` [^14] | - | `-d aacraid,H,L,ID /dev/sdX` [^15] |

See the notes below and the <a class="ext-link" href="https://trac.smartmontools.org/browser/trunk/smartmontools/INSTALL"><span class="icon"></span>INSTALL</a><a class="ziplink" href="https://trac.smartmontools.org/export/HEAD/trunk/smartmontools/INSTALL" title="Download"><span class="icon"></span></a> file for information about kernel and driver requirements on your platform.
Also consult the <a href="/docs.html#man-pages">man pages</a> for controller specific smartmontools options or directives.

## Notes:
>   <font color="red">Smartmontools have no access to disks thru these RAID controllers on NetBSD, OpenBSD, MacOS and Solaris.</font><br>

[^1]: 3ware RAID controllers are supported on Linux since smartmontools release 5.1-18. Support for char devices /dev/twX was added in release 5.33.
[^2]: 3ware support on FreeBSD is available since release 5.33, multiple controller and char device support was added in release 5.36.
[^3]: 3ware 9000 series only (added in release 5.37), requires Windows driver 9.4.0 or later. For older controllers, smartctl and smartd provide limited SMART support through `tw_cli` tool, see man page. Initially the SMART support was added only to the 32-bit Windows driver. With recent driver versions SMART access works on 64-bit Windows 7 (see <a class="ext-link" href="http://sourceforge.net/mailarchive/forum.php?thread_name=20110420135554.701c2163%40linux.localdomain&forum_name=smartmontools-support"><span class="icon"></span>mailing list</a>) but not on 64-bit XP/2003 (see <a class="ext-link" href="https://trac.smartmontools.org/ticket/172"><span class="icon"></span>ticket ~~#172~~</a>).
[^4]: Areca SATA controller support for Linux was added in release 5.39. Areca SAS controller support (SATA drives only) was added in release 5.43. SAS drive support was added in release 6.1.
[^5]: HighPoint RocketRAID support for Linux was added in release 5.37.
[^6]: HighPoint RocketRAID support for FreeBSD was added in release 5.39.
[^7]: CCISS (Compaq Smart Array Controller) support for Linux was added in release 5.37. SATA auto-detection was added in release 5.43.
[^8]: Support for LSI MegaRAID controller on Linux was added in release 5.39. Please note that on some controllers device enumeration starts from 8 (use `-d megaraid,8` in such cases). In release 6.1 autoscan functionality implemented for the Linux version.
[^9]: Support of LSI MegaRAID on FreeBSD is implemented with mfip.ko module and /dev/passX devices. Direct access support -d megaraid and device scanning was added in release 7.3.
[^10]: Intel ICHxR RAID (CSMI) support for Windows was added in release 5.41. May also work with other controllers if the driver implements CSMI.
[^11]: Areca SATA controller support for FreeBSD was added in release 5.42. Areca SAS controller support (SATA drives only) was added in release 5.43. SAS drive support was added in release 6.1.
[^12]: Areca SATA/SAS controller support (SATA drives only) for Windows was added in release 5.43. SAS drive support was added in release 6.0.
[^13]: According to user reports, some Windows drivers for LSI MegaRAID and Dell PERC 6 implement CMSI (see <a class="ext-link" href="https://trac.smartmontools.org/ticket/243#comment:7"><span class="icon"></span>ticket ~~#243~~</a> and <a class="ext-link" href="http://sourceforge.net/p/smartmontools/mailman/message/30879378/"><span class="icon"></span>drive-database mailing list</a>), other drivers don't (see <a class="ext-link" href="http://sourceforge.net/p/smartmontools/mailman/message/31525054/"><span class="icon"></span>support mailing list)</a>.
[^14]: Aacraid support for Linux was added in release 6.3.
[^15]: Adaptec support for Windows was added in release 6.4. It is currently disabled on Windows due to unresolved bugs. Use `-d accraid,...,force` flag to try anyway. Details could be found in <a class="ext-link" href="https:/trac.smartmontools.org/ticket/1515"><span class="icon"></span>ticket #1515</a>. Please submit patches if you aware how to fix this issue or open ticket to the vendor.
