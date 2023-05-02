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

* <a class="ext-link" href="https://crystalmark.info/en/software/crystaldiskinfo/"><span class="icon"></span>CrystalDiskInfo</a> (C++, MIT, Windows)
* <a class="ext-link" href="http://0pointer.de/blog/projects/being-smart.html"><span class="icon"></span>libatasmart, skdump, sktest</a> (C, LGPLv2.1, Linux)
* <a class="ext-link" href="http://hdck.sourceforge.net/"><span class="icon"></span>hdck</a> (C, GPLv3, Linux)
* <a class="ext-link" href="https://sourceforge.net/projects/hdparm/"><span class="icon"></span>hdparm</a> (C, BSD, Linux)
* <a class="ext-link" href="https://github.com/Cisco-Talos/MBRFilter"><span class="icon"></span>MBRFilter</a> (C, GPLv2, Windows) - Disk filter driver that prevents writing to sector 0
* <a class="ext-link" href="https://www.naraeon.net/en/latest-nvme-tools/"><span class="icon"></span>Naraeon NVMe Tools</a> (Delphi, GPLv3, Windows)
* <a class="ext-link" href="https://www.naraeon.net/en/latest-naraeon-ssd-tools"><span class="icon"></span>Naraeon SSD Tools</a> (Delphi, MIT, Windows)
* <a class="ext-link" href="https://github.com/linux-nvme/nvme-cli"><span class="icon"></span>nvme-cli</a> (C, GPLv2, Linux/FreeBSD)
* <a class="ext-link" href="https://github.com/Seagate/openSeaChest"><span class="icon"></span>openSeaChest (Seagate)</a> (C, MPLv2, Cross platform)
* <a class="ext-link" href="https://github.com/CyberShadow/trimcheck"><span class="icon"></span>trimcheck</a> (D, MPLv2, Windows)
* <a class="ext-link" href="https://github.com/kasbert/OS-X-SAT-SMART-Driver"><span class="icon"></span>OS X SAT SMART Driver</a> (C++, APSL, Mac OS) - kernel driver for providing access to external (USB or FireWire) drive SMART data

## HDD/SSD References

* <a class="ext-link" href="http://www.johnnylucky.org/data-storage/ssd-database.html"><span class="icon"></span>Johnny Lucky Solid State Drive Database</a>
* <a class="ext-link" href="http://www.hddoracle.com/viewtopic.php?f=59&amp;t=2034"><span class="icon"></span>Vendor specific SMART attributes for SSDs by Apple, Dell, HP and Lenovo</a>

## Studies / Background Info

