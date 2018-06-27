
Debian
====================
This directory contains files used to package tacod/taco-qt
for Debian-based Linux systems. If you compile tacod/taco-qt yourself, there are some useful files here.

## taco: URI support ##


taco-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install taco-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your taco-qt binary to `/usr/bin`
and the `../../share/pixmaps/taco128.png` to `/usr/share/pixmaps`

taco-qt.protocol (KDE)

