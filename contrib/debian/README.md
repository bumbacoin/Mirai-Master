
Debian
====================
This directory contains files used to package miraid/mirai-qt
for Debian-based Linux systems. If you compile miraid/mirai-qt yourself, there are some useful files here.

## mirai: URI support ##


mirai-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install mirai-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your miraiqt binary to `/usr/bin`
and the `../../share/pixmaps/mirai128.png` to `/usr/share/pixmaps`

mirai-qt.protocol (KDE)

