# PixiFlood
PixiFlood LED Driver, Turn a 10w-100w floodlight Housing into a WS2811 Floodlight Pixel

DESCRIPTION:

A LED Driver that will allow a flood light to be controlled as a WS2811 Pixel. Allows up to 
170 flood lights to be controlled with a single universe. 

My goal was to enable placement of a flood light without having to deal with different controllers or 
wiring needs. By using WS2811, place a flood light at the beginning or end of a pixel string and maintain 
complete control. 

Version 2 and Version 3 introduced the concept of a built in ESPixelStick, which allows wireless connectitivy to communicate with the Floodlight.

Version 3:
Focused on delivering a single board designed to support any wattage of LED from 10w to 100w.
This objective required the design to no longer include direct attachment of the LED to the PCB, it is to 
be connected via wires to allow for the wide arrangement of LED sizes and pin spacings.

The previous designs relied on linear voltage regulators since the voltage reduction was acceptable going 
from 12v to 5v.  With the use of higher wattage LEDs, voltage requirements are much greater required changing
the 5v voltage regulator circuitry to a switching model to eliminate the overheating of the previous design.

The PT4115 specifications are unacceptable to anything above a 20w LED, as such beginning with 3.0 the LED
Driver is being switched out for an AL8862 and the supporting components have been modified to support that
new IC.

This new design includes the addition of a sidecar that contains ESPixelStick capabilities.  Using the sidecar
and an ESP-01 the floodlight can be driven wirelessly.
