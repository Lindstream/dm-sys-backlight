Dream Machine: Intel Backlight
==============================
Neat backlight setter/getter written in C for Intel graphics.

All credit goes to its original author: ewaller @ https://bbs.archlinux.org/viewtopic.php?id=197863

Installation & allowing access to all users.
----
```
$user: gcc backlight.c
$user: su 
$root: mv a.out /usr/share/bin/backlight
$root: chmod +s !$
$root: exit
``` 