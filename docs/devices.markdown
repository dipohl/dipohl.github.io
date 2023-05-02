---
layout: default
title: Device Support
---

# Smartmontools Device Support

**Table of Contents**
* TOC
{:toc}

Smartmontools work on different operating systems. Due to OS-specific issues and also depending on the different state of smartmontools development on the platforms, device support ist not the same for all OS platforms.

## Supported Devices

* <a href="/Supported_RAID-Controllers.html">RAID-Controllers</a> that work with smartmontools
* <a class="ext-link" href="https://trac.smartmontools.org/wiki/Supported_USB-Devices"><span class="icon"></span>USB-Devices</a> that work with smartmontools

## Documentation On Device Support

<ul>
    <li><a href="/NVMe_Support.html">Smartmontools supports NVMe starting from version 6.5</a></li>
    <li><a class="ext-link" href="https://trac.smartmontools.org/browser/trunk/www/smartmontools_scsi.xml"><span class="icon"></span>SCSI devices and smartmontools</a> - This article by <a class="ext-link" href="http://sourceforge.net/users/dpgilbert/"><span class="icon"></span>Douglas Gilbert</a> describes how smartmontools interacts with SCSI devices like disks and tapes (including medium changers). Passing reference is also made to devices that use the SCSI command set such as USB mass storage devices and IEEE1394 devices that use the "sbp2" protocol. In many situations SATA disks are accessed using a (partial) SCSI command set.</li>
    <li><a class="ext-link" href="https://trac.smartmontools.org/wiki/USB">USB devices and smartmontools</a> - To access SMART functionality, smartmontools must be able to send ATA commands directly to the disk.</li>
    <li><a href="/NAS.html">NAS devices and smartmontools</a> - Smartmontools can work also on <em>Network Attached Storage</em> (NAS) devices, if the appropiate functions are available there, e.g. on Dlink DNS-323 with <a class="ext-link" href="http://www.inreto.de/dns323/fun-plug/"><span class="icon"></span>fonz firmware</a></li>
</ul>

---
[top](./devices.html)
