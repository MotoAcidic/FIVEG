
Debian
====================
This directory contains files used to package fivegd/fiveg-qt
for Debian-based Linux systems. If you compile fivegd/fiveg-qt yourself, there are some useful files here.

## fiveg: URI support ##


fiveg-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install fiveg-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your fiveg-qt binary to `/usr/bin`
and the `../../share/pixmaps/fiveg128.png` to `/usr/share/pixmaps`

fiveg-qt.protocol (KDE)

