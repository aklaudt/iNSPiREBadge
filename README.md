# DigiGirlz Badge
This is a simple electronic name badge designed by Omnitech Inc for the Microsoft DigiGirlz 2020 event in Sioux Falls South Dakota. The board is based on an Atmel 328p microcontroller, and has a 128x64 oled display, powered by a CR2032 battery.

![Badge Layout](https://delgrossoengineering.com/images/digigirlz/badgeBoard.png)

## Requirements
* This repository [Download Here](https://github.com/ad3154/DigiGirlzBadge/archive/master.zip)
* DigiGirlz Badge
* USBTinyISP Programmer
* USBTinyISP Driver [Download](https://github.com/adafruit/Adafruit_Windows_Drivers/releases/download/2.4.0.0/adafruit_drivers_2.4.0.0.exe)
* Arduino IDE
* Adafruit SSD1306 Library [How to install libraries](https://www.arduino.cc/en/guide/libraries)
* Low-Power Library [How to install libraries](https://www.arduino.cc/en/guide/libraries)
* (optional) CR2032 Battery
* (optional) [LCD Assistant](http://en.radzio.dxp.pl/bitmap_converter/)

## Instructions
* Install all of the software listed above, including Arduino and the driver.
* Install the arduino libraries. See [Here for instructions](https://www.arduino.cc/en/guide/libraries)
* Plug the programmer into your computer via the included USB cable.
* Connect your badge to the programmer using the included 6 pin ribbon cable.
* The badge will power on if connected properly. If it does not, you may need to reverse the ribbon cable.
* Open either of the example .ino files in the Arduino IDE. 
* Edit the code if you wish
* Click "Sketch" -> "Upload Using Programmer". This may take some time. Do not unplug the badge.
* Once the upload is complete, your code will run, and the screen will change.
* See the powerpoint presentation in the repository for more detailed instructions.

## More Information
You can learn more about DigiGirlz [from Microsoft's website](https://www.microsoft.com/en-us/diversity/programs/digigirlz/default.aspx), and you can learn more about Omnitech [here](https://www.omnitech-inc.com).

My personal website: https://delgrossoengineering.com
