libinput
========

This repository is forked from [freedesktop](https://gitlab.freedesktop.org/libinput/libinput).

The gestures of touchpads are optimized to Ubuntu 22.04 on Lenovo Legion 570i.

Install
-------

```sh
$ sudo apt install build-essential meson ninja-build libudev-dev libmtdev-dev libevdev-dev libwacom-dev libgtk-4-dev check
$ meson --prefix=/usr builddir/
$ ninja -C builddir/
$ sudo ninja -C builddir/ install
```
