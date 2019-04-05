
Debian
====================
This directory contains files used to package bitsbeed/bitsbee-qt
for Debian-based Linux systems. If you compile bitsbeed/bitsbee-qt yourself, there are some useful files here.

## bitsbee: URI support ##


bitsbee-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bitsbee-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bitsbeeqt binary to `/usr/bin`
and the `../../share/pixmaps/bitsbee128.png` to `/usr/share/pixmaps`

bitsbee-qt.protocol (KDE)

