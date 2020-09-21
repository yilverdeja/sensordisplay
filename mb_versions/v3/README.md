# Main Board v3
This is the third version of the Main Board PCB for the sensor display.

## Changes from v2
* Female Header was changed to a 2x6 to expose SPI pins (SCK, MOSI, MISO) and RESET to be able to burn the Arduino Bootloader onto the ATMEGA2560.
* The USB was replaced to avoid clearance errors from the footprint that was being previously
* The button was not available on LCSC, therefore it was changed to one that was in stock.
* The LED was changed to have a forward voltage of 2.2V and the LED resistor values were changed to obtain the forward current of 20mA.
* The copper ground area was fixed. 

## Top View
![alt text][topview]

## Bottom View
![alt text][bottomview]

[topview]: https://github.com/yilverdeja/sensordisplay/blob/master/mb_versions/v3/SD_v3_topview.JPG "Main Board v3 Top View"
[bottomview]: https://github.com/yilverdeja/sensordisplay/blob/master/mb_versions/v3/SD_v3_bottomview.JPG "Main Board v3 Bottom View"
