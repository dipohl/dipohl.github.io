---
layout: default
title: smartmontools
---

# Smartmontools Home

**Table of Contents**
* TOC
{:toc}

## News
<ul>
    <li><code>2022-10-10</code>: <strong>20th anniversary</strong> of <a class="ext-link" href="https://trac.smartmontools.org/changeset/13"><span class="icon"></span>smartmontools first release</a> - see also <a class="wiki" href="/history.html">smartmontools history</a>.</li>
    <li><code>2022-02-28</code>: <strong>We released <a class="ext-link" href="https://sourceforge.net/projects/smartmontools/files/smartmontools/7.3/"><span class="icon"></span>version 7.3 of Smartmontools</a>. See the <a class="ext-link" href="https://trac.smartmontools.org/browser/tags/RELEASE_7_3/smartmontools/NEWS"><span class="icon"></span>NEWS</a> file and the <a class="ext-link" href="https://trac.smartmontools.org/query?milestone=Release+7.3"><span class="icon"></span>ticket report</a> to get a summary of the changes and new features.</strong></li>
    <li><code>2022-02-04</code>: <strong>Alexander Shaduri released <a class="ext-link" href="https://github.com/ashaduri/gsmartcontrol/releases/tag/v1.1.4"><span class="icon"></span>version 1.1.4 of GSmartControl</a> (a graphical user interface for smartctl). Available for Linux, FreeBSD, MacOS X and Windows.</strong></li>
    <li><code>2021-10-23</code>: <strong>There is a security issue if <code>smartd</code> is used conjunction with GNU mailutils &lt; 3.13. See ticket <a class="ext-link" href="https://trac.smartmontools.org/ticket/1535" title="#1535: defect: Code execution vulnerability if smartd uses 'mail' from GNU mailutils ... (closed: fixed)"><span class="icon"></span>#1535</a> for details and various possible fixes.</strong></li>
    <li><code>2018-10-17</code>: In the past we offered <strong>daily builds</strong> on <a class="ext-link" href="https://builds.smartmontools.org"><span class="icon"></span>builds.smartmontools.org</a>. Now we do automated builds <strong>on every commit</strong> to the <a class="ext-link" href="https://trac.smartmontools.org/browser/trunk/smartmontools"><span class="icon"></span>repository</a>. Read more about it in section <a href="/#github-mirror-and-circle-ci-integration">GitHub mirror and Circle CI integration</a> below.</li>
    <li><code>2017-07-30</code>: Our mailing lists moved from sourceforge to JPBerlin. <strong>(!) Please subscribe on the <a href="/help.html#Mailinglists">new mailing lists</a></strong>.</li>
    <li>...see <a href="/news.html">here for further news</a></li>
</ul>

## About Smartmontools

The smartmontools package contains two utility programs (<code>smartctl</code> and <code>smartd</code>)
to control and monitor storage systems using the <em>Self-Monitoring, Analysis and
Reporting Technology System</em> (SMART) built into most modern ATA/SATA, SCSI/SAS and NVMe disks.
In many cases, these utilities will provide advanced warning of disk degradation and failure
 
Smartmontools was originally derived from the Linux <a class="ext-link" href="https://sourceforge.net/projects/smartsuite/"><span class="icon"></span>smartsuite package</a> and actually supports ATA/SATA, <a class="ext-link" href="https://trac.smartmontools.org/browser/trunk/www/smartmontools_scsi.xml"><span class="icon"></span>SCSI</a>/SAS and <a href="/NVMe_Support.html">NVMe</a> disks and also SCSI/SAS tape devices.
It should run on any modern Linux, FreeBSD, NetBSD, OpenBSD, Darwin (macOS), Solaris, Windows, Cygwin, OS/2, eComStation or QNX system.
Smartmontools can also be run from one of many different <a href="/LiveCDs.html">Live CDs/DVDs</a>.

Sourcecode tarballs and precompiled packages for Darwin (macOS) and Windows are available at the <a class="ext-link" href="https://sourceforge.net/projects/smartmontools/files/smartmontools/"><span class="icon"></span>project page at Sourceforge</a>.

