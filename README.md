# A build of slock with my configs
Version forked: [1.5](https://dl.suckless.org/tools/slock-1.5.tar.gz)

# Patches used

* blur pixelated screen ([slock-blurpixelatedscreen-1.4.diff][blur])
* message ([slock-message-20191002-b46028b.diff][message])

[blur]: https://tools.suckless.org/slock/patches/blur-pixelated-screen/slock-blur_pixelated_screen-1.4.diff
[message]: https://tools.suckless.org/slock/patches/message/slock-message-20191002-b46028b.diff


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
Before running, check the available fonts with `slock -f`
and set `font_name` in `config.h` accordingly.

Simply invoke the 'slock' command. To get out of it, enter your password.
