
Debian
====================
This directory contains files used to package slashd/slash-qt
for Debian-based Linux systems. If you compile slashd/slash-qt yourself, there are some useful files here.

## slash: URI support ##


slash-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install slash-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your slash-qt binary to `/usr/bin`
and the `../../share/pixmaps/slash128.png` to `/usr/share/pixmaps`

slash-qt.protocol (KDE)

