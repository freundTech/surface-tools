# autorotate

A simple script for automatic screen rotation, using a 3d acceleration sensor.
This script does NOT remap your touchscreen to match the new rotation. Please run the penmon script from this repository to do this.

Configuration:
* sensorname: Name of the acceleration sensor. Can usualy be found at `/sys/bus/iio/devices/<device>/name`.
* screenname: Name of the screen to rotate. Run `xrandr -q` to list all screens.

Dependencies:
* python3
* xrandr
* pyudev
* pygobject
* gtk+3
* AppIndicator (optional)
