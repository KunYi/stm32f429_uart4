stm32f429_uart4
===============

Verify STM32F429 Discovery UART4 on PORTA 

Toolchain
==============
gcc 4.8 for ARM, url:https://launchpad.net/gcc-arm-embedded

Download
==============
stlink, url: https://github.com/texane/stlink

Build
==============
make

Download
==============
st-flash write uart4.bin 0x08000000
or 
make flash
