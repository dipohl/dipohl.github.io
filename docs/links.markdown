---
layout: default
title: Links
---

# Smartmontools Recommended Links

**Table of Contents**
* TOC
{:toc}

## Graphical And Web User Interfaces For `smartctl`

* <a class="ext-link" href="http://gsmartcontrol.sourceforge.net/home/index.php/About"><span class="icon"></span>GSmartControl</a> (C++, Linux, FreeBSD, MacOS X, Windows)
* <a class="ext-link" href="https://archive.codeplex.com/?p=hddguardian"><span class="icon"></span>HDD Guardian</a> (VB.NET, Windows, retired).
Due to <a class="ext-link" href="https://blogs.msdn.microsoft.com/bharry/2017/03/31/shutting-down-codeplex/"><span class="icon"></span>CodePlex shutdown</a>, see <a class="ext-link" href="https://github.com/native-api/hddguardian"><span class="icon"></span>GitHub</a> for source code, and <a class="ext-link" href="http://www.softpedia.com/get/System/Hard-Disk-Utils/HDD-Guardian.shtml"><span class="icon"></span>Softpedia</a> or <a class="ext-link" href="http://www.snapfiles.com/get/hddguardian.html"><span class="icon"></span>SnapFiles</a> for binaries.
* <a class="ext-link" href="http://binaryfruit.com/drivedx"><span class="icon"></span>DriveDx</a> (OS X, Proprietary Software)
* <a class="ext-link" href="https://www.volitans-software.com/apps/smart-utility/"><span class="icon"></span>SMART Utility</a> (OS X, Proprietary Software)
* <a class="ext-link" href="https://github.com/AnalogJ/scrutiny"><span class="icon"></span>scrutiny</a> WebUI for smartd S.M.A.R.T monitoring

## Monitoring Tools Working With Smartmontools

* <a class="ext-link" href="http://munin-monitoring.org/"><span class="icon"></span>Munin</a>
* <a class="ext-link" href="http://exchange.nagios.org/index.php?option=com_mtree&amp;task=search&amp;searchword=smartmontools#/"><span class="icon"></span>Nagios plugins</a>
* <a class="ext-link" href="https://www.thomas-krenn.com/en/wiki/SMART_Attributes_Monitoring_Plugin"><span class="icon"></span>SMART Attributes Monitoring Plugin</a>
* <a class="ext-link" href="https://share.zabbix.com/search-by/tags?value=smartmontools"><span class="icon"></span>Zabbix</a>
* <a class="ext-link" href="https://docs.netdata.cloud/collectors/python.d.plugin/smartd_log/"><span class="icon"></span>NetData SMART Attributes Monitoring Plugin</a>
* <a class="ext-link" href="https://docs.influxdata.com/telegraf/v1.14/plugins/plugin-list/#smart"><span class="icon"></span>S.M.A.R.T. Input Plugin for the Telegraf - plugin-driven server agent for collecting &amp; reporting metricsc</a>

## Mirrors And Forks Of Smartmontools

* <a class="ext-link" href="https://github.com/smartmontools/smartmontools"><span class="icon"></span>Official GitHub mirror</a> of <a class="extlink" href="https://trac.smartmontools.org/browser/"><span class="icon"></span>smartmontools SVN</a> - Feel free to fork, submit PR-s and issues.
* <a class="ext-link" href="https://github.com/mirror/smartmontools"><span class="icon"></span>Independent GitHub mirror</a> of <a class="extlink" href="https://trac.smarmtontools.org/browser/trunk/smartmontools"><span class="icon"></span>smartmontools SVN trunk</a><a class="ziplink" href="https://trac.smartmontools.org/browser/trunk/smartmontools?rev=5470&amp;format=zip" title="Download as Zip archive"><span class="icon"></span></a> - PR-s and issues placed here will possibly be ignored.
* <a class="ext-link" href="https://github.com/allanliu/smartmontools"><span class="icon"></span>libsmartctl</a> - Provides smartctl functionality as a static library.
* <a class="ext-link" href="https://sourceforge.net/p/xboxhdm2/smartmontools-sec/ci/master/tree/"><span class="icon"></span>Smartmontools with security</a> - a fork of
<a class="ext-link" href="https://trac.smartmontools.org/browser/tags/RELEASE_6_2/smartmontools"><span class="icon"></span>smartmontools 6.2</a><a class="ziplink" href="https://trac.smartmontools.org/browser/tags/RELEASE_6_2/smartmontools?rev=5470&amp;format=zip" title="Download as Zip archive"><span class="icon"></span></a> which adds
<a class="ext-link" href="http://www.xbmc4xbox.org.uk/forum/viewtopic.php?f=13&amp;t=4125"><span class="icon"></span>ATA Security commands</a> to `smartctl`.

## Other Projects Using Smartmontools

* <a class="ext-link" href="https://github.com/linuxhw/SMART"><span class="icon"></span>Linux Desktop HDD/SSD Reliability Test</a> - <a class="ext-link" href="https://github.com/linuxhw/EnterpriseDrive"><span class="icon"></span>Enterprise HDD/SSD Reliability Test</a> - a large collection of smartctl outputs collected by Linux users at <a class="ext-link" href="https://linux-hardware.org"><span class="icon"></span>linux-hardware.org</a>.
* <a class="ext-link" href="https://github.com/bsdhw/SMART"><span class="icon"></span>BSD HDD/SSD Reliability Test</a> - a large collection of smartctl outputs collected by BSD users at <a class="ext-link" href="https://bsd-hardware.info"><span class="icon"></span>bsd-hardware.info</a>.
* <a class="ext-link" href="https://github.com/dswarbrick/smart"><span class="icon"></span>Pure Go SMART library</a> (Go, GPLv3) - includes <a class="ext-link" href="https://github.com/dswarbrick/smart/tree/master/cmd/mkdrivedb"><span class="icon"></span>mkdrivedb</a> tool to download smartmontools <a class="ext-link" href="https://trac.smartmontools.org/browser/trunk/smartmontools/drivedb.h">drivedb.h</a><a class="ziplink" href="https://trac.smartmontools.org//export/HEAD/trunk/smartmontools/drivedb.h" title="Download"><span class="icon"></span></a> file and convert it to YAML.
* <a class="ext-link" href="https://pypi.python.org/pypi/pySMART/0.2"><span class="icon"></span>pySMART</a> - a simple Python wrapper for the smartctl component of smartmontools.
* <a class="ext-link" href="http://www.netpower.fr/smartmontools-win"><span class="icon"></span>Smartmontools for Windows Package</a>
(<a class="ext-link" href="https://github.com/deajan/smartmontools-win"><span class="icon"></span>Source Code</a>) - alternative smartmontools installation package for Windows.
* <a class="ext-link" href="https://www.supermicro.com/products/nfo/SMS_SD5.cfm"><span class="icon"></span>Supermicro SuperDoctor</a>

## Other HDD/SSD Related OpenSource Projects

## HDD/SSD References

## Studies / Background Info

## Useful References On SMART

## ATA/ATAPI References

## SCSI References

## NVMe References

## The Original SMART Specification

[top](./)
