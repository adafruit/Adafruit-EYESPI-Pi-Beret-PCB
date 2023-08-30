## Adafruit EYESPI Pi Beret PCB

<a href="http://www.adafruit.com/products/5783"><img src="assets/5783.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit EYESPI Pi Beret. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/5783

### Description

Raspberry Pi's make for handy lil computers, but they're really wonderful when you can connect all sorts of nifty hardware to them: color TFT or E-Ink displays, and sensors are our go-to favorites. Even better is when we make it fast and effortless to wire these up. With this new EYESPI Pi Beret there's no more counting pins or noodling with a breakout board. This slim HAT plugs in and gives you lots of hardware connection options so that many projects become plug-and-play.

Our most recent display breakouts have come with a new feature: an 18-pin "EYE SPI" standard FPC connector with flip-top connector. This is intended to be a sort-of "STEMMA QT for displays" - a way to quickly connect and extend display wiring that uses a lot of SPI pins. In this case we need a lot of SPI and accessory pins, and we want to be able to use long distances, so we go with an 18-pin 0.5mm pitch FPC.

With such a slim and flexible cable, it's easy to have displays anywhere without them physically attached to the Pi like in our PiTFTs. Accessorize with big bold colorful displays or power-sipping E-Ink. 

Don't forget you'll also want an 18-pin EYESPI FPC cable. And of course one of our EYESPI displays too - look for the EYESPI logo on the back to know you've got one that can clip in.

* MOSI/MISO/SCK SPI pins are connected to the default SPI port on the Raspberry Pi
* SDA/SCL I2C pins are connected to the default I2C port on the Pi
* Display CS on Raspberry Pi CE 0
* Display DC on Raspberry Pi GPIO #25
* Display Reset on Raspberry Pi GPIO #27
* Display Busy on Raspberry Pi GPIO #17 (used for E-Inks)
* Display Backlight on Raspberry Pi GPIO #18 (there's a jumper to cut/disable this if you want to use the PWM output for other uses like NeoPixels)
* Touch CS on Raspberry Pi CE 1
* Touch IRQ on Raspberry Pi GPIO #24

The remaining EYESPI pins are not connected, leaving you with plenty of GPIO for other accessory boards.

We also have a Stemma QT connector for the I2C port, to make connecting all sorts of Qwiic/Stemma QT devices super easy, two tactile switches on GPIO #5 and #6 and a slide switch on GPIO #13 which you can use for any sort of interface project or configuration.

Display and EYESPI cable are not included.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
