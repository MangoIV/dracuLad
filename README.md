# dracuLad
This is a 34-36-key-board.
## Features
- 36 keys, two of them can be replaced by rotary encoders making it support 34-36 keys and 2-4 encoders. 
- bright RGB Underglow with ws2812b LEDs
- one ssd1306 OLED per side
- powered by QMK-firmware (Firmware can be found at [my fork of the qmk firmware with branch "draculad"](https://github.com/MangoIV/qmk_firmware/tree/draculad))
- aggressive pinky stagger similar to the kyria but with an alternative thumb cluster to raise comfort for large hands
- support for mx and choc switches
- files for fr4 plate and acrylic bottom plate as well as OLED window
## Some pictures to get your mouth watery
![showcase of both sides](https://github.com/mangoiv/draculad/blob/master/pictures/both_sides_showcase.jpg?raw=true)
![showcase of oled cover](https://github.com/mangoiv/draculad/blob/master/pictures/oled_cover_showcase.jpg?raw=true)
![showcase of underglow](https://github.com/mangoiv/draculad/blob/master/pictures/both_sides_underglow_oleds.jpg?raw=true)
![oled cover](https://github.com/mangoiv/draculad/blob/master/pictures/right_side_oled_cover.jpg?raw=true)
## State of the project
- first proto has been built, second and third in the works
- problems with RGB lighting that has been fixed in the upstream PCB already
- current rev has an easy fix for those issues as seen below
![rgb fix left side](https://github.com/mangoiv/draculad/blob/master/pictures/left_side_gnd_fix.jpg?raw=true)
## Plans
- update the pcb for cleaner wiring
- test pcbs with fixed rgb
- build low pro version (in progress)
## What do you need for building this
- 2 pcbs
- a bottom plate, a top plate, an OLED cover (of course they're optional, especially when buildin the choc version)
- 34-36 Switches, either choc low profile v1 or mx compatible ones
- 2-4 rotary encoders (e.g. if you choose to build with 3 rotaries, you would only need 35 switches)
- 2 pro micro compatible controllers
- 20 ws2812b LEDs (if you want underglow)
- 38 sod323 SMD diodes
- two reset switches (they're also optional, you could alway just reset with tweezers or from the firmware)
- two SSD1306 OLEDs, those are optional as well
- two TRRS jacks
- 8 0.7cm standoffs, 16 m2 screws to mount the case 
- 6 standoffs with m2 screws for the OLED cover (standoff size depends on whether you use the OLEDs or not and probably also how low profile you pro micro is mounted (bit-c for example is a bit higher profile))
- usb cable, trrs cable, rotary encoder knobs, keycaps
