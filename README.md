# STM32F1 Project template

This is a template project for any STM32F1 microcontroller, using the GNU ARM GCC toolchain. In order to select the appropiate
microcontroller model, you need to:

* Change the $(CPU) alias in the Makefile to match your MCU.
* Change the $(LDSCRIPT) alias in Makefile to match your corresponding MCU. LD scripts are located in cmsis/linker/
* Change -D option in CFLAGS to match your MCU.
* Change the startup_stm32f1**.s accordingly. They are located in cmsis/device/src/
