systemd-unit
============

Arch Linux rc.d script that launches service defined in systemd service unit file.
Symlink script to same name as systemd unit has (without .service extension) and run as usual.

Depends on <a href="https://aur.archlinux.org/packages/initscripts-fork/">initscripts-fork</a> or anything that provides compatible _/etc/rc.d/functions_ library.


Usage: 
```
# ln -s systemd-unit NetworkManager
# /etc/rc.d/NetworkManager start
```

Changelog:
```
0.2 - added support for service@user symlink format
0.1 - initial
```
