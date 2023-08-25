# Day 25

In order to correctly get the color effect, please fallow all instructions below.

1. Boot your raspberry pi and type `sudo pip3 install rpi_ws281x adafruit-circuitpython-neopixel`
2. Connect the `5v` and `GND` pins on the LED strip or ring to `5 Volts` and `GND` on the raspberry pi
3. Connect the `DI` pin on the LED strip or ring to `GPIO 18` on the raspberry pi
4. Download and save the code from this repository to a folder on your raspberry pi
5. open a terminal window and navigate to the folder where you put the code it. (i.e: `cd /path/to/code`)
6. Type `sudo python3 RingLight.py` then press `enter` (The code has to run with admin priviliges in order to work)
7. Congrates, you should have a working LED color effect. This will work with any ws2812 LED strip or ring.
