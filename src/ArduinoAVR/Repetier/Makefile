# Arduino Make file. Refer to https://github.com/sudar/Arduino-Makefile

# For the RAMPS 1.4 electronics
SHIELD_TAG   = ramps
# For the BrundleFab protoboard
#SHIELD_TAG   = brundle

BOARD_TAG    = mega2560
ISP_PORT = /dev/ttyACM0
MONITOR_PORT = /dev/ttyACM0

MONITOR_BAUDRATE = 115200
ARDMK_DIR=/usr/share/arduino

USER_LIB_PATH = libraries

CXXFLAGS = -DMICROSTEPS=16 -Wno-deprecated-declarations

ARDUINO_LIBS = \
	       SPI \
	       Wire

CFLAGS_STD = -Wall -Werror
CXXFLAGS_STD = -Wall -Werror

-include $(ARDMK_DIR)/Arduino.mk

# !!! Important. You have to use make ispload to upload when using ISP programmer
