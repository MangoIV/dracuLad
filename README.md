# dracuLad
This is a 34-36-key-board.
## Features
- 36 keys, two of them can be replaced by rotary encoders making it support 34-36 keys and 2-4 encoders. 
- bright RGB Underglow with ws2812b LEDs
- one ssd1306 OLED per side
- powered by QMK-firmware (Firmware can be find at [my fork of the qmk firmware with branch "draculad"](https://github.com/MangoIV/qmk_firmware/tree/draculad))
- aggressive pinky stagger similar to the kyria but with an alternative thumb cluster to raise comfort large hands
- support for mx and choc switches
- files for fr4 plate and acrylic bottom plate as well as OLED window
## State of the project
- first proto has been built, second and third in the works
- problems with RGB lighting that has been fixed in the upstream PCB already
- current rev has an easy fix for those issues as seen below
![rgb fix left side](https://github.com/mangoiv/draculad/blob/master/pictures/left_side_gnd_fix.jpg?raw=true)
## Plans
- update the pcb for cleaner wiring
- test pcbs with fixed rgb
- build low pro version (in progress)
