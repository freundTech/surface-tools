# autorotate

A simple script for remapping touch devices when a screen is rotated or (dis)connected.

Configuration:
* touchscreen: Screen to map the touch device to. RUn `xrandr -q` to list all screens.
* inputnames: Names of the input devices to remap. Run `xinput list` to list all input devices.

Dependencies:
* python
* xrandr
* xinput
