
Debian
====================
This directory contains files used to package Orboxd/Orbox-qt
for Debian-based Linux systems. If you compile Orboxd/Orbox-qt yourself, there are some useful files here.

## Orbox: URI support ##


Orbox-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install Orbox-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your Orboxqt binary to `/usr/bin`
and the `../../share/pixmaps/Orbox128.png` to `/usr/share/pixmaps`

Orbox-qt.protocol (KDE)

