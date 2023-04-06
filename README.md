# FurTech

These are the files for a fursuit I am planning on making. I wanted eye displays for more expression, but then realized I cant see through the displays, Stereo cameras and an AR headset will be used for vision. The cameras will be hidden in the eyebrows. The jetson nano will handle stereo correction and managing the various sensors and servos. Once I have the hardware needed I will begin working on software. Base features are vision and ears reacting to sound. Then eye tracking using the cameras and opencv.

## Goals

* Eye Displays
* Ears which react to motion and environment
* Moving mouth to my voice
* Headpat detection and reactions
* Active cooling fan
* Stereo forward cameras
* AR/VR display for vision
* Eye Tracking (Vision or internal camera)
* No spaghetti 

## Hardware Features

Sensors connect over I2C

### Power Supply

* USB PD in @8-20V
* 3 5V 5A Linear Regulators
* Current Monitoring over I2C

### Sensors

* I2C Multiplexor
* Temperature Sensor
* 9-Axis IMU
* 5 Touch Sensors
* Cooling fan for comfort

### Ear Breakout

* Servo power switch
* i2C PWM Driver
* Mic/ADC input

### Display Driver

* 2 Display Connections
* Single output connection

### jetson Nano Breakout

* I2C In
* Display SPI in
* Power in

## Other Hardware

* Nvidia Jetson Nano
* Nreal Air
* Stereo Cameras 1080P@60
* Usb PD battery
* 2x MatrixOrbital EVE3/4 displays
