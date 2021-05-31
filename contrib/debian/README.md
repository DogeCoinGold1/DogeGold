
Debian
====================
This directory contains files used to package dogegoldd/dogegold-qt
for Debian-based Linux systems. If you compile dogegoldd/dogegold-qt yourself, there are some useful files here.

## dogegold: URI support ##


dogegold-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install dogegold-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your dogegold-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

dogegold-qt.protocol (KDE)

