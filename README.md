# OPEnS-Lab-Sapflow
This is the final version of the code for a project I worked on at Oregon State's OPEnS Lab

Below is the Bill of materials required to assemble this project:

*  [Bill of Materials](https://osf.io/3kgcm/)

For using this code, the following libraries must be installed:

## Libraries

- [SdFat](https://github.com/greiman/SdFat "SdFat")
- [OPEnS RTC](https://github.com/OPEnSLab-OSU/OPEnS_RTC "OPEnS_RTC")
- [Low-Power](https://github.com/rocketscream/Low-Power "Low-Power")
- [Protothreads](https://github.com/P4SSER8Y/ProtoThreadsForArduino)
- [DSPlite](https://github.com/kamocat/DSPlite)
- [RadioHead](https://github.com/adafruit/RadioHead)
- [ArduinoJSON](https://github.com/bblanchon/ArduinoJson)
- [FeatherFault](https://github.com/OPEnSLab-OSU/FeatherFault)
- [ASF core](https://github.com/adafruit/Adafruit_ASFcore.git) commit f6ffa8b
- [Plog](https://github.com/OPEnSLab-OSU/plog)

## Using Code

For flashing the Arduino code, open the sapflow_protothread folder and open the sapflow_protothread.ino file.
When the IDE opens, verify that the Adafruit Feather M0 Microcontroller is connected to a COM port.
At this point the upload can begin.


Further Instructions for hardware assembly, connections, and operation can be seen in the Hardwarex article

## Other Files

The Development only folder contains code that was used for the base station in a past implementation of the hardware (seen in the Feather9x_RX subfolder).
The Development only folder also contains the mcp3424_code subfolder which contains code that helped in the development of reading ADC values in the hardware setup.
