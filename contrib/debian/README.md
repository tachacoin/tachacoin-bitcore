
Debian
====================
This directory contains files used to package tachacoind/tachacoin-qt
for Debian-based Linux systems. If you compile tachacoind/tachacoin-qt yourself, there are some useful files here.

## tachacoin: URI support ##


tachacoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install tachacoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your tachacoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

tachacoin-qt.protocol (KDE)

