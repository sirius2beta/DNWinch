# DNWinch
esptool.py --port /dev/ttyUSB0 write_flash --flash_mode qio --flash_size detect 0x0 winch_control.ino.bootloader.bin 0x10000 winch_control.ino.bin