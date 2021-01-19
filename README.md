# dracuLad
This is a 34-36-key-board.
## Features
- 36 keys, two of them can be replaced by rotary encoders making it support 34-36 keys and 2-4 encoders. 
- bright RGB Underglow with ws2812b LEDs
- one ssd1306 OLED per side
- support for the [pimoroni trackball](https://shop.pimoroni.com/products/trackball-breakout)
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
- PCBs are fully working (OLED, LEDs, all switches, encoders, Trackball)
- acrylic plates are ordered and soon to be tested
- for the upper encoder you can't use the really big guitar knobs as they're to wide and will interfere with the OLEDs. The smaller ones are recommended
## What do you need for building this
- 2x pcbs
- 2x bottom plate, 2x top plate, 2x OLED cover (of course they're optional, especially when building the choc version)
- 34-36 Switches, either choc low profile v1 or mx compatible ones
- 2-4 rotary encoders (e.g. if you choose to build with 3 rotaries, you would only need 35 switches)
- 2x pro micro compatible controllers
- 20x ws2812b LEDs (if you want underglow)
- 38x sod123 SMD diodes
- 2x reset switches (they're also optional, you could alway just reset with tweezers or from the firmware)
- 2x SSD1306 OLEDs, those are optional as well
- 1x pimoroni trackball (optional)
- 2x TRRS jacks
- 8x 0.7cm standoffs, 16 m2 screws to mount the case 
- 6x standoffs with m2 screws for the OLED cover (standoff size depends on whether you use the OLEDs or not and probably also how low profile your pro micro is mounted (bit-c for example is a bit higher profile), with OLEDs 1cm is ok)
- usb cable, trrs cable, rotary encoder knobs, keycaps

## License 
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
