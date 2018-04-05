
Debian
====================
This directory contains files used to package envisiond/envision-qt
for Debian-based Linux systems. If you compile envisiond/envision-qt yourself, there are some useful files here.

## envision: URI support ##


envision-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install envision-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your envision-qt binary to `/usr/bin`
and the `../../share/pixmaps/envision128.png` to `/usr/share/pixmaps`

envision-qt.protocol (KDE)

