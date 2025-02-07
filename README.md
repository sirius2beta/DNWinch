# DNWinch
esptool.py --port /dev/ttyUSB0 -b 460800 --before default_reset --after hard_reset --chip esp32 write_flash --flash_mode qio --flash_size detect 0x0 winch_control.ino.merged.bin