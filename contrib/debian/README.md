
Debian
====================
This directory contains files used to package raptured/rapture-qt
for Debian-based Linux systems. If you compile raptured/rapture-qt yourself, there are some useful files here.

## rapture: URI support ##


rapture-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install rapture-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your rapture-qt binary to `/usr/bin`
and the `../../share/pixmaps/rapture128.png` to `/usr/share/pixmaps`

rapture-qt.protocol (KDE)

