# MSP430 CLion Template #

## Requirements ##

* MSP430-GCC opensource toolchain (http://www.ti.com/tool/msp430-gcc-opensource)
* mspdebug (for uploading firmware)

## Settings ##

Set environment variable *MSP430_GCC_PATH* to the installed msp430-gcc-opensource toolchain, eg: 

    export MSP430_GCC_PATH=~/msp-gcc
    export PATH="${MSP430_GCC_PATH}/bin:${PATH}"

in ```~/.profile``` or ```~/.bashrc``` file
