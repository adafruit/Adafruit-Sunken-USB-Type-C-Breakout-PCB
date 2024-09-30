## Adafruit Sunken USB Type C Breakout Board - Downstream Connection PCB

<a href="http://www.adafruit.com/products/6050"><img src="assets/6050.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit Sunken USB Type C Breakout Board - Downstream Connection. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/6050

### Description

When you want a svelte USB C build, a 'sunken' type connector that straddles the PCBA will let you keep your build super slim. This breakout gives you all the contacts for a USB Type C connector, but lower than the classic 'horizontal' USB-C breakout and a vertical version.

USB C features a symmetric/reversible connector, more data pins, and higher current output capability. But, for most developers, the pin usage you know and love from older USB will work just fine. This breakout gives you all the basics you need and a resistor configuration that mimics classic USB 2.0 for a downstream connection

The two 5.1K resistors on the CC pins indicate to the upstream port to provide 5V and up to 1.5A (whether the upstream can supply that much current depends on what you're connecting to.

For most usages, you can connect VBUS to your 5V input, GND to ground, and D+ and D- as you expect. You can monitor the CC and SBU pins to determine cable polarity or send side-band data. Or leave them disconnected.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