<p>
<a style="padding:0; border:none" href="https://sourceforge.net/projects/smartmontools/files/smartmontools/7.3/stats/timeline"><img src="https://img.shields.io/sourceforge/dt/smartmontools/smartmontools/7.3?label=7.3%20downloads" alt="..." title="Total Downloads of 7.3" /></a>
<a style="padding:0; border:none" href="https://sourceforge.net/projects/smartmontools/files/smartmontools/7.3/stats/timeline"><img src="https://img.shields.io/sourceforge/dw/smartmontools/smartmontools/7.3?label=" alt="..." title="Weekly Downloads of 7.3" /></a>
<a style="padding:0; border:none" href="https://sourceforge.net/projects/smartmontools/files/smartmontools/7.2/stats/timeline"><img src="https://img.shields.io/sourceforge/dt/smartmontools/smartmontools/7.2?label=7.2%20downloads" alt="..." title="Total Downloads of 7.1" /></a>
...
<a style="padding:0; border:none" href="https://sourceforge.net/projects/smartmontools/files/stats/timeline?dates=2002-10-01+to+2021-12-31"><img src="https://img.shields.io/sourceforge/dt/smartmontools?label=all%20downloads" alt="..." title="Total Downloads since 2002" /></a>
</p>
<p>
Precompiled packages are available from the repositories of various distributions, see the <a class="wiki" href="/packages.html">Packages</a> page or <a class="ext-link" href="https://repology.org/project/smartmontools/versions"><span class="icon"></span>Repology.org</a>.
Some examples:
</p>
<p>
<a style="padding:0; border:none" href="https://www.archlinux.org/packages/?q=smartmontools"><img src="https://repology.org/badge/version-for-repo/arch/smartmontools.svg?header=Arch" alt="Arch" title="Arch" /></a>
<a style="padding:0; border:none" href="https://src.fedoraproject.org/rpms/smartmontools"><img src="https://repology.org/badge/version-for-repo/fedora_35/smartmontools.svg?header=Fedora%2035" alt="Fedora" title="Fedora" /></a>
<a style="padding:0; border:none" href="https://packages.debian.org/bullseye/smartmontools"><img src="https://repology.org/badge/version-for-repo/debian_11/smartmontools.svg?header=Debian%2011" alt="Debian" title="Debian" /></a>
<a style="padding:0; border:none" href="https://packages.ubuntu.com/jammy/smartmontools"><img src="https://repology.org/badge/version-for-repo/ubuntu_22_04/smartmontools.svg?header=Ubuntu%2022.04" alt="Ubuntu" title="Ubuntu" /></a>
<a style="padding:0; border:none" href="https://www.freshports.org/sysutils/smartmontools"><img src="https://repology.org/badge/version-for-repo/freebsd/smartmontools.svg?header=FreeBSD" alt="FreeBSD" title="FreeBSD" /></a>
<a style="padding:0; border:none" href="http://pkgsrc.se/sysutils/smartmontools"><img src="https://repology.org/badge/version-for-repo/pkgsrc_current/smartmontools.svg?header=NetBSD" alt="NetBSD" title="NetBSD" /></a>
<a style="padding:0; border:none" href="https://openports.pl/path/sysutils/smartmontools"><img src="https://repology.org/badge/version-for-repo/openbsd/smartmontools.svg?header=OpenBSD" alt="OpenBSD" title="OpenBSD" /></a>
<a style="padding:0; border:none" href="https://github.com/Homebrew/homebrew-core/commits/master/Formula/smartmontools.rb"><img src="https://repology.org/badge/version-for-repo/homebrew/smartmontools.svg?header=macOS%20%28brew%29" alt="macOS (brew)" title="macOS (brew)" /></a>
<a style="padding:0; border:none" href="https://github.com/macports/macports-ports/tree/master/sysutils/smartmontools"><img src="https://repology.org/badge/version-for-repo/macports/smartmontools.svg?header=macOS%20%28ports%29" alt="macOS (ports)" title="macOS (ports)" /></a>
<a style="padding:0; border:none" href="http://pkg.openindiana.org/hipster/en/search.shtml?token=smartmontools&amp;action=Search"><img src="https://repology.org/badge/version-for-repo/openindiana/smartmontools.svg?header=OpenIndiana" alt="OpenIndiana" title="OpenIndiana" /></a>
<a style="padding:0; border:none" href="https://chocolatey.org/packages/smartmontools"><img src="https://repology.org/badge/version-for-repo/chocolatey/smartmontools.svg?header=Windows%20%28choco%29" alt="Windows" title="Windows" /></a>
<a style="padding:0; border:none" href="https://cygwin.com/packages/summary/smartmontools.html"><img src="https://repology.org/badge/version-for-repo/cygwin/smartmontools.svg?header=Cygwin" alt="Cygwin" title="Cygwin" /></a>
...
<a style="padding:0; border:none" href="https://repology.org/badge/vertical-allrepos/smartmontools.svg"><img src="https://repology.org/badge/tiny-repos/smartmontools.svg" alt="in repositories" title="to repository overview" /></a>
</p>
<p>
Due to OS-specific issues and also depending on the different state of smartmontools development on the platforms, device support is not the same for all OS platforms.
See info about <a href="/Supported_RAID-Controllers.html">RAID-controller</a>, <a href="/USB.html">USB</a> and <a href="/NVMe_Support.html">NVMe</a> support here on the homepage and of course in the <a class="wiki" href="docs.html#Manpages">manpages</a>.
</p>
<p>
Thanks to Alexander Shaduri, there is also a graphical user interface for <code>smartctl</code> available.
Go to the Homepage of <a class="ext-link" href="https://gsmartcontrol.sourceforge.io/"><span class="icon"></span>GSmartControl</a> to get all info and the software itself.
Have a look at the <a class="ext-link" href="https://gsmartcontrol.sourceforge.io/home/index.php/Screenshots"><span class="icon"></span>screenshots</a>
and the <a class="ext-link" href="https://gsmartcontrol.sourceforge.io/home/index.php/About"><span class="icon"></span>feature list</a> to get an impression of this nice tool.
</p>

## Contribute to Smartmontools

