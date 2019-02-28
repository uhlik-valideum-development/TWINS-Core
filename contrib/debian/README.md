
Debian
====================
This directory contains files used to package valideumd/valideum-qt
for Debian-based Linux systems. If you compile valideumd/valideum-qt yourself, there are some useful files here.

## valideum: URI support ##


valideum-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install valideum-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your valideumqt binary to `/usr/bin`
and the `../../share/pixmaps/valideum128.png` to `/usr/share/pixmaps`

valideum-qt.protocol (KDE)

