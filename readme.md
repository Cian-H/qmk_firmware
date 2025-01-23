My personal fork of the QMK project for the purposes of defining my own custom keyboard layouts.

# Installation
1. Build the firmware
```sh
poetry install
poetry run ./compile_my_layout.sh
```
2. Disconnect all wires from keyboard, hold button on kb half while connecting USB.
3. Drag-and-drop .uf2 file onto kb storage.
4. Repeat for other kb half

> [!WARNING]
> The current version of this software is broken due to issue [#24725](https://github.com/qmk/qmk_firmware/issues/24725). It will not be able to be compiled to a .uf2 file until this issue is fixed.

# Keymap

![My keymap](https://github.com/Cian-H/qmk_firmware/blob/master/keymap.svg)
