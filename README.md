sweep2sleep Disabler
==========

sweep2sleep is a gesture that exists on some Android ROMs (eg. Resurrection Remix N) that makes your device sleep if you slide right or left on the bottom of your screen.

This module disables sweep2sleep by running the following command in the "late_start" service:

`echo "0" > sys/sweep2sleep/sweep2sleep`


## Changelog
* v4   (06.05.2019) - Update to Magisk v18100 template
* v3   (18.11.2018) - Update to Magisk v17000 template
* v1.2 (07.09.2017) - Update to Magisk v1400 template
* v1.1 (25.07.2017) - Added to GitHub repo
* v1.0 (25.07.2017) - Initial release


## Notice
* Take a full backup before installing the module.
* You should use latest Magisk Manager to install this module. If you meet any problem under installation from Magisk Manager, please try to install it from recovery.


## Links
* [![XDA Thread](https://img.shields.io/badge/XDA-Thread-orange.svg)](https://forum.xda-developers.com/apps/magisk/magisk-sweep2sleep-disabler-t3681631)
* [![Magisk](https://img.shields.io/badge/Magisk-19%2B-00B39B.svg)](https://forum.xda-developers.com/apps/magisk/official-magisk-v7-universal-systemless-t3473445)


## Credits
* <a href="https://forum.xda-developers.com/member.php?u=4470081">topjohnwu@xda</a> for developing Magisk
* <a href="https://forum.xda-developers.com/member.php?u=4960264">Salkrikaltor@xda</a> for <a href="https://forum.xda-developers.com/showpost.php?p=70733735&postcount=962">sharing</a> how to disable it.


Copyright (C) 2017-2019 <a href="https://forum.xda-developers.com/member.php?u=6415870">tfae@xda</a> (tfaeusebio@gmail.com)
