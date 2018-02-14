
Debian
====================
This directory contains files used to package gocoinmed/gocoinme-qt
for Debian-based Linux systems. If you compile gocoinmed/gocoinme-qt yourself, there are some useful files here.

## gocoinme: URI support ##


gocoinme-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install gocoinme-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your gocoinmeqt binary to `/usr/bin`
and the `../../share/pixmaps/gocoinme128.png` to `/usr/share/pixmaps`

gocoinme-qt.protocol (KDE)

