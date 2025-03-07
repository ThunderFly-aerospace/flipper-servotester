# Flipper servotester application

This application could be used for testing devices containing standard [RC servo](https://en.wikipedia.org/wiki/Servo_(radio_control)), by generating a [PWM RC servo signal](https://en.wikipedia.org/wiki/Servo_control). 

## Installation instructions

Install application from [Flipper Zero application catalog](https://docs.flipper.net/apps), or go to the releases, download apps.zip and extract it in your SD card.

## Usage

- Connect the Servo PWM input to **A7** Flipper Zero in.
- Enable 5V output in the GPIO menu or plug-in USB-C charging cable. (If you're supplying power from an external power source, make sure it has common ground with the flipper GND)
- Start the ServoTester app
- Test different servo positions

## Build instructions

- Clone the [official flipper zero firmware](https://github.com/flipperdevices/flipperzero-firmware)
- Add the content of this repo to the `applications_user` folder
- Follow [official instructions](https://github.com/flipperdevices/flipperzero-firmware/blob/dev/documentation/AppsOnSDCard.md)
