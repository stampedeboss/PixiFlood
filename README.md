# PixiFlood
PixiFlood LED Driver, Turn your 10W Floodlight into a WS2811 Pixel

DESCRIPTION
A LED Driver that will allow a 10W flood light to be controlled as a WS2811 Pixel. Allows up to 
170 flood lights to be controlled with a single universe. 

My goal was to enable placement of a flood light without having to deal with different controllers or 
wiring needs. By using WS2811, place a flood light at the beginning or end of a pixel string and maintain 
complete control. 

The additional wireless version allows the driver to function as its own controller and communicate 
via wireless connection using the Komby Protocol. It contains an ATMEGA328 and necessary circuitry to 
support the nRF24 and Komby Software. 

Designed for LED Modules: 
Model: 10W 
Color: RGB 
DC Forward Voltage (VF): Red 6-8V, Green 9-12V, Blue 9-12V 
DC Forward current (IF): 300MA 
Out put Lumens: Red 120-150LM, Green 200-300LM, Blue 70-100LM 
Wave Length : Red 620-625nm , Green 515-520nm, Blue
