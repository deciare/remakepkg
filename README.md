remakepkg
=========

This is a script for Arch Linux (and other Linux distrbutions making use of the pacman package management system) that converts an already-installed package back into a pacman-installable archive.

This may be useful for backing up packages installed from AUR, particularly those that took multiple hours to build. The output from this script may also be installed on a different computer.

Usage
-----

    remakepkg <package-name>

Parameters
----------

__package-name__ is the name of a package that is currently installed, such as "freetype2-infinality" or "wine-silverlight".
