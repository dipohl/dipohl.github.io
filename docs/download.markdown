---
layout: default
title: Download 
---

## Smartmontools Download and Installation

**Table of Contents**
* TOC
{:toc}

Smartmontools 7.3 was released 2022-02-28, see <a class="ext-link" href="https://trac.smartmontools.org/browser/tags/RELEASE_7_3/smartmontools/NEWS">NEWS</a><a class="ziplink" href="https://trac.smartmontools.org/export/HEAD/tags/RELEASE_7_3/smartmontools/NEWS" title="Download"><span class="icon"></span></a>,&nbsp;
<a class="ext-link" href="https://trac.smartmontools.org/browser/tags/RELEASE_7_3/smartmontools/ChangeLog">ChangeLog</a><a class="ziplink" href="https://trac.smartmontools.org/export/HEAD/tags/RELEASE_7_3/smartmontools/ChangeLog" title="Download"><span class="icon"></span></a>&nbsp; 
and <a class="ext-link" href="https://trac.smartmontools.org/query?milestone=Release+7.3"><span class="icon"></span>tickets</a> for details.

Release files are signed with OpenPGP/GPG key ID `FF3AEFF5`, fingerprint: `0C95 77FD 2C4C FCB4 B9A5 9964 0A30 812E FF3A EFF5`.

The public key block is available here:
<a class="ext-link" href="https://trac.smartmontools.org/browser/trunk/www/SmartmontoolsSigningKey_2021.txt"><span class="icon"></span>Trac Browser</a><a class="ziplink" href="https://trac.smartmontools.org//export/HEAD/trunk/www/SmartmontoolsSigningKey_2021.txt" title="Download"><span class="icon"></span></a>,
<a class="ext-link" href="https://sourceforge.net/p/smartmontools/code/HEAD/tree/trunk/www/SmartmontoolsSigningKey_2021.txt"><span class="icon"></span>SVN Repository</a>,
<a class="ext-link" href="https://keyserver.ubuntu.com/pks/lookup?search=0xFF3AEFF5&amp;fingerprint=on&amp;op=index"><span class="icon"></span>Key Servers</a> 
(see the <a href="/faq.html#check-signature">FAQ</a> for older keys).

After installation or booting from a <a href="/Live-CD.html">Live-CD</a>, you can read smartmontools man pages and try out the commands:
```
  man smartd.conf
  man smartctl
  man smartd
  
  sudo /usr/sbin/smartctl -s on -o on -S on /dev/sda
  sudo /usr/sbin/smartctl -x /dev/sda
```
Note that the default location for the manual pages are `/usr/share/man/man5` and `/usr/share/man/man8`. If `'man'` doesn't find them, then you may need to add `/usr/share/man` to your `MANPATH` environment variable.

The <a href="#InstalltheWindowspackage">Windows package</a> provides preformatted man pages in `.html` and `*.txt` format.

## Install precompiled package
Precompiled packages are available for many distributions, see the <a class="ext-link" href="https://trac.smartmontools.org/wiki/Packages"><span class="icon"></span>Packages page</a>.
