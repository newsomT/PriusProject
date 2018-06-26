
Debian
====================
This directory contains files used to package priusd/prius-qt
for Debian-based Linux systems. If you compile priusd/prius-qt yourself, there are some useful files here.

## prius: URI support ##


prius-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install prius-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your priusqt binary to `/usr/bin`
and the `../../share/pixmaps/prius128.png` to `/usr/share/pixmaps`

prius-qt.protocol (KDE)

