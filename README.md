# STM32F1 Project template

This is a template project for any STM32F1 microcontroller. In order to select the appropiate
microcontroller model, you need to:

* Change the $(CPU) alias in the Makefile to match your MCU.
* Change the $(LDSCRIPT) alias in Makefile to match your corresponding MCU.
* Change -D option in CFLAGS to match your MCU.
