# CatFeeder-Hardware

The control board for the Cat Feeder project.  For completion you will need both
[CatFeeder Firmware](https://github.com/ifreislich/CatFeeder-Firmware)
and
[Catfeeder Enclosure](https://github.com/ifreislich/CatFeeder-3D-Model).

![CatFeeder-Hardware](https://github.com/ifreislich/CatFeeder-Hardware/blob/main/images/catfeeder-front.png)

## Wiring
J3 RFID - Wire from HID 5365EGP00 or similar 
Pin|Signal|Wire
---|------|------
1|+12V|Red
2|Data 1|White
3|Data 0|Green
4|GND|Black

J5 Scale - Connection to the Load Cell
Pin|Wire
---|----
1|Black
2|Red
3|Green
4|White

J6 Auger - Nema17 20mm stepper motor
Pin|Signal|Wire
---|------|----
1|2B|Black
2|2A|Green
3|1A|Red
4|1B|Blue

J7 Door - 28BYJ-48 Stepper motor
Pin|Signal|Wire
---|------|----
1|2B|Blue
2|2A|Yellow
3|1A|Pink
4|1B|Orange
