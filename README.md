# Bootloader-STM32

Created an application that runs after the bootloader starts in a different portion of the memory in STM32F411RE Nucleo Board. This repository was done to get an hands on experience in bootloaders.

### Key take aways:

- Basics of the linker script
- How to place variables in RAM and FLASH
- How to create functions in RAM and FLASH
- How to create a simple bootloader
- How to offset the interrupt vector and create an application to run in a different memory region
- How to debug bootloader and application
- How to share an API between bootloader and application


### Memory Partitioning in STM32 

![image](https://github.com/user-attachments/assets/ca0c6af5-f23c-4bba-a21f-203d7dce392b)

![image](https://github.com/user-attachments/assets/eac23595-7039-4594-bdf4-17b2e4f996ce)
