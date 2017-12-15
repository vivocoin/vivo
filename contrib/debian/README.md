
Debian
====================
This directory contains files used to package vivod/vivo-qt
for Debian-based Linux systems. If you compile vivod/vivo-qt yourself, there are some useful files here.

## vivo: URI support ##


vivo-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install vivo-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your vivo-qt binary to `/usr/bin`
and the `../../share/pixmaps/vivo128.png` to `/usr/share/pixmaps`

vivo-qt.protocol (KDE)

