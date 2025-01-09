
Debian
====================
This directory contains files used to package beerscoind/beerscoin-qt
for Debian-based Linux systems. If you compile beerscoind/beerscoin-qt yourself, there are some useful files here.

## beerscoin: URI support ##


beerscoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install beerscoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your beerscoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/beerscoin128.png` to `/usr/share/pixmaps`

beerscoin-qt.protocol (KDE)

