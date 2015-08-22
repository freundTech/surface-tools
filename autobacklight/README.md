# autobacklight

A simple script for automaticlly adjusting the screen backlight dependent on the ambient light sensor.

Configuration:
* sensorname: Name of the ambient light sensor. Can usualy be found at `/sys/bus/iio/devices/<device>/name`.
* ambientlightmin: Minimal ambient light value the sensor can output. Currently does nothing.
* ambientlightmax: Ambient light value at which the backlight should be at maximum brightness.
* fadetime: Time the backlight needs to fade from one value to anothe in milliseconds.

Dependencies:
* python3
* xbacklight
* pyudev
* pygobject
* gtk+3
* AppIndicator (optional)
