
Debian
====================
This directory contains files used to package utumd/utum-qt
for Debian-based Linux systems. If you compile utumd/utum-qt yourself, there are some useful files here.

## utum: URI support ##


utum-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install utum-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your utumqt binary to `/usr/bin`
and the `../../share/pixmaps/utum128.png` to `/usr/share/pixmaps`

utum-qt.protocol (KDE)

