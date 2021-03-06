# ESP8266 Library for Eagle PCB CAD

Tangent: Espressif makes the ESP8266 chip.  AI Thinker has created a series of very popular
modules based on the ESP8266, the most popular of these is the ESP-12, which is commonly
called ESP8266-12.

This library is centered around the AI Thinker modules and popular related modules.  It
currently contains the following modules:
- ESP-12F - based on the datasheet specs, it is probably compatible with prior versions
  of the module, but I didn't make the effort to determine this.
    - The default symbol / package / device that includes all 22 pins.
    - An alternate symbol / package / device that includes only the main 16 pins.  This is
      likely more compatible with earlier versions of ESP8266-12 which don't have pads
      along the bottom edge.
    - Important detail: This package defines the pad numbers with the bottom edge being
      17-22, as shown in the datasheet.  Many other references number them as 9-14,
      which is how they were numbered for earlier versions.  This shouldn't matter when
      using Eagle, as the signal names are mapped properly from the schematic symbol.
    - Datasheet is at <http://wiki.ai-thinker.com/_media/esp8266/a014ps01.pdf>

Future devices might include:
- Wemos D1 Mini - based on the ESP-12, but with pin headers on 0.1" spacing, as well as a
  USB serial interface and power regulator.
- ESP-12 adapter plate - a simple PCB that adapts the 2.0mm pad spacing to 0.1" pin
  headers for breadboard work.

## For questions or defects

Please open an issue here: <https://github.com/RichardFoo/ESP8266-Eagle/issues>

## Use at your own risk.  
