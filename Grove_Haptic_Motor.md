# Grove - Haptic Motor
----------
## Introduction ##

Take me to [Specification](#Specification)



![Grove - Haptic Motor](http://www.seeedstudio.com/wiki/images/thumb/e/e3/Grove_Haptic_Motor.jpg/500px-Grove_Haptic_Motor.jpg)

**Grove - Haptic motor** is a grove module integrated with [**DRV2605L**](http://www.ti.com/product/DRV2605L) which will give your project more feelings. This motor is specially designed for various effects, such as ramping the vibration level up and down, for wearables and other IoT devices. Right now we have developed an easy-to-use library which simulate 123 kinds in total of vibrating modes and this will make your prototyping quicker. Also, you can develop more advanced functions with driver DRV2605L which will improve actuator performance in terms of acceleration consistency, start time, and break time and is accessible through a shared I2C compatible bus or PWM input signal.

[![enter image description here](http://www.seeedstudio.com/wiki/images/thumb/d/d0/Get_One_Now_Banner.png/150px-Get_One_Now_Banner.png)](http://www.seeedstudio.com/depot/Breakout-for-LinkIt-Smart-7688-v20-p-2641.html)

## Features ##

- More vibration effects.
- Quicken your project prototyping process.
- Easy-to-use library with 123 kinds of vibrating modes.
- Powerful driver to implanting more advanced functions.

##<a name="Specification"></a>Specification

| 123 | 21321 |
| ---- /------- /
| 123 | 21321 |

|Product reversion | Release date |Support status |Notes                  |
|------------------/--------------/---------------/-------------------|
|Version 1.0       |November 2015 |Supported      | None                  |
|Version 2.0       |April 2016    |Supported      | Refer to New Features |


## Application ideas ##

- Mobile phone, tablets.
- wearable devices.
- Remote controls, touch-enabled devices.
- Industrial human-machine interfaces.

## Hardware Overview ##

![Grove - Haptic Motor_front](http://www.seeedstudio.com/wiki/images/e/e3/Grove_Haptic_Motor.jpg)
![Grove - Haptic Motor_back](http://www.seeedstudio.com/wiki/images/b/b5/Grove_Haptic_Motor_back.jpg)


## Getting started ##

!!!Note
     This section only shows you how to build a basic development environment. You can build a development environment for your project with following guides:

### Build IDE ###

Refer to following guides to building an appropriate IDE:

- [**Getting Started on Windows**](http://www.seeedstudio.com/wiki/Seeeduino_v4.2#Getting_Started_on_Windows)
- [**Getting Started on Mac OS X**](http://www.seeedstudio.com/wiki/Seeeduino_v4.2#Getting_Started_on_Mac_OS_X)

!!!Note
     Arduino board will also be fine if you happen to have no Seeeduino board because [**Seeeduino**](http://www.seeedstudio.com/wiki/Seeeduino_v4.2) is compatible with Arduino.

### Hardware connection ###

!!!Note
    
-  Make sure you have built a development environment successful through previous steps.
-  Make sure your board has selected Arduino Uno and COM port right chosen. Connect to I2C interface on Seeeduino board and Haptic motor with grove wire.

![Hardware connection](http://www.seeedstudio.com/wiki/images/9/9c/Grove_haptic_motor_connection.jpg)

### Download sample code ###

1. You can download [**sample code**](https://github.com/Seeed-Studio/Grove_Haptic_Motor) and library or header files.
1. Click a button named **"Download Zip"** at **[Github](https://github.com/Seeed-Studio/Grove_Haptic_Motor)**.
1. Decompress the downloaded ZIP file.
1. Remove the "-master" twice in decompressed file name.
1. Copy the folder ***Grove_Haptic_Motor*** into your library folder (In default, it is same with Sketchbook Location which can be found by clicking **File > Preference**).Under Windows, it will likely be called "**My Documents\Arduino\libraries**". 
!!!Note 
    For Mac users, it will likely be called "Documents/Arduino/libraries". On Linux, it will be the "libraries" folder in your sketchbook.
1. Copy file **drv2605.cpp** and file **drv2605.h** to its parent directory.

### Load sample code ###
!!!Note
    In this case we use **[Seeeduino 4.2](http://www.seeedstudio.com/wiki/Seeeduino_v4.2)** as experiment board which is a compatible board with Arduino.
!!!Tips
    You can use **[Base shield v2](http://www.seeedstudio.com/wiki/Grove_-_Base_shield_v2)** as expansion board which will make your connection of modules simple.
!!!Note 