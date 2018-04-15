
Debian
====================
This directory contains files used to package tribed/tribe-qt
for Debian-based Linux systems. If you compile tribed/tribe-qt yourself, there are some useful files here.

## tribe: URI support ##


tribe-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install tribe-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your tribe-qt binary to `/usr/bin`
and the `../../share/pixmaps/tribe128.png` to `/usr/share/pixmaps`

tribe-qt.protocol (KDE)

