![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white) ![Inkscape](https://img.shields.io/badge/Inkscape-e0e0e0?style=for-the-badge&logo=inkscape&logoColor=080A13)

# Balut55
a 55% handwired keyboard with rotary encoder
for an easier transition to a keyboard without numkeys, but still has arrow keys

## Hardware
Microcontroller: [Elite-C](https://deskthority.net/wiki/Elite-C). See link for pinout.

### Wiring
Wire mapping created using [Keyboard Firmware Builder](https://kbfirmware.com/).
See `vial-qmk > config.h` for pin configuration and `vial-qmk > info.json` for mapping.
![wiring](./hardware/wiring.png)

### Plate
[Plate design](./hardware/kbplate.svg) created using [Keyboard Plate Generator by Keebio](https://plate.keeb.io/)

## Firmware
This keyboard has been programmed to work with [Vial](https://get.vial.today/). Note that the vial-qmk directory will not work on its own. You will need to fork the [vial-qmk respository](https://github.com/vial-kb/vial-qmk), and nest the directory under vial-qmk > keyboards > handwired

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).
