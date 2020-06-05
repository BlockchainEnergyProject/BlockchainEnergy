
Debian
====================
This directory contains files used to package blockchainenergyd/blockchainenergy-qt
for Debian-based Linux systems. If you compile blockchainenergyd/blockchainenergy-qt yourself, there are some useful files here.

## blockchainenergy: URI support ##


blockchainenergy-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install blockchainenergy-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your blockchainenergy-qt binary to `/usr/bin`
and the `../../share/pixmaps/blockchainenergy128.png` to `/usr/share/pixmaps`

blockchainenergy-qt.protocol (KDE)

