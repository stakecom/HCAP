
Debian
====================
This directory contains files used to package healcapitald/healcapital-qt
for Debian-based Linux systems. If you compile healcapitald/healcapital-qt yourself, there are some useful files here.

## healcapital: URI support ##


healcapital-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install healcapital-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your healcapitalqt binary to `/usr/bin`
and the `../../share/pixmaps/healcapital128.png` to `/usr/share/pixmaps`

healcapital-qt.protocol (KDE)

