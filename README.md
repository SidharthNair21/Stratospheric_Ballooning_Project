_In collaboration with [Nishanth Kavuru](https://github.com/CptnSapphire246/CSE-1012-Stratospheric-Ballooning-Team-LeBalloon-Flight-Code)_

Before uploading the code, ensure that the PICOLO flight computer has been properly set up. Refer to _LeBalloon_Information.md_.

Note that only two folders are needed to run the PICOLO flight code: _Libraries_ and _PICOLOv1_; _ESC_Controller_ and _TestStand_Thrust_ are not required however, they have been included to provide further information on how the propeller and the test stand function independently. _PICOLOv1_ has been included directly, but the libraries are not. These include:
- [SparkFun u-blox GNSS Arduino Library](https://github.com/sparkfun/SparkFun_u-blox_GNSS_Arduino_Library)
- [SparkFun u-blox Arduino Library](https://github.com/sparkfun/SparkFun_Ublox_Arduino_Library)
- [SD](https://github.com/arduino-libraries/SD)
- [MS5611_Arduino_Library](https://github.com/RobTillaart/MS5611)
- [Adafruit_VEML7700_Library](https://github.com/adafruit/Adafruit_VEML7700)
- [Adafruit_Unified_Sensor](https://github.com/adafruit/Adafruit_Sensor)
- [Adafruit_SSD1306](https://github.com/adafruit/Adafruit_SSD1306)
- [Adafruit_LTR329_and_LTR303](https://github.com/adafruit/Adafruit_LTR329_LTR303)
- [Adafruit_HX711](https://github.com/adafruit/Adafruit_HX711)
- [Adafruit_GFX_Library](https://github.com/adafruit/Adafruit-GFX-Library)
- [Adafruit_BusIO](https://github.com/adafruit/Adafruit_BusIO)
- [Adafruit_BNO055](https://github.com/adafruit/Adafruit_BNO055)



_PICOLOv1_ contains the main code used during the flight and ground testing including _PICOLOv1.ino_ which is the key player in the flight code. _Libraries_ contains all the necessary libraries that are needed to be installed for the flight code to function properly. Both folders should be placed in an 'Arduino' folder or which ever folder is being used to store all .ino files on the machine.

Branch A and B contaian two unique versions of the flight code from launch day, refer to the commit histories of _PICOLOv1.ino_ in each branch for more details.

Once the folders have been downloaded and the flight computer has been assembled accordingly, open up the flight code (_PICOLOv1.ino_), connect the PICOLO to the machine using a USB cable, and flash the code. A start-up message should appear on the serial monitor.
