# esphome-for-deye (Pi Pico)

IMPORTANT: IS NOT YET READY!. DO NOT USE

Made for Deye SUN-12K-SG04LP3 and other compatible inverters such as the SUN-5/6/8/10/-SG04LP3.

This is a fork of Klatremis's esphome setup. This has been adapted for the Raspberry Pi Pico.

The build is based on a common buck converter, a TTL <-> RS485 with flowcontrol and a Pi Pico.

For use with ESP32 & TTL To RS485 Module with automatic flow control.
I powered the esp32 from CN2 pin 7&8 with 12V into a USB converter.

This include all addresses i could see relevant from the inverter. 
Including Changing time of use, Charge/discharge amps etc.

The battery input is commited out as im having a separate rs485 reader for that.

![esp32 rs485_bb](https://user-images.githubusercontent.com/22115157/211201233-f5fe9189-e6b3-4ee1-9baa-48068f078127.jpg)

![image](https://user-images.githubusercontent.com/22115157/211201343-1d54cada-4b2c-40b0-88c4-faf31e17fead.png)

