# Flipper servotester application

![Servo tester application screenshot](servotester/assets/Servo_Tester_Manual_mode.png)

This application could be used for testing devices containing standard [RC servo](https://en.wikipedia.org/wiki/Servo_(radio_control)), by generating a [PWM RC servo signal](https://en.wikipedia.org/wiki/Servo_control). 

## Installation instructions

Please install the application from [Flipper Zero application catalog](https://docs.flipper.net/apps), or go to the releases, download apps.zip, and extract it to your SD card.

## Usage

- Connect the Servo PWM input to **A7** Flipper Zero in.
- Enable 5V output in the GPIO menu or plug-in USB-C charging cable. (If you're supplying power from an external power source, make sure it has common ground with the flipper GND)
- Start the Servo Tester app
- Move servo required positions using controls bellow

## Controls

| Button | Action                       |
| :----- | :--------------------------- |
| 🔼     | Up button increases pulse width by 10 us.|
| 🔽     | The down button decreases pulse width by 10 us.   |
| ◀️     | Left button decreases pulse width by 1 us.   |
| ▶️     | The right button increases pulse width by 1 us.  |
| ↩️     | Back button exit application.   |
| 🔵     | Center button change mode. |

## Build instructions

Install [uFBT - micro Flipper Build Tool](https://github.com/flipperdevices/flipperzero-ufbt) to get a toolkit for building flipper zero applications. 

- Clone this git repository
- cd to *ServoTesterApp* content.
- run *ufbt && ufbt launch* with flipper connected. It automatically installs the compiled application into Flipper Zero.

