
Debian
====================
This directory contains files used to package BoomCoind/BoomCoin-qt
for Debian-based Linux systems. If you compile BoomCoind/BoomCoin-qt yourself, there are some useful files here.

## BoomCoin: URI support ##


BoomCoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install BoomCoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your BoomCoinqt binary to `/usr/bin`
and the `../../share/pixmaps/BoomCoin128.png` to `/usr/share/pixmaps`

BoomCoin-qt.protocol (KDE)

