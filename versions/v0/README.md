# Sensor Display V0
Main ICs
1. MCU: ATMega2560
2. USB to Serial: CP2104
3. 3.3V LDO: AP2112

Problems:
1. CP2104 uses a QFN package making it hard to solder.
2. USB C is overkill.
3. Most sensors run at 3.3V, therefore most can't work with a 5V I2C.

Solutions
1. CH304N / CH303N are cheap USB to Serial converters with SOP-8 packages
2. Go with a micro USB for simplicity
3. Use a level shifter to shift from 5V to 3.3V. Use the BSS138 transistor.
