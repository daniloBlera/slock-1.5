# A fork of slock with my configs
Version forked: [1.5](https://dl.suckless.org/tools/slock-1.5.tar.gz)

# Patches used

* blur pixelated screen [(slock-blurpixelatedscreen-1.4.diff)][blur]

[blur]: https://tools.suckless.org/slock/patches/blur-pixelated-screen/slock-blur_pixelated_screen-1.4.diff

slock - simple screen locker
============================
simple screen locker utility for X.


Requirements
------------
In order to build slock you need the Xlib header files.


Installation
------------
Edit config.mk to match your local setup (slock is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install slock
(if necessary as root):

    make clean install


Running slock
-------------
Simply invoke the 'slock' command. To get out of it, enter your password.
