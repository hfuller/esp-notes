# Witty development board, aka "The Burger"

I found this board on eBay under the name "ESP-12F ESP8266 Serial WiFi Development Board Micro USB Module With 3 Modes G6T5". It doesn't seem to have an easily-searchable model other than that. I've been calling it "the burger" because u put it together

It consists of two halves. The top half provides a light sensor, RGB LED, button, and Micro-USB power source. The bottom half provides a flash button, a reset button, and a Micro-USB programming interface.

Ignore anyone who tells you this RGB LED is a WS2812/NeoPixel. This is simply not the case. No clue why I keep seeing this "information" out there.

GPIO Connections:
* ESP8266 onboard blue LED: 2, inverted logic
* RGB LED red: 15
* RGB LED green: 12
* RGB LED blue: 13
* Light sensor: A0
* Button: 4

## Sources
* https://yoursunny.com/t/2016/WittyCloud-first/
* Multimeter
* School of hard knocks
