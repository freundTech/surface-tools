# dynonboard

A simple script for automatically starting and stopping an onscreen keyboard when a physical keyboard is connected/disconnected.

Configuration:
* onboard: full path to the onscreen keyboard to start.
* keyboardname: Name of the keyboard to look for. Run `xinput list` to list all input devices.
* nameisdouble: Set this to `True` if there are 2 identically named devices and both have to be connected.

Dependencies:
* python3
* xinput
* killall
* Any onscreen keyboard (Suggested: onboard)
