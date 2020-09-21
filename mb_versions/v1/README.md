# Main Board v1
This is the first version of the Main Board PCB for the sensor display.

## Changes from v0
* Moved to EasyEDA to get parts designed by LCSC
* Replaced the CP2104 with the CH304N / CH303N since it's a cheaper USB to Serial Converter in an SOP8 package that is easier to solder.
* Replaced the USB C with a Micro USB for simplicity.
* Added the BSS138 transistor as a level shifter to shift the 5V I2C line to 3.3V.
* Reorganized the components on the schematic to make it easier to follow how everything is connected.
* Added a header to expose the I2C and Power pins for the external sensor module.
* Added test points to expose the power pins and I2C line for debugging.

## Top View
![alt text][topview]

## Bottom View
![alt text][bottomview]

[topview]: https://github.com/yilverdeja/sensordisplay/blob/master/mb_versions/v1/SD_v1_topview.JPG "Main Board v1 Top View"
[bottomview]: https://github.com/yilverdeja/sensordisplay/blob/master/mb_versions/v1/SD_v1_bottomview.JPG "Main Board v1 Bottom View"
