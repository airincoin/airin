
Debian
====================
This directory contains files used to package airind/airin-qt
for Debian-based Linux systems. If you compile airind/airin-qt yourself, there are some useful files here.

## airin: URI support ##


airin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install airin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your airinqt binary to `/usr/bin`
and the `../../share/pixmaps/airin128.png` to `/usr/share/pixmaps`

airin-qt.protocol (KDE)

