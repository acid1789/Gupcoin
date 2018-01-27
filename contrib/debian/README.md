
Debian
====================
This directory contains files used to package gupcoind/gupcoin-qt
for Debian-based Linux systems. If you compile gupcoind/gupcoin-qt yourself, there are some useful files here.

## gupcoin: URI support ##


gupcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install gupcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your gupcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/gupcoin128.png` to `/usr/share/pixmaps`

gupcoin-qt.protocol (KDE)

