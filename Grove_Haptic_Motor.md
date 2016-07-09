# Grove - Haptic Motor
----------
## Introduction ##

![Grove - Haptic Motor](http://www.seeedstudio.com/wiki/images/thumb/e/e3/Grove_Haptic_Motor.jpg/500px-Grove_Haptic_Motor.jpg)

**Grove - Haptic motor** is a grove module integrated with [**DRV2605L**](http://www.ti.com/product/DRV2605L) which will give your project more feelings. This motor is specially designed for various effects, such as ramping the vibration level up and down, for wearables and other IoT devices. Right now we have developed an easy-to-use library which simulates 123 kinds in total of vibrating modes and this will make your prototyping quicker. Also, you can develop more advanced functions with driver DRV2605L which will improve actuator performance in terms of acceleration consistency, start time, and break time and is accessible through a shared I2C compatible bus or PWM input signal.

[![enter image description here](http://www.seeedstudio.com/wiki/images/thumb/d/d0/Get_One_Now_Banner.png/150px-Get_One_Now_Banner.png)](https://www.seeedstudio.com/item_detail.html?p_id=2546)

## Features ##

- More vibration effects.
- Quicken your project prototyping process.
- Easy-to-use library with 123 kinds of vibrating modes.
- Powerful driver to implanting more advanced functions.

## Specification ##
--- | --- 
--- | --- 
**Operating voltage**   |   3.3~5.0 V
**Ripples (at maximum power)**   |   50~100 mV
**Max power**   |   750 mW
**I2C speed**   |   100 kHz
**Vibration effects**   |   123 types
**Driver**   |   DRV2605L
**Port**   |   I2C
**Default I2C Address**   |   0x5A

## Application ideas ##

- Mobile phone, tablets.
- wearable devices.
- Remote controls, touch-enabled devices.
- Industrial human-machine interfaces.

## Hardware Overview ##

![](https://raw.githubusercontent.com/SeeedDocument/Grove_Haptic_Motor/master/image/board.png)


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
    Never touch driver DRV2605L which may cause damage to it while it get power connected.
![Grove Haptic Motor cautions](http://www.seeedstudio.com/wiki/images/b/b7/Grove_Haptic_Motor_cautions.png)

1. Make sure haptic motor and main control board well connected.
2. Load your sample code drv2605.ino under example file of decompressed file.
1. Flash your code to your main control board by click Project>Upload(CTRL+U).
1. After uploading, you now get haptic motor vibrate at a smooth style.

## Resources ##

- Schematic files in **[Eagle format](http://www.seeedstudio.com/wiki/images/9/90/Grove_Haptic_Motor_v0.9_Eagle.zip)** and **[PDF format](http://www.seeedstudio.com/wiki/images/c/cc/Grove_Haptic_Motor_v0.9_SCH.pdf)**.
- More about drive circuit **[DRV2605L](http://www.ti.com/product/DRV2605L)**.
- **[Git repository](https://github.com/Seeed-Studio/Grove_Haptic_Motor)**

##Is this page helpful?
<iframe style="height: 600px; width: 500px; margin: 10px 0 10px;" allowTransparency="true" src="https://www.surveymonkey.com/r/MFQSJ6F" frameborder="0"></iframe>