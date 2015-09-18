# Arduino Make file. Refer to https://github.com/sudar/Arduino-Makefile

BOARD_TAG    = mega2560
ISP_PORT = /dev/ttyUSB0
MONITOR_PORT = /dev/ttyUSB0

ARDMK_DIR=/usr/share/arduino

USER_LIB_PATH = libraries

CXXFLAGS = -Wno-deprecated-declarations -g3

MONITOR_BAUDRATE = 230400

ARDUINO_LIBS = \
	       Wire \
	       SPI

-include $(ARDMK_DIR)/Arduino.mk

CFLAGS_STD = -Wall -Werror
CXXFLAGS_STD = -Wall -Werror
# !!! Important. You have to use make ispload to upload when using ISP programmer
