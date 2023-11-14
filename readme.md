# KeyMaster
This is a simple 3x3 macropad with an rotary encoder based on the rp2040 Raspberry Pi Pico. 
You can use VIA if you flash the VIA keymap.



* Keyboard Maintainer: [Bastian Reuther](https://github.com/bastifpv)
* Hardware Availability: 
    - [Pi Pico](https://www.raspberrypi.com/products/raspberry-pi-pico/) 
    - [Keychron K Pro Switch](https://www.keychron.com/products/keychron-k-pro-switch)
    - [1N4148 Diodes](https://www.amazon.de/Hailege-100PCS-1N4148-IN4148-High-Speed/dp/B07YZ8G7TG/ref=sr_1_6?__mk_de_DE=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=N5YHFBVFQFPE&keywords=diode+100+pack&qid=1695635790&sprefix=diode+100+pack%2Caps%2C92&sr=8-6)

Copy this folder to `qmk-firmware/keyboards/`

Compile example for this keyboard (after setting up your build environment):

    qmk compile -kb KeyMaster -km via

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 2 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the ´BOOTSEL´ button on the Pi Picos
