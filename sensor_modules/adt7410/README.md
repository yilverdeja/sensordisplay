# ADT7410 Sensor Module
An add-on PCB that allows for temperature detection via i2c using the ADT7410 Temperature Sensor.

## Top View
![alt text][topview]

## Bottom View
![alt text][bottomview]

[topview]: https://github.com/yilverdeja/sensordisplay/blob/master/sensor_modules/adt7410/TSM_v1_topview.JPG "ADT7410 PCB I2C Top View"
[bottomview]: https://github.com/yilverdeja/sensordisplay/blob/master/sensor_modules/adt7410/TSM_v1_bottomview.JPG "ADT7410 PCB I2C Bottom View"

## Improvements
To improve this board, the following can be done:
* Remove extra 2 pins (from sensor board and main board since there are only 4 pins available).
* The ADT7410 has 4 different I2C addresses by changing the values for A0 and A1. Make it possible to configure a boards i2c address by using jumpers or soldering certain pads together.
