# Espressif ESP8266 Library for Eagle PCB CAD

This library currently contains the following Espressif modules:
- ESP8266-12F - based on the datasheet specs, it is probably compatible with prior versions
  of the module, but I didn't make the effort to determine this.
    - The default symbol / package / device include all 22 pins.
    - An alternate symbol / package / device that includes the main 16 pins.  This is
      likely more compatible with earlier versions of ESP8266-12 which don't have pads
      along the bottom edge.

Future devices might include:
- Wemos D1 Mini - based on the ESP8266-12, but with pin headers on 0.1" spacing.
- ESP8266 Adapter plate - a simple PCB hat adapts the 2.0mm pad spacing to an 0.1" pin
  header for breadboard work.

## For questions or defects

Please open an issue here: <https://github.com/RichardFoo/ESP8266-Eagle/issues>
