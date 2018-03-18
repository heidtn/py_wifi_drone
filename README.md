# Mini Wifi Drone
This library can be used with several of the mini inexpensive WiFi video drones you can get nowadays.  It's confirmed working with the fq777-954, but should also work with the Cheerson CX-10W and a few others running similar firmware.  It allows control of the drone as well as access to the video stream.

## Dependencies
The control should work out of the box, but video requires gstreamer which can be setup by following the instructions here: https://gstreamer.freedesktop.org/documentation/installing/on-linux.html

The video also requires OpenCV installed with the python bindings.

Finally pygame needs to be installed.

## Known issues
The video streaming isn't perfect and has some artifacting and delays.  On the app, the artifacting isn't present, so there should be a way to fix it.


This repo is forked from here: https://github.com/voorloopnul/drone-fq777-954