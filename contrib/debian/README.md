
Debian
====================
This directory contains files used to package itcoind/itcoin-qt
for Debian-based Linux systems. If you compile itcoind/itcoin-qt yourself, there are some useful files here.

## pivx: URI support ##


itcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install itcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your itcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/pivx128.png` to `/usr/share/pixmaps`

itcoin-qt.protocol (KDE)

