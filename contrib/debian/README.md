
Debian
====================
This directory contains files used to package alanisd/alanis-qt
for Debian-based Linux systems. If you compile alanisd/alanis-qt yourself, there are some useful files here.

## alanis: URI support ##


alanis-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install alanis-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your alanisqt binary to `/usr/bin`
and the `../../share/pixmaps/alanis128.png` to `/usr/share/pixmaps`

alanis-qt.protocol (KDE)

