# lixx-bat-indicator

Плата для вимірювання напруги батареї LiFePo або Li-ion.
Складається з процесора CH32V003J4M6 та OLED-дісплейного модуля 128х64 або 128x32 (на справді ще не визначився).

Тут буде і плата (в подальшому) і програма.


    PIN MAP
    -------

    pin2 - VSS
    pin4 - VDD

    pin8 - DIO (programming)

    pin1 - PA1 - Тимчасово світлодіод LED

    OLED-display
    pin5 - PC1 - I2C SDA
    pin6 - PC2 - I2C SCL


## Встановлення інструментів

https://github.com/riscv-software-src/homebrew-riscv

```bash
brew tap riscv-software-src/riscv
brew install riscv-tools
brew install riscv-openocd
brew test riscv-tools
/opt/homebrew/opt/riscv-gnu-toolchain/bin/riscv64-unknown-elf-gcc --version
```

/opt/homebrew/opt/riscv-openocd/bin/openocd



Во, подивиться це:

https://github.com/wagiminator/CH32V003-GameConsole/tree/main

Ще це:
https://github.com/wagiminator/MCU-Templates

Ще тут купа посилань:
https://github.com/wagiminator/Development-Boards/tree/main/CH32V003A4M6_DevBoard


https://github.com/AlessandroAU/ESP32-CRSF-Packet-Gen/blob/master/CRSF_testcode/CRSF.h
https://px4.github.io/Firmware-Doxygen/d9/dd2/crsf_8cpp_source.html

https://github.com/vedderb/bldc_uart_comm_stm32f4_discovery/blob/c19a6283e187040f25aa52e213673938db054d06/bldc_interface.c#L567

https://vedder.se/2015/10/communicating-with-the-vesc-using-uart/
