# esphome-for-deye (Pi Pico)


Made for Deye SUN-12K-SG04LP3 and other compatible inverters such as the SUN-5/6/8/10/-SG04LP3.

This is a fork of [Klatremis's esphome setup](https://github.com/klatremis/esphome-for-deye). This has been adapted for the Raspberry Pi Pico.

The build is based on a common buck converter, a TTL <-> RS485 with flowcontrol and a Pi Pico.

The Pi Pico can be powered from CN2 pin 7&8 with 12V. The buck converter will downshift this to the 5v required for the Pi Pico

Some of the inverter data exposed to Home Assistant:

* Status
* Time of charge
* Battery information (charge current, discharge current, state of charge)
* Temperature
* Grid frequency
* and many more.

Full credit goes to Klatremis for his work on the original esp32 setup.

IMPORTANT: This config file has not yet been tested in production. It may not work

Included is the Time card from Klatremis:

![image](https://user-images.githubusercontent.com/22115157/211201343-1d54cada-4b2c-40b0-88c4-faf31e17fead.png)

