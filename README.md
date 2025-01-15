## Adafruit Mini Sparkle Motion - WLED-friendly ESP32 NeoPixel LED Driver PCB

<a href="http://www.adafruit.com/products/6160"><img src="assets/6160.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit Mini Sparkle Motion - WLED-friendly ESP32 NeoPixel LED Driver. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/6160

### Description

The Adafruit Sparkle Motion Mini is part of our series of "Sparkle Motion" boards, that are our attempt to make the best small WLED-friendly smart LED driving board in the whole world. Our resident mermaid, firepixie makes a lot of projects with WLED and she loves it! So how can we make something that will be powerful enough to drive advanced LED projects that need a compact design?

The Mini version of the Sparkle Motion is a simpler version of our full-featured Sparkle Motion, we give up the high voltage support and built in IR receiver, in order to make it under 1 square inch in size! By using a 4-layer board and double-sided assembly we've put together this feature set:

* Power via USB Type C for up to 5V 4A input - you can use off-the-shelf USB battery packs for portable operation.
* 4 Amp resetting fuse to protect from over-current drive
* ESP32 mini module with built in antenna port - the classic ESP32 has the best WLED support even if we'd prefer the 'S2 or 'S3. Comes with 4 MB of flash, dual core 240MHz Tensilica, WiFi, Bluetooth LE and Bluetooth Classic support.
* USB-serial converter with auto-reset
* Two output signals plus 5V power and ground - both signal output are level shifted to 5V. These are on 0.1" spaced breakout pads. To keep the design slim we don't include terminal blocks pre-soldered, but we do stock the matching blocks if you want them
* Extra 2x3 0.1" breakout pads with 4 more GPIO plus 3V power and ground.
* Built-in I2S microphone
* Stemma QT I2C port to connect external sensors/OLED/etc
* User button on GPIO 0 plus Reset button
* Red built-in LED on pin 12
* Small built-in NeoPixel on pin 18 
* Separate analog/digital input JST port for analog input, potentiometer, microphone or external IR receiver on pin 13
* Compact enough you can use it for wearable projects - 1.2"x0.8" / 30mm x 20mm size with mounting holes

While we recommend it for use with WLED, it will also work just fine as a compact ESP32 board for use with Arduino, ESP-IDF, MicroPython, CircuitPython or any other ESP32 supported codebase. 

Note that unlike the classic Sparkle Motion board, we don't include terminal blocks pre-soldered to keep the board very slim. We do stock the matching blocks if you want them, a small amount of soldering is required to attach them. Also, unlike the bigger version, we dropped the on-board IR receiver - however its easy to add one by plugging in a JST SH 3-pin socket cable and slotting in an IR receiver module.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
