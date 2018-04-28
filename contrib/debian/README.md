
Debian
====================
This directory contains files used to package xinardd/xinard-qt
for Debian-based Linux systems. If you compile xinardd/xinard-qt yourself, there are some useful files here.

## xinard: URI support ##


xinard-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install xinard-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your xinardqt binary to `/usr/bin`
and the `../../share/pixmaps/xinard128.png` to `/usr/share/pixmaps`

xinard-qt.protocol (KDE)

