STM32Cube STM32F0xx HAL Driver
==============================

STM32F0xx HAL Driver package maintained by Argonio.
This build is based on the official STM32CubeF0 HAL v1.0.1 located at:
http://www.st.com/web/catalog/tools/FM147/CL1794/SC961/SS1743/LN1897/PF260612?icmp=pf260612_pron_nb_jun2014&sc=stm32cubef0-pr

Main features of this package:
* Makefile build
* Makefile include file `argonio-stm32f0xx-hal-driver.mk` designed for use in your projects
* Configuration template for HAL and CMSIS

This package depends on Argonio STM32Cube CMSIS:
https://github.com/dobromyslov/argonio-stm32-cmsis

Proposed layout for your project:

    lib\ +
         |- argonio-stm32-cmsis
         \- argonio-stm32f0xx-hal-driver
    src\ +
         |- conf\ +
         |        |- stm32f0xx_cmsis_conf.h
         |        \- stm32f0xx_hal_conf.h
         \- main.c
    Makefile
