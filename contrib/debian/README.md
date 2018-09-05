
Debian
====================
This directory contains files used to package hashtaltd/hashtalt-qt
for Debian-based Linux systems. If you compile hashtaltd/hashtalt-qt yourself, there are some useful files here.

## hashtalt: URI support ##


hashtalt-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install hashtalt-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your hashtalt-qt binary to `/usr/bin`
and the `../../share/pixmaps/hashtalt128.png` to `/usr/share/pixmaps`

hashtalt-qt.protocol (KDE)

