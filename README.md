deggy-reformatter
=================

Take Deggy RTF files and reformat them

Description
-----------

Takes Deggy reports in RTF and reformats them into text files while:

* validating that all points have been checked
* warning if extra swipes of the wand are logged
* showing gaps with no checks
* flagging if any "core hours" are not covered

Requires
--------

* Perl
* unrtf (deb/rpm is just `unrtf`)
* Perl module DateTime (debian package `libdatetime-perl` or rpm `perl-DateTime`)

Plans
-----

* integrate schedule from a google drive spreadsheet or maybe somewhere else
