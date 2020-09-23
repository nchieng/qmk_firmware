# The default keymap for xd87


```
$ qmk compile -kb xd87 -km nchieng
# Connect keyboard in bootloader mode
$ sudo dfu-programmer atmega32u4 erase
$ sudo dfu-programmer atmega32u4 flash xd87_nchieng.hex
$ sudo dfu-programmer atmega32u4 reset
```