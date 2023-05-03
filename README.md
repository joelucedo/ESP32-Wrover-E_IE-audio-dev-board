# ESP32-Wrover-E_IE-audio-dev-board

I designed this board to play with FAUST sound synthesis language.

Documentation about FAUST and ESP32  : https://faustdoc.grame.fr/tutorials/esp32/ - https://faust.grame.fr/

## Specs and features

* ESP32-WROVER-IE-N16R8 (64Mbit PSRAM - 16 MB SPI flash)
* Audio codec : WM8978 (differential mic inputs - line in - aux - line out - speaker out - headphone)
* MIDI support : in, out, thru
* 16x IO multiplexer
* Micro sd socket

## Drivers and libraries
Tested with ~~ESP-IDF~~ ESP32 Arduino core. 

* MIDI  : https://github.com/FortySevenEffects/arduino_midi_library
* MUX   : https://github.com/waspinator/CD74HC4067
* SD    : https://github.com/espressif/arduino-esp32/tree/master/libraries/SD 
* CODEC : https://faustdoc.grame.fr/tutorials/esp32/

