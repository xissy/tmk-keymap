# tmk-keymap
> Taeho's HHKB Pro2 or Type-S Hasu Bluetooth Constoller Custom Keymap

1. Go to `http://www.tmk-kbd.com/tmk_keyboard/editor/unimap/?hhkb_rn42`
1. Import `hhkb_hasu_taeho.hex` file
1. Customize it
1. Export(Download) the firmware hex file
1. Flash the file to the keyboard
    1. `dfu-programmer atmega32u4 erase --force`
    1. `dfu-programmer atmega32u4 flash hhkb_hasu_taeho`
