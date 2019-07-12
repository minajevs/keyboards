# My keyboards

I own some nice keyboards. QMK layout configs are stored in this repo.

## How to flash a QMK keyboard
1) Download QMK Toolbox either from this repo, or from [official source](https://github.com/qmk/qmk_toolbox/releases)
2) Enter a bootloader mode on a keyboard
    1) Unplug it
    2) Hold "bootloader combo" (usually space + b)
    3) Plug it back
    4) After few seconds let combo go
3) In QMK Toolbox choose compiled keymap, correct microcontroller (usually shown when you connect a keyboard in bootloader mode)
4) Click "flash"
5) Done

## Useful link
* [Latest QMK Toolbox releases](https://github.com/qmk/qmk_toolbox/releases)
* [QMK Configurator](https://config.qmk.fm)
* [Keycode reference](https://docs.qmk.fm/#/keycodes)