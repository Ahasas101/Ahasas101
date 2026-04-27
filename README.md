# Hi, I'm Ahasas Yadav
### Embedded Systems and Firmware Developer

I am an electronics and communication engineering undergraduate specializing in low-level firmware architecture, embedded Linux, and hardware design. My work spans the entire embedded stack—from bare-metal microcontroller programming and custom bootloaders to complex RTOS implementations, Linux kernel modules, and custom PCB design.

[LinkedIn](https://www.linkedin.com/in/ahasas-yadav-188582291/) | [Embedded Portfolio](https://github.com/Ahasas101/Embedded_Portfolio)

---

## Technical Expertise

* **Microcontrollers & SoCs:** ARM Cortex-M (STM32), AM335x (BeagleBone Black), AVR (ATmega16A), ESP32
* **Embedded Linux:** Linux Kernel Modules (LKM), Character & Platform Drivers, Device Tree (DTS), U-Boot, Buildroot, Sysfs
* **Systems & RTOS:** Bare-metal C, Custom Bootloaders, FreeRTOS (Task Scheduling, IPC), UML State Machines, DMA Architecture
* **Protocols:** I2C, SPI, UART, CAN Bus, USB Power Delivery (USB-PD), RF Transmission
* **Tools & Hardware:** STM32CubeIDE, KiCad, GCC Toolchain, GDB, Logic Analyzers, Oscilloscopes, Electromechanical Relays

---

## Featured Projects

### [100W USB-C PD Programmable DC Power Supply](https://github.com/Ahasas101/USB-C-Constant-Voltage-Programmable-Power-Supply)
An advanced power electronics project delivering a programmable DC output negotiated via USB-C Power Delivery.
* Integrated the **CH224K** PD controller to dynamically negotiate voltages from 5V to 20V.
* Developed **STM32** firmware to interface with an **INA226** sensor over I2C for real-time telemetry on an OLED display.
* Designed a custom multi-layer PCB in **KiCad** featuring high-current power planes and PMOS-based reverse-current protection.

### [Embedded Linux & Custom Driver Development](https://github.com/Ahasas101/Linux_Custom_driver_development)
A comprehensive dive into the Linux device model on the AM335x (BeagleBone Black) architecture.
* Developed custom platform drivers and character device drivers for hardware interfacing.
* Engineered hardware abstraction via **Device Tree Source (DTS)** and cross-compiled the **Linux Kernel** and **U-Boot** from scratch.

### [Custom STM32 Bootloader](https://github.com/Ahasas101/Custom_Stm32_Bootloader)
A from-scratch bootloader implementation designed to manage host applications and flash memory architecture on ARM Cortex-M systems.

### [SAVER: Smart Automated Vehicle Overspeed Regulator](https://github.com/Ahasas101/SAVER)
A fault-tolerant, STM32-based intelligent overspeed detection system.
* Engineered board support packages to interface **GPS** and **GSM** modules.
* Implemented an interrupt-driven firmware architecture for real-time monitoring and low-latency violation reporting.

### [4-Bit Binary Relay Calculator](https://github.com/Ahasas101/Project_3_Relay_Binary_Calculator)
A pure hardware logic project demonstrating digital switching theory.
* Architected complex combinational logic (Full Adders, SR Latches) using entirely electromechanical SPDT relays, without any semiconductor logic gates.

---

## Coursework & Specialized Training

I have dedicated significant time to mastering core embedded concepts through rigorous, project-based coursework:

* **[Mastering RTOS (FreeRTOS)](https://github.com/Ahasas101/RTOS_projects_stm32):** Implemented FreeRTOS task scheduling, synchronization primitives, and debugging via Segger SystemView.
* **[ARM Cortex-M DMA Programming](https://github.com/Ahasas101/DMA_projects_Stm32):** Explored direct memory access controller architecture and driver development to offload CPU tasks.
* **[Embedded System Design Using UML](https://github.com/Ahasas101/State_Machine_Projects):** Designed state charts and Finite State Machines using the Quantum Leaps Framework.
* **[Bare-Metal MCU Programming (Level 1 & 2)](https://github.com/Ahasas101/STM32F411CEu6_Drivers):** Authored peripheral drivers (SPI, I2C, UART, CAN, Timers, RTC) for the STM32F411CEU6 directly from datasheets. 

---
*Feel free to explore my repositories above to view my source code, hardware schematics, and detailed project documentation.*
