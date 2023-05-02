---
layout: default
title: Help
---

# Smartmontools Help

**Table of Contents**
* TOC
{:toc}

## Frequently Asked Questions (FAQ)
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

If the drive fails a self-test, but still has '`PASSED`' SMART health status, this usually means that there is a corrupted (uncorrectable=UNC) sector on the disk. See <a class="ext-link" href="https://trac.smartmontools.org/wiki/BadBlockHowto"><span class="icon"></span>Bad block HOWTO</a> for instructions about how to force this sector to reallocate.

## Howto Read `smartctl` Reports

### Annotated Reports

* <a class="ext-link" href="https://trac.smartmontools.org/wiki/Howto_ReadSmartctlReports_ATA_542.1"><span class="icon"></span>ATA-Disk (`smartctl 5.42`)</a>
* <a class="ext-link" href="https://trac.smartmontools.org/wiki/Howto_ReadSmartctlReports_ATA"><span class="icon"></span>ATA-Disk (`smartctl 5.39`)</a>

### Example Output

* <a class="ext-link" href="https://trac.smartmontools.org/wiki/Examples_HTS547550A9E384"><span class="icon"></span>ATA HDD (Hitachi) thru AHCI controller (`smartctl 6.5`)</a>
* <a class="ext-link" href="https://trac.smartmontools.org/wiki/Examples_SSDSC2BB120G4"><span class="icon"></span>SSD (Intel) thru AHCI controller (`smartctl 6.5`)</a>
* <a class="ext-link" href="https://trac.smartmontools.org/wiki/Examples_HUS154545VLS300"><span class="icon"></span>SAS HDD (Hitachi) thru MegaRAID SAS 1078 controller (`smartctl 6.5`)</a>
* <a class="ext-link" href="https://trac.smartmontools.org/wiki/Examples_EG0146FAWHU"><span class="icon"></span>SAS HDD (HP) thru HP Smart Array controller (`smartctl 5.43`)</a> 

#### Faulty Disks

* <a class="ext-link" href="https://trac.smartmontools.org/wiki/Examples_THNSNJ256GVNU"><span class="icon"></span>SSD (Toshiba) - self test detected read failure (`smartctl 6.5`)</a>

## Distribution-specific Bug Reports

The smartmontools package supports a number of different operating systems. Some of those operating systems are also distributed by multiple sources, and some of these maintain a database of bug reports. Here are links:

<ul>
    <li><a class="ext-link" href="http://bugs.debian.org/cgi-bin/pkgreport.cgi?which=pkg&amp;data=smartmontools&amp;archive=no"><span class="icon"></span>Debian Linux bug database</a></li>
    <li><a class="ext-link" href="https://bugzilla.redhat.com/buglist.cgi?field0-0-0=short_desc&amp;type0-0-1=anywords&amp;field0-0-1=status_whiteboard&amp;value0-0-2=smartmontools+smartsuite&amp;classification=Red+Hat&amp;classification=Fedora&amp;query_format=advanced&amp;field0-0-2=component&amp;value0-0-1=smartctl+smartd+smartmontools+smartsuite&amp;type0-0-0=anywords&amp;value0-0-0=smartctl+smartd+smartmontools+smartsuite&amp;type0-0-2=anywordssubstr"><span class="icon"></span>Redhat/Fedora Linux bugzilla database</a></li>
    <li><a class="ext-link" href="http://bugs.gentoo.org/buglist.cgi?query_format=advanced&amp;short_desc_type=allwordssubstr&amp;short_desc=&amp;long_desc_type=allwordssubstr&amp;long_desc=&amp;bug_file_loc_type=allwordssubstr&amp;bug_file_loc=&amp;status_whiteboard_type=allwordssubstr&amp;status_whiteboard=&amp;keywords_type=allwords&amp;keywords=&amp;emailtype1=substring&amp;email1=&amp;emailtype2=substring&amp;email2=&amp;bugidtype=include&amp;bug_id=&amp;votes=&amp;chfieldfrom=&amp;chfieldto=Now&amp;chfieldvalue=&amp;cmdtype=doit&amp;order=Reuse+same+sort+as+last+time&amp;field0-0-0=product&amp;type0-0-0=substring&amp;value0-0-0=smartmontools&amp;field0-0-1=component&amp;type0-0-1=substring&amp;value0-0-1=smartmontools&amp;field0-0-2=short_desc&amp;type0-0-2=anywords&amp;value0-0-2=smartctl+smartd+smartmontools&amp;field0-0-3=status_whiteboard&amp;type0-0-3=anywords&amp;value0-0-3=smartctl+smartd+smartmontools"><span class="icon"></span>Gentoo Linux bugzilla database</a></li>
    <li><a class="ext-link" href="https://bugs.launchpad.net/ubuntu/+source/smartmontools/"><span class="icon"></span>Ubuntu Linux bug database</a></li>
    <li><a class="ext-link" href="https://bugs.freebsd.org/bugzilla/buglist.cgi?order=resolution,bug_id%20DESC&amp;query_based_on=&amp;query_format=advanced&amp;short_desc=smartctl%20smartd%20smartmontools&amp;short_desc_type=anywords"><span class="icon"></span>FreeBSD bugzilla database</a></li
    ><li><a class="ext-link" href="https://gnats.netbsd.org/cgi-bin/query-pr-list.pl?text=smartctl%7Csmartd%7Csmartmontools&amp;state=open&amp;state=analyzed&amp;state=feedback&amp;state=suspended"><span class="icon"></span>NetBSD bug database</a></li
    ><li><a class="ext-link" href="http://trac.macports.org/query?port=smartmontools&amp;col=id&amp;col=summary&amp;col=status&amp;col=owner&amp;col=type&amp;col=priority&amp;desc=1&amp;order=status"><span class="icon"></span>MacPorts bug database</a></li>
</ul>

If you can provide additional distribution or OS-specific bug-database links, please send an email to <a class="ext-link" href="https://listi.jpberlin.de/mailman/listinfo/smartmontools-support"><span class="icon"></span>smartmontools-support mailing list</a>

## No Access To Sourceforge Services?

Our project offers <a class="ext-link" href="https://sourceforge.net/projects/smartmontools/files/?source=navbar"><span class="icon"></span>File Download</a> and <a class="ext-link" href="https://sourceforge.net/p/smartmontools/code/HEAD/tree/"><span class="icon"></span>SVN</a> which are hosted in <a class="ext-link" href="https://sourceforge.net/projects/smartmontools/"><span class="icon"></span>our project at SourceForge</a>. <a class="ext-link" href="https://sourceforge.net/"><span class="icon"></span>SourceForge</a> is a free service, which supports a very large number of users and projects. Please check <a class="ext-link" href="https://twitter.com/sfnet_ops"><span class="icon"></span>SF.net Operations</a> to see the maintenance schedule and to learn if SourceForge is experiencing unscheduled system outages or other problems.

For download purposes you can also use the <a class="ext-link" href="https://trac.smartmontools.org/browser"><span class="icon"></span>SVN mirror</a> and the <a class="ext-link" href="https://builds.smartmontools.org/"><span class="icon"></span>daily builds</a> on our own internet servers.

## Problems With Trac Registration?

In case of problems with your Trac registration write to the <a class="ext-link" href="https://listi.jpberlin.de/mailman/listinfo/smartmontools-devel"><span class="icon"></span>smartmontools team list</a>. This is a private list. Postings from non-member addresses are held in moderation queue and need manual approvement to go to the list. So you have to take a delay into account until your mail reaches the smartmontools team members.

## License
Smartmontools (and content of this website) are published under <a class="ext-link" href="https://www.gnu.org/licenses/gpl-2.0.html#SEC1"><span class="icon"></span>GNU GPL</a> if not otherwise explicitly declared in context of a contributed section or page.

---
[top](./help.html)