* <a class="ext-link" href="https://www.backblaze.com/b2/hard-drive-test-data.html"><span class="icon"></span>Hard Drive Data and Stats</a>, Brian Beach, Andy Klein in <em>Backblaze Blog</em>, since November 2013.
* <a class="ext-link" href="https://www.ru.nl/publish/pages/909275/draft-paper_1.pdf"><span class="icon"></span>Self-encrypting deception: weaknesses in the encryption of solid state drives</a>, Carlo Meijer, Bernard van Gastel, November 2018 (see also <a class="ext-link" href="https://www.schneier.com/blog/archives/2018/11/security_of_sol.html"><span class="icon">​</span>Schneier on Security</a>).
* <a class="ext-link" href="https://www.backblaze.com/blog/helium-filled-hard-drive-failure-rates/"><span class="icon"></span>The Helium Factor and Hard Drive Failure Rates</a>, Andy Klein in <em>Backblaze Blog</em>, May 2018.
* <a class="ext-link" href="https://www.backblaze.com/blog/what-smart-stats-indicate-hard-drive-failures/"><span class="icon">​</span>What SMART Stats Tell Us About Hard Drives</a>, Andy Klein in <em>Backblaze Blog</em>, October 2016.
* <a class="ext-link" href="https://eprint.iacr.org/2015/1002"><span class="icon"></span>got HW crypto? On the (in)security of a Self-Encrypting Drive series</a>, Gunnar Alendal, Christian Kison, modg, September 2015.
* <a class="ext-link" href="http://techreport.com/review/24841/introducing-the-ssd-endurance-experiment"><span class="icon"></span>The SSD Endurance Experiment:</a>
<a class="ext-link" href="http://techreport.com/review/25320/the-ssd-endurance-experiment-22tb-update"><span class="icon"></span>22TB</a>,
<a class="ext-link" href="http://techreport.com/review/25559/the-ssd-endurance-experiment-200tb-update"><span class="icon"></span>200TB</a>,
<a class="ext-link" href="http://techreport.com/review/25681/the-ssd-endurance-experiment-testing-data-retention-at-300tb"><span class="icon"></span>300TB</a>,
<a class="ext-link" href="http://techreport.com/review/25889/the-ssd-endurance-experiment-500tb-update"><span class="icon"></span>500TB</a>,
<a class="ext-link" href="http://techreport.com/review/26058/the-ssd-endurance-experiment-data-retention-after-600tb"><span class="icon"></span>600TB</a>,
<a class="ext-link" href="http://techreport.com/review/26523/the-ssd-endurance-experiment-casualties-on-the-way-to-a-petabyte"><span class="icon"></span>1PB</a>,
<a class="ext-link" href="http://techreport.com/review/27062/the-ssd-endurance-experiment-only-two-remain-after-1-5pb"><span class="icon"></span>1.5PB</a>,
<a class="ext-link" href="http://techreport.com/review/27436/the-ssd-endurance-experiment-two-freaking-petabytes"><span class="icon"></span>2PB</a>,
<a class="ext-link" href="http://techreport.com/review/27909/the-ssd-endurance-experiment-theyre-all-dead"><span class="icon"></span>They're all dead</a>,
Geoff Gasior in <em>The Tech Report</em>, August 2013 - March 2015.
* <a class="ext-link" href="https://indico.cern.ch/event/320819/contributions/742938/attachments/618990/851639/SSD_Benchmarking_at_CERN__HEPiX_Fall_2014.pdf"><span class="icon"></span>SSD Benchmarking at CERN</a>
(<a class="ext-link" href="https://lvalsan.web.cern.ch/lvalsan/ssd_benchmarking/"><span class="icon"></span>Results</a>), Liviu Vâlsan in <em>HEPiX Fall 2014 Workshop</em>, October 2014.
* <a class="ext-link" href="http://queue.acm.org/detail.cfm?id=2385276"><span class="icon"></span>Anatomy of a Solid-state Drive</a>,
Michael Cornwell (Pure Storage) in <em>ACM Queue vol 10, no 10</em>, October 2012.
* <a class="ext-link" href="http://www.computerworld.com/article/2536400/disaster-recovery/vendor-disk-failure-rates--myth-or-metric-.html"><span class="icon"></span>Vendor disk failure rates: Myth or metric?</a>, 
Mary Brandel in <em>Computerworld</em>, April 2008.
* <a class="ext-link" href="https://www.usenix.org/legacy/events/fast08/tech/full_papers/jiang/jiang_html/index.html"><span class="icon"></span>Are Disks the Dominant Contributor for Storage Failures? A Comprehensive Study of Storage Subsystem Failure Characteristics</a>,
Weihang Jiang, Chongfeng Hu, Yuanyuan Zhou, Arkady Kanevsky in <em>6th USENIX Conference on File and Storage Technologies (FAST '08)</em>, pg 111-125, February 2008.
* <a class="ext-link" href="http://queue.acm.org/detail.cfm?id=1317403"><span class="icon"></span>Hard Disk Drives: The Good, The Bad and The Ugly</a>, 
Jon Elerath (Network Appliance) in <em>ACM Queue vol 5, no 6</em>, pg 28-37, September 2007.
* <a class="ext-link" href="https://www.usenix.org/legacy/events/fast07/tech/schroeder/schroeder_html/index.html"><span class="icon"></span>Disk Failures in the Real World: What does an MTTF of 1,000,000 hours mean to you?</a>,
Bianca Schroeder, Garth A. Gibson (Carnegie Mellon University) in <em>5th USENIX Conference on File and Storage Technologies (FAST '07)</em>, pg 1-16, February 2007.
* <a class="ext-link" href="https://www.usenix.org/legacy/events/fast07/tech/full_papers/pinheiro/pinheiro_html/index.html"><span class="icon"></span>Failure Trends in a Large Disk Drive Population</a>,
Eduardo Pinheiro, Wolf-Dietrich Weber, Luiz André Barroso (Google Inc.) in <em>5th USENIX Conference on File and Storage Technologies (FAST '07)</em>, pg 17-28, February 2007.
* <a class="ext-link" href="http://ieeexplore.ieee.org/xpl/articleDetails.jsp?reload=true&amp;tp=&amp;arnumber=816306"><span class="icon"></span>Specifying Reliability in the Disk Drive Industry: No More MTBF's</a>,
Jon G. Elerath (IBM Storage Systems Division) in <em>Proceedings of the IEEE 2000 Annual Reliability and Maintainability Symposium</em>, pg 194, January 2000.

## Useful References On SMART

<a class="ext-link" href="http://www.wikipedia.org/"><span class="icon"></span>Wikipedia</a> articles about SMART:

>   
<a class="ext-link" href="http://en.wikipedia.org/wiki/S.M.A.R.T."><span class="icon"></span>English</a>,
<a class="ext-link" href="http://de.wikipedia.org/wiki/Self-Monitoring%2C_Analysis_and_Reporting_Technology"><span class="icon"></span>Deutsch</a>,
<a class="ext-link" href="http://es.wikipedia.org/wiki/S.M.A.R.T."><span class="icon"></span>Español</a>,
<a class="ext-link" href="http://fr.wikipedia.org/wiki/Self-Monitoring%2C_Analysis_and_Reporting_Technology"><span class="icon"></span>Français</a>,\
<a class="ext-link" href="http://it.wikipedia.org/wiki/Self-Monitoring%2C_Analysis_and_Reporting_Technology"><span class="icon"></span>Italiano</a>,
<a class="ext-link" href="http://ja.wikipedia.org/wiki/Self-Monitoring%2C_Analysis_and_Reporting_Technology"><span class="icon"></span>Japanese</a>,
<a class="ext-link" href="http://nl.wikipedia.org/wiki/S.M.A.R.T."><span class="icon"></span>Nederlands</a>,
<a class="ext-link" href="http://pl.wikipedia.org/wiki/S.M.A.R.T._%28informatyka%29"><span class="icon"></span>Polski</a>,\
<a class="ext-link" href="http://pt.wikipedia.org/wiki/S.M.A.R.T."><span class="icon"></span>Português</a>,
<a class="ext-link" href="http://ru.wikipedia.org/wiki/%D0%A2%D0%B5%D1%85%D0%BD%D0%BE%D0%BB%D0%BE%D0%B3%D0%B8%D1%8F_SMART"><span class="icon"></span>Russian</a>,
<a class="ext-link" href="http://sk.wikipedia.org/wiki/S.M.A.R.T"><span class="icon"></span>Slovenčina</a>,
<a class="ext-link" href="http://sv.wikipedia.org/wiki/S.M.A.R.T."><span class="icon"></span>Svenska</a>

<a class="ext-link" href="http://smartlinux.sourceforge.net/smart/"><span class="icon"></span>Zbigniew Chlondowski's SMART Information Site</a> (no longer maintained)

## ATA/ATAPI References

The <a class="ext-link" href="http://www.t13.org"><span class="icon"></span>homepage of the T13 project</a>.\
Access to documents requires a T13 account.

## SCSI References

The <a class="ext-link" href="https://www.t10.org"><span class="icon"></span>homepage of the T10 project</a>.\
Public documents are available under the conditions of the <a class="ext-link" href="https://www.t10.org/t10_access.htm"><span class="icon"></span>T10 public-access model</a>.

## NVMe References

See <a href="/NVMe_Support.html#AboutNVMe">NVMe page on Smartmontools website</a>.

## The Original SMART Specification

The original SMART specification is SFF-8035i from the <a class="ext-link" href="http://www.sffcommittee.com/ns/"><span class="icon"></span>Small Form Factors (SFF) Committee</a>.\
Here is the <a class="ext-link" href="ftp://ftp.seagate.com/sff/INF-8035.TXT"><span class="icon"></span>SFF "link"</a> (they have <a class="ext-link" href="ftp://ftp.seagate.com/sff/SFF-8000.TXT"><span class="icon"></span>"expired" </a> the document).
* <a class="ext-link" href="http://www.linux-mips.org/pub/linux/mips/people/macro/S.M.A.R.T./SFF-8035i.pdf"><span class="icon"></span>SFF-8035i "Self-Monitoring, Analysis and Reporting Technology (S.M.A.R.T.)" version 1.0</a>, May 1995.
* <a class="ext-link" href="http://www.linux-mips.org/pub/linux/mips/people/macro/S.M.A.R.T./8035R2_0.PDF"><span class="icon"></span>SFF-8035i "Self-Monitoring, Analysis and Reporting Technology (S.M.A.R.T.)" revision 2.0</a>, April 1996.
* <a class="ext-link" href="http://www.linux-mips.org/pub/linux/mips/people/macro/S.M.A.R.T./8055.PDF"><span class="icon"></span>SFF-8055i "S.M.A.R.T. Applications Guide for the ATA and SCSI Interfaces" revision 1.4</a>, June 1996.

---
[top](./links.html)
