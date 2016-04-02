<p align="center">
  <img width=420 src="https://pbs.twimg.com/media/Ce-ti2uUAAAjRpa.jpg:large">
</p>

#plantokei
:sparkles: :floppy_disk: :herb: plants + arduino = moyashi + tamagotchi :herb: :floppy_disk:

Plantokei is a golem made up of:
- An [Arduino Uno](https://www.arduino.cc/en/Main/ArduinoBoardUno)
- A [SainSmart ST7735](http://www.sainsmart.com/sainsmart-1-8-spi-lcd-module-with-microsd-led-backlight-for-arduino-mega-atmel-atmega.html) LCD
- A simple [photocell](https://learn.adafruit.com/photocells/overview)
- A plant! :3

## Developing
### Easy Mode
The easiest way to get going with Plantokei is to load up `plantokei.ino` in the
[Arduino IDE](https://www.arduino.cc/en/Main/Software). You'll need to download
the two libraries for the LCD screen, `Adafruit_GFX.zip` and `Adafruit_ST3775.zip`, available in [this helpful tutorial](http://www.tweaking4all.com/hardware/arduino/sainsmart-arduino-color-display/) along with instructions to install said libraries.

### Slightly-Less-Easy Mode
If you're like me and you value text editor shortcuts over your own happiness,
then congratulations! You can build and upload the plantokei source yourself.
(Note that I am actively working on making this process suck less... in the meantime, sorry!)

NOTE: plantokei's build process depends on the excellent Arduino-Makefile project. If you're on a system other than OS X or if these instructions don't work out of the box, check out the similarly great [Bare Arduino Project](https://github.com/ladislas/Bare-Arduino-Project) for instructions on setting up Arduino-Makefile for other systems like Linux and Windows.

1. After cloning the plantokei repo, install the git submodules. This includes the Arduino-Makefile dependency, as well as all of the Arduino libraries: `git submodule init && git submodule update`

1.