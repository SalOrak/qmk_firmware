# Corne Choc 

<<<<<<< HEAD
I've recently built a Corne Choc 3x6 with Kailh Hotswaps using Silver switches.

This is a forked repository from ![QMK Firmware](https://github.com/qmk/qmk_firmware/) public GitHub repository.
QMK is a keyboard firmware based on the [tmk\_keyboard firmware](https://github.com/tmk/tmk_keyboard) with some useful features for Atmel AVR and ARM controllers, and more specifically, the [OLKB product line](https://olkb.com), the [ErgoDox EZ](https://ergodox-ez.com) keyboard, and the [Clueboard product line](https://clueboard.co).
=======
[![Current Version](https://img.shields.io/github/tag/qmk/qmk_firmware.svg)](https://github.com/qmk/qmk_firmware/tags)
[![Discord](https://img.shields.io/discord/440868230475677696.svg)](https://discord.gg/qmk)
[![Docs Status](https://img.shields.io/badge/docs-ready-orange.svg)](https://docs.qmk.fm)
[![GitHub contributors](https://img.shields.io/github/contributors/qmk/qmk_firmware.svg)](https://github.com/qmk/qmk_firmware/pulse/monthly)
[![GitHub forks](https://img.shields.io/github/forks/qmk/qmk_firmware.svg?style=social&label=Fork)](https://github.com/qmk/qmk_firmware/)

This is a keyboard firmware based on the [tmk\_keyboard firmware](https://github.com/tmk/tmk_keyboard) with some useful features for Atmel AVR and ARM controllers, and more specifically, the [OLKB product line](https://olkb.com), the [ErgoDox EZ](https://ergodox-ez.com) keyboard, and the Clueboard product line.
>>>>>>> qmk/master


![Corne Choc Keyboard](crkbd-choc.jpg)

<<<<<<< HEAD
## Layout

I've used [Keyboard Layout Editor](www.keyboard-layout-editor.com) to create an image of my keyboard layout. 
=======
The docs are powered by [VitePress](https://vitepress.dev/). They are also viewable offline; see [Previewing the Documentation](https://docs.qmk.fm/#/contributing?id=previewing-the-documentation) for more details.

You can request changes by making a fork and opening a [pull request](https://github.com/qmk/qmk_firmware/pulls).
>>>>>>> qmk/master

I'm currently using Dvorak and I added some custom keymaps to adapt my needs.

### Layer 0 

Layer 0 is my base layer and it is where all my alpha keys are mapped.

![Dvorak Layer 0](dvorak-layer-0.jpg)

### Layer 1 

Layer 1 is the **symbols** and **numbers** layout.

![Dvorak Layer 1](dvorak-layer-1.jpg)

### Layer 2

Layer 2 is the **misc*** and **movement** layout. It include the ability to fully use the mouse without a mouse!

![Dvorak Layer 2](dvorak-layer-2.jpg)


## Build
If you have a Corne Choc 3x6 keyboard and you want to use the same layout run 
```bash
make crkbd:dvorak
# or make crkbd:qwerty
```