### Device Information
If your drive is not in the <a class="ext-link" href="https://trac.smartmontools.org/browser/trunk/smartmontools/drivedb.h"><span class="icon"></span>current version of smartmontools drive database</a><a class="trac-rawlink" href="https://trac.smartmontools.org/export/HEAD/trunk/smartmontools/drivedb.h" title="Download"></a>, you can help to improve smartmontools information by <a href="/FAQ.html#MyATASATAdriveisnotinthesmartctlsmartddatabase">sending a report about your drive</a> to our mailinglist <a class="ext-link" href="https://listi.jpberlin.de/mailman/listinfo/smartmontools-database"><span class="icon"></span>smartmontools-database</a>.

We collect info about <a href="/Supported_USB-Devices.html">USB devices that have been successfully or unsuccessfully tested with smartmontools</a>. If you have information about a device not listed there, write an email to the <a class="ext-link" href="https://listi.jpberlin.de/mailman/listinfo/smartmontools-database"><span class="icon"></span>smartmontools-database mailinglist</a>.

### Bug Reports
To submit a bug report or propose an enhancement for smartmontools create a <a class="ext-link" href="https://trac.smartmontools.org/newticket"><span class="icon"></span>new ticket in smartmontools trac</a>. Login is needed for that. If you don't want to register an account, you can also send the info to our <a class="ext-link" href="https://listi.jpberlin.de/mailman/listinfo/smartmontools-support"><span class="icon"></span>smartmontools-support</a> mailing list.

### Patches
Patches are welcome! <strong>The most convenient way for us is, when you attach them to a <a class="ext-link" href="https://trac.smartmontools.org/newticket"><span class="icon"></span>new ticket in smartmontools trac</a></strong>. But it's also possible to submit patches for code review to <a class="ext-link" href="https://listi.jpberlin.de/mailman/listinfo/smartmontools-devel"><span class="icon"></span>developers mailinglist</a>. You don't need to be member of the mailinglist for it. Our list moderator will approve posting requests in these cases. Your patches should refer to our recent code base in <a href="download.html#InstalllatestunreleasedcodefromSVNrepository">SVN</a>. You should also have a look at the documents in the <a href="developer.html">developers area here on smartmontools homepage</a>. You will find info about smartmontools software architecture and tutorials and guidelines from our developers there.

### GitHub mirror and Circle CI integration
For those who prefer to use git and GitHub we maintain an <a class="ext-link" href="https://github.com/smartmontools/smartmontools/"><span class="icon"></span>official mirror</a> of the smartmontools project. Feel free to fork, submit PR-s and issues. The mirror is updated every 15 minutes from our sourceforge SVN. Also a Circle CI Continuous Integration and Delivery system has been setup, see <a class="ext-link" href="https://circleci.com/gh/smartmontools/smartmontools"><span class="icon"></span>builds page</a> for the details. Every commit to the GitHub triggers a new build and provides <a class="ext-link" href="https://builds.smartmontools.org"><span class="icon">​</span>a source tarball and various binaries</a> as artifacts.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;GitHub: <sub><a style="padding:0; border:none" href="https://github.com/smartmontools/smartmontools/issues"><img src="https://img.shields.io/github/issues/smartmontools/smartmontools?logo=github&amp;label=issues" alt="..." title="Open Issues" /></a> <a style="padding:0; border:none" href="https://github.com/smartmontools/smartmontools/issues?q=is%3Aclosed"><img src="https://img.shields.io/github/issues-closed/smartmontools/smartmontools?label=" alt="..." title="Closed Issues" /></a> <a style="padding:0; border:none" href="https://github.com/smartmontools/smartmontools/pulls"><img src="https://img.shields.io/github/issues-pr/smartmontools/smartmontools?logo=github&amp;label=pull%20requests" alt="..." title="Open PRs" /></a> <a style="padding:0; border:none" href="https://github.com/smartmontools/smartmontools/pulls?q=is%3Aclosed"><img src="https://img.shields.io/github/issues-pr-closed/smartmontools/smartmontools?label=" alt="..." title="Closed PRs" /></a></sub><br>
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Trunk build status: <sub><a style="padding:0; border:none" href="https://circleci.com/gh/smartmontools/smartmontools"><img width="66" alt="Build Status" src="https://circleci.com/gh/smartmontools/smartmontools.svg?style=svg" title="Build Status" height="18" /></a></sub><br>
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;CodeQL scanning: <sub><a style="padding:0; border:none" href="https://github.com/smartmontools/smartmontools/security/code-scanning"><img src="/assets/images/badge.svg" alt="..." title="CodeQL scanning" /></a></sub>

### Incident Reports
If you see a failure or have a problem with <a href="/developer.html#Facilities">our project facilities</a> you may report it to
<code>smartmontools-devel@listi.jpberlin.de</code>. You don't need to be subscribed for that. Your mail will then go to the list moderator and she will take action to solve the issue.

## License
Smartmontools (and content of this website) are published under <a class="ext-link" href="https://www.gnu.org/licenses/gpl-2.0.html#SEC1"><span class="icon"></span>GNU GPL</a> if not otherwise explicitly declared in context of a contributed section or page.

[top](./)
