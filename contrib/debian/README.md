
Debian
====================
This directory contains files used to package incognitod/incognito-qt
for Debian-based Linux systems. If you compile incognitod/incognito-qt yourself, there are some useful files here.

## incognito: URI support ##


incognito-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install incognito-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your incognitoqt binary to `/usr/bin`
and the `../../share/pixmaps/incognito128.png` to `/usr/share/pixmaps`

incognito-qt.protocol (KDE)

