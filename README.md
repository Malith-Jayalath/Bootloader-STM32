# Bootloader-STM32

Created an application that runs after the bootloader starts in a different portion of the memory in STM32F411RE Nucleo Board. This repository was created to obtain a hands-on experience in bootloaders.

### Key takeaways:

- Basics of the linker script
- How to place variables in RAM and FLASH
- How to create functions in RAM and FLASH
- How to create a simple bootloader
- How to offset the interrupt vector and create an application to run in a different memory region
- How to debug the bootloader and application
- How to share an API between the bootloader and the application


### Memory Partitioning in STM32 

![image](https://github.com/user-attachments/assets/ca0c6af5-f23c-4bba-a21f-203d7dce392b)

![image](https://github.com/user-attachments/assets/eac23595-7039-4594-bdf4-17b2e4f996ce)

### Creating a new function in that memory partition

![image](https://github.com/user-attachments/assets/40f0cfda-75f2-4bba-979c-f259fd18d596)

![image](https://github.com/user-attachments/assets/0f89e6a6-0f61-4660-bdc4-39e255669391)

![image](https://github.com/user-attachments/assets/eec1d76f-35d0-447d-9f7e-8a9af455c0e4)

### Bootloader, Application, and the shared static library which is created in the MY_MEMORY region  
![image](https://github.com/user-attachments/assets/7b2643a1-39e6-44a7-a2f8-2a593e96082c)

### Debugging both the Bootloader and Application by setting the Bootloader as the entry point 
![image](https://github.com/user-attachments/assets/2651595a-dbf1-434a-b2e5-52352404ba6a)

### Shared API for both the Bootloader and the Application 
![image](https://github.com/user-attachments/assets/9004f796-49a6-432a-8aa8-8bd033612d31)

### Accessing the API which is in the MY_MEMORY from the Application
![image](https://github.com/user-attachments/assets/1ea902f3-a466-4fda-9487-f31262b04927)
![image](https://github.com/user-attachments/assets/bfe3c910-ff84-45aa-8ea6-24a16797440b)
