# Home Assistant Add-on: Fan Controller

Fan Controller for Home Assistant.

![Supports aarch64 Architecture][aarch64-shield] ![Supports amd64 Architecture][amd64-shield] ![Supports armv7 Architecture][armv7-shield]

## About

You can use this add-on to install fan controller, which is a tool to control your RPi cooling system.


[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg

[test]: images/raspberry_pi_fan_controller_schematic.svg

## Hardware

* Raspberry Pi
* Fan 5V
* Transistor 

## Mount the fan
Mount the fan according to the scheme: 
![Screenshot](https://github.com/nokunev/FanCotroller/blob/master/images/raspberry_pi_fan_controller_schematic.png)

## Configuration
At the addon configuration tab please specify:
* GPIO pin number according to the scheme:
![Screenshot](https://github.com/nokunev/FanCotroller/blob/master/images/GPIO_Pinout_Diagram.png)
* Temperature at which the fan turns on
* Temperature at which the fan turns off
