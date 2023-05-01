---
layout: default
title: Help
---

# Smartmontools Help

**Table of Contents**
* TOC
{:toc}

## Frequently asked questions (FAQ)
If you have problems or need support, first look at the page with answers to [frequently asked questions](/faq.html).

## Mailinglists
**Note:** On 2017-07-30 we started new mailing lists.

<ul>
    <li><a class="ext-link" href="https://listi.jpberlin.de/mailman/listinfo/smartmontools-support"><span class="icon"></span>smartmontools-support</a> - <em>This is the support, discussion, bug report and suggestion mailing list for smartmontools</em></li>
    <li><a class="ext-link" href="https://listi.jpberlin.de/mailman/listinfo/smartmontools-database"><span class="icon"></span>smartmontools-database</a> - <em>List for contributions of info about drives that are not yet in smartmontools drive db</em></li>
    <li><a class="ext-link" href="https://listi.jpberlin.de/mailman/listinfo/smartmontools-announce"><span class="icon"></span>smartmontools-announce</a> - <em>Announcement mailing list for the smartmontools package</em>
</li>
</ul>

If you don't find an answer in the FAQs, the next step is, to
<a class="ext-link" href="http://sourceforge.net/p/smartmontools/mailman/search/?q=&amp;mail_list=smartmontools-support"><span class="icon"></span>search the (old) support mailing list archives</a>.

List of searchable archives on the internet:

<table>
    <tr>
        <td> smartmontools-support (Old List!): </td>
        <td> <a class="ext-link" href="https://sourceforge.net/p/smartmontools/mailman/smartmontools-support/"><span class="icon"></span>SourceForge</a> </td>
        <td> - </td>
        <td> <a class="ext-link" href="https://marc.info/?l=smartmontools-support"><span class="icon"></span>MARC</a> </td>
        <td> <a class="ext-link" href="http://markmail.org/search/?q=list%3Asmartmontools-support"><span class="icon"></span>MarkMail</a> </td>
        <td> <a class="ext-link" href="http://smartmontools-support.narkive.com/"><span class="icon"></span>Narkive</a></td>
    </tr><tr>
        <td> smartmontools-database (Old List!): </td>
        <td> <a class="ext-link" href="https://sourceforge.net/p/smartmontools/mailman/smartmontools-database/"><span class="icon"></span>SourceForge</a> </td>
        <td> <a class="ext-link" href="https://www.mail-archive.com/smartmontools-database@lists.sourceforge.net/"><span class="icon"></span>Mail-Archive</a> </td>
        <td> <a class="ext-link" href="https://marc.info/?l=smartmontools-database"><span class="icon"></span>MARC</a> </td>
        <td> - </td>
        <td> <a class="ext-link" href="http://smartmontools-database.narkive.com/"><span class="icon"></span>Narkive</a></td>
    </tr>
</table>

If you don't find an answer to your question in the archives, then please send an email to the <a class="ext-link" href="https://listi.jpberlin.de/mailman/listinfo/smartmontools-support"><span class="icon"></span>smartmontools-support mailing list</a>. This is a moderated forum: you are not required to subscribe to the list in order to post your question. You can ask all questions concerning the installation and use of smartmontools. Or perhaps [you want to become a developer](/developer.html), or <a class="ext-link" href="https://trac.smartmontools.org/newticket">suggest some new extensions</a>?

## Serious Problem Reports

If you are worried about your disks `Health` state, because `smartctl` gave critical warnings or reported strange attribute values: Have a look at the [FAQ](/faq.html) page and consult the [section on how to read smartctl reports](#Howtoreadsmartctlreports).

If the drive fails a self-test, but still has '`PASSED`' SMART health status, this usually means that there is a corrupted (uncorrectable=UNC) sector on the disk. See [Bad block HOWTO](https://trac.smartmontools.org/wiki/BadBlockHowto) for instructions about how to force this sector to reallocate.
