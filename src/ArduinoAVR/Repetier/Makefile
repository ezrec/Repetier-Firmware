# Arduino Make file. Refer to https://github.com/sudar/Arduino-Makefile

BOARD_TAG    = mega2560
ISP_PORT = /dev/ttyUSB0
MONITOR_PORT = /dev/ttyUSB0

MONITOR_BAUDRATE = 230400
ARDMK_DIR=/usr/share/arduino

USER_LIB_PATH = libraries

ARDUINO_LIBS = SPI \
	       Wire

CXXFLAGS = -Wno-deprecated-declarations -Werror

-include $(ARDMK_DIR)/Arduino.mk

EXTRA_FLAGS = -Wall -Werror
# !!! Important. You have to use make ispload to upload when using ISP programmer
