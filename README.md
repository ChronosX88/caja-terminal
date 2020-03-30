caja-terminal
======================

>Embedded terminal in caja

caja-terminal is an embedded terminal in caja, the MATE's file browser.
It is always open in the current folder, and follows the navigation.

*Caja terminal is a fork of nautilus terminal.*

Dependencies:

    * PyGObject 3.x <https://pygobject.readthedocs.io/en/latest/>

	* Caja Python <https://github.com/mate-desktop/python-caja>

	* VTE with GObject Introspection <https://wiki.gnome.org/Apps/Terminal/VTE>

	* Python XDG <http://freedesktop.org/wiki/Software/pyxdg>

Building dependencies:

    * GNU gettext <http://www.gnu.org/software/gettext/>

	* Bash

Install:

    To install Caja Terminal, run `./install.sh --install` as root.

Uninstall:

    To uninstall Caja Terminal, run
    `/usr/share/caja-terminal/install.sh --remove` as root.
