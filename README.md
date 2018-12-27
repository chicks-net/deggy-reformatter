# deggy-reformatter

[![Open Source Love png2](https://badges.frapsoft.com/os/v2/open-source.png?v=103)](https://github.com/ellerbrock/open-source-badges/)
[![GPLv2 license](https://img.shields.io/badge/License-GPLv2-blue.svg)](https://github.com/chicks-net/deggy-reformatter/blob/master/LICENSE)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-no-red.svg)](https://github.com/chicks-net/deggy-reformatter/graphs/commit-activity)

Take Deggy RTF files and reformat them

## Description

Takes Deggy reports in RTF and reformats them into text files while:

* validating that all points have been checked
* warning if extra swipes of the wand are logged
* showing gaps with no checks
* flagging if any "core hours" are not covered
* integrating guard schedule with [simple text format](Schedule_format.md)

## Requires

* Perl
* unrtf (deb/rpm is just `unrtf`)
* Perl module DateTime (debian package `libdatetime-perl` or rpm `perl-DateTime`)

## Utilities

* `copier` - renames randomly named input files into `DeggyReportYYYYMMDD` based on the content
* `downloader` - WIP to retrieve attachments from gmail

## Ideas

* integrate schedule from a google calendar
