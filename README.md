# TinyClr Library
Version: __0.10.0__

Note: If environment variable __NUGET_REPOSITORY__ is define, some project generate a Nuget package for them, and copy generated package into it.

Documentation is in progress (each file of module documentation is in project folder with MarkDown File)

***
:construction: : Work In Progress
***

## Core:
Module              | Roles       | Package                                                                                            
------------------- | ----------- | -------------------------------------------------------------------------------------------------- 
 __Application__ | Class with Initialization and loop function | Not yet
__Led__ | Class to help with test easily |
__Button__ | Class to help with test easily |
__Pins__ | Include some boards which don't appear in GHI.TinyClr.Pins | [Package](https://www.bauland.fr/Nuget/Download?Path=Bauland.Pins.0.10.0.nupkg)

## Modules:

### Adafruit

Module              | State       | Package                                                                                            | Documentation
------------------- | ----------- | -------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------
Color Sensor (1334) | __Working__ | [Package](https://www.bauland.fr/Nuget/Download?Path=Bauland.Adafruit.ColorSensor1334.0.10.0.nupkg) | [Documentation](https://github.com/bauland/TinyClrLib/blob/master/Modules/Adafruit/ColorSensor1334/ColorSensor1334.md) 

### Gadgeteer

Module           | State       | Package                                                                                              | Documentation
---------------- | ----------- | ---------------------------------------------------------------------------------------------------- | -------------
AccelG248        | __Working__ | [Package](https://www.bauland.fr/Nuget/Download?Path=Bauland.Gadgeteer.AccelG248.0.10.0.nupkg)        | [Documentation](https://github.com/bauland/TinyClrLib/blob/master/Modules/Gadgeteer/AccelG248/AccelG248.md)
Bluetooth		 | __Working__ | [Package](https://www.bauland.fr/Nuget/Download?Path=Bauland.Gadgeteer.Bluetooth.0.10.0.nupkg)        | [Documentation](https://github.com/bauland/TinyClrLib/blob/master/Modules/Gadgeteer/Bluetooth/Bluetooth.md)
Button           | __Working__ | [Package](https://www.bauland.fr/Nuget/Download?Path=Bauland.Gadgeteer.Button.0.10.0.nupkg)           | [Documentation](https://github.com/bauland/TinyClrLib/blob/master/Modules/Gadgeteer/Button/Button.md)
CharacterDisplay | __Working__ | [Package](https://www.bauland.fr/Nuget/Download?Path=Bauland.Gadgeteer.CharacterDisplay.0.10.0.nupkg) | [Documentation](https://github.com/bauland/TinyClrLib/blob/master/Modules/Gadgeteer/CharacterDisplay/CharacterDisplay.md)
DisplayN18       | __Working__ | [Package](https://www.bauland.fr/Nuget/Download?Path=Bauland.Gadgeteer.DisplayN18.0.10.0.nupkg)       | [Documentation](https://github.com/bauland/TinyClrLib/blob/master/Modules/Gadgeteer/DisplayN18/DisplayN18.md)
Gyro             | __Working__ | [Package](https://www.bauland.fr/Nuget/Download?Path=Bauland.Gadgeteer.Gyro.0.10.0.nupkg)             | [Documentation](https://github.com/bauland/TinyClrLib/blob/master/Modules/Gadgeteer/Gyro/Gyro.md)
Led7C            | __Working__ | [Package](https://www.bauland.fr/Nuget/Download?Path=Bauland.Gadgeteer.Led7C.0.10.0.nupkg)            | [Documentation](https://github.com/bauland/TinyClrLib/blob/master/Modules/Gadgeteer/Led7C/Led7C.md)
Led7R            | __Working__ | [Package](https://www.bauland.fr/Nuget/Download?Path=Bauland.Gadgeteer.Led7R.0.10.0.nupkg)            | [Documentation](https://github.com/bauland/TinyClrLib/blob/master/Modules/Gadgeteer/Led7R/Led7R.md)
LedStrip         | __Working__ | [Package](https://www.bauland.fr/Nuget/Download?Path=Bauland.Gadgeteer.LedStrip.0.10.0.nupkg)         | [Documentation](https://github.com/bauland/TinyClrLib/blob/master/Modules/Gadgeteer/LedStrip/LedStrip.md)
LightSense       | __Working__ | [Package](https://www.bauland.fr/Nuget/Download?Path=Bauland.Gadgeteer.LightSense.0.10.0.nupkg)       | [Documentation](https://github.com/bauland/TinyClrLib/blob/master/Modules/Gadgeteer/LightSense/LightSense.md)
MotorDriverL298  | __Working__ | [Package](https://www.bauland.fr/Nuget/Download?Path=Bauland.Gadgeteer.MotorDriverL298.0.10.0.nupkg)  | [Documentation](https://github.com/bauland/TinyClrLib/blob/master/Modules/Gadgeteer/MotorDriverL298/MotorDriverL298.md)
Music            | __Working__ | [Package](https://www.bauland.fr/Nuget/Download?Path=Bauland.Gadgeteer.Music.0.10.0.nupkg)            | [Documentation](https://github.com/bauland/TinyClrLib/blob/master/Modules/Gadgeteer/Music/Music.md)
Potentiometer    | __Working__ | [Package](https://www.bauland.fr/Nuget/Download?Path=Bauland.Gadgeteer.Potentiometer.0.10.0.nupkg)    | [Documentation](https://github.com/bauland/TinyClrLib/blob/master/Modules/Gadgeteer/Potentiometer/Potentiometer.md)
RotaryH1         | __Working__ | [Package](https://www.bauland.fr/Nuget/Download?Path=Bauland.Gadgeteer.RotaryH1.0.10.0.nupkg)         | [Documentation](https://github.com/bauland/TinyClrLib/blob/master/Modules/Gadgeteer/RotaryH1/RotaryH1.md)
TempHumid        | __Working__ | [Package](https://www.bauland.fr/Nuget/Download?Path=Bauland.Gadgeteer.TempHumid.0.10.0.nupkg)        | [Documentation](https://github.com/bauland/TinyClrLib/blob/master/Modules/Gadgeteer/TempHumid/TempHumid.md)
Tunes            | __Working__ | [Package](https://www.bauland.fr/Nuget/Download?Path=Bauland.Gadgeteer.Tunes.0.10.0.nupkg)            | [Documentation](https://github.com/bauland/TinyClrLib/blob/master/Modules/Gadgeteer/Tunes/Tunes.md)

### Grove

Module          | State          | Package                                                                                          | Documentation                                                                                                           | Notes
--------------- | -------------- | ------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------- | -----
Button          | __Working__    | [Package](https://www.bauland.fr/Nuget/Download?Path=Bauland.Grove.Button.0.10.0.nupkg)           | [Documentation](https://github.com/bauland/TinyClrLib/blob/master/Modules/Grove/Button/Button.md)                       | 
Buzzer          | __Working__    | [Package](https://www.bauland.fr/Nuget/Download?Path=Bauland.Grove.Buzzer.0.10.0.nupkg)           | [Documentation](https://github.com/bauland/TinyClrLib/tree/master/Modules/Grove/Buzzer/Buzzer.md)                       |
4-Digit Display | __Working__    | [Package](https://www.bauland.fr/Nuget/Download?Path=Bauland.Grove.FourDigitDisplay.0.10.0.nupkg) | [Documentation](https://github.com/bauland/TinyClrLib/blob/master/Modules/Grove/FourDigitDisplay/FourDigitDisplay.md)   |
I2C Color       | __Working__    | [Package](https://www.bauland.fr/Nuget/Download?Path=Bauland.Grove.I2cColorSensor.0.10.0.nupkg)   | [Documentation](https://github.com/bauland/TinyClrLib/blob/master/Modules/Grove/I2cColorSensor/I2cColorSensor.md)       |
LcdRgbBacklight | __Working__    | [Package](https://www.bauland.fr/Nuget/Download?Path=Bauland.Grove.LcdRgbBacklight.0.10.0.nupkg)  | [Documentation](https://github.com/bauland/TinyClrLib/blob/master/Modules/Grove/LcdRgbBacklight/LcdRgbBacklight.md)     |
LedSocket       | __Working__    | [Package](https://www.bauland.fr/Nuget/Download?Path=Bauland.Grove.Led.0.10.0.nupkg)              | [Documentation](https://github.com/bauland/TinyClrLib/blob/master/Modules/Grove/Led/Led.md)                             | from GHI
LightSensor     | __Working__    | [Package](https://www.bauland.fr/Nuget/Download?Path=Bauland.Grove.LightSensor.0.10.0.nupkg)      | [Documentation](https://github.com/bauland/TinyClrLib/blob/master/Modules/Grove/LightSensor/LightSensor.md)             | from GHI
Relay           | __Working__    | [Package](https://www.bauland.fr/Nuget/Download?Path=Bauland.Grove.Relay.0.10.0.nupkg)            | [Documentation](https://github.com/bauland/TinyClrLib/blob/master/Modules/Grove/Relay/Relay.md)                         | from GHI
Rotary Angle    | __Working__    | [Package](https://www.bauland.fr/Nuget/Download?Path=Bauland.Grove.RotaryAngleSensor.0.10.0.nupkg)| [Documentation](https://github.com/bauland/TinyClrLib/blob/master/Modules/Grove/RotaryAngleSensor/RotaryAngleSensor.md) | from GHI
Rtc             | __Working__    | [Package](https://www.bauland.fr/Nuget/Download?Path=Bauland.Grove.Rtc.0.10.0.nupkg)              | [Documentation](https://github.com/bauland/TinyClrLib/blob/master/Modules/Grove/Rtc/Rtc.md)                             |
SerialBluetooth3| __Working__    | [Package](https://www.bauland.fr/Nuget/Download?Path=Bauland.Grove.SerialBluetooth3.0.10.0.nupkg) | [Documentation](https://github.com/bauland/TinyClrLib/blob/master/Modules/Grove/SerialBluetooth3/SerialBluetooth3.md)   | 
ServoMotor      | __Working__    |                                                                                                  | Not yet                                                                                                                 | from GHI
Sound           | __Working__    | [Package](https://www.bauland.fr/Nuget/Download?Path=Bauland.Grove.SoundSensor.0.10.0.nupkg)      | [Documentation](https://github.com/bauland/TinyClrLib/blob/master/Modules/Grove/SoundSensor/SoundSensor.md)             | from GHI
Temperature     | __Working__    | [Package](https://www.bauland.fr/Nuget/Download?Path=Bauland.Grove.SoundSensor.0.10.0.nupkg)      | [Documentation](https://github.com/bauland/TinyClrLib/blob/master/Modules/Grove/TemperatureSensor/TemperatureSensor.md) | from GHI
TouchSensor     | __Working__    | [Package](https://www.bauland.fr/Nuget/Download?Path=Bauland.Grove.TemperatureSensor.0.10.0.nupkg)| [Documentation](https://github.com/bauland/TinyClrLib/blob/master/Modules/Grove/TouchSensor/TouchSensor.md)             | from GHI 
UltrasonicRanger| __Working__    | [Package](https://www.bauland.fr/Nuget/Download?Path=Bauland.Grove.UltrasonicRanger.0.10.0.nupkg) | [Documentation](https://github.com/bauland/TinyClrLib/blob/master/Modules/Grove/UltrasonicRanger/UltrasonicRanger.md)   |

### Mikro Click

Module                | State          | Package     | Documentation
--------------------- | -------------- | ----------- | -------------
Bluetooth LE P module | :construction: |             | Not yet

### Others

Module  | State       | Package                                                                                | Documentation
------- | ----------- | -------------------------------------------------------------------------------------- | -------------
HC-SR04 | __Working__ | [Package](https://www.bauland.fr/Nuget/Download?Path=Bauland.Other.HCSR04.0.10.0.nupkg) | [Documentation](https://github.com/bauland/TinyClrLib/blob/master/Modules/Others/HCSR04/HC-SR04.md)

***
:construction: : Work In Progress
***