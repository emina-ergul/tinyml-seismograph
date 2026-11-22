## Notes

- my specific board STM32F407G-DISC1 specs (that I care about):
    - built around the STM32F407VGT6 32-bit Arm Cortex-M4 microcontroller
    - 1 MB of Flash memory and 192 KB of SRAM
    -  ST-MEMS 3-axis digital accelerometer
    - supports both IC2 and SPI but the accelerometer         specifically is SPI
    - STM32CubeIDE compatible

- HAL library import (hardware abstarction layer) is an STM specific library