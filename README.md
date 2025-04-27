# STM32F407 Low-Level Driver Library

## 📋 Project Description

This project contains **custom low-level drivers** developed for the **STM32F407 microcontroller**.  
All drivers are written manually without using STM32CubeMX or the official STM32 HAL/LL libraries, providing direct access to hardware resources.

---

## 🚀 Features

- Manual peripheral initialization and configuration
- No dependency on STM32CubeMX or STM32 HAL
- Clean and modular driver architecture
- Focused on bare-metal embedded development

---

## 📂 Implemented Drivers

- **GPIO**: General Purpose Input/Output configuration (Input, Output, Alternate Function, Pull-up, Pull-down)
- **EXTI**: External Interrupt Controller configuration
- **I2C**: I2C communication setup (Master mode)
- **RCC**: Reset and Clock Control configuration
- **SPI**: Serial Peripheral Interface setup
- **USART**: Universal Synchronous/Asynchronous Receiver/Transmitter setup
- **Specific_Header_File**: Device-specific header files and definitions

---

## 🛠️ Compilation and Usage

You can directly integrate these drivers into your STM32F407 projects.  
Recommended development environments:
- **Compiler/IDE**: ARM GCC / STM32CubeIDE / Keil MDK / IAR Embedded Workbench
- **Target Device**: STM32 series
- 
```
## 📜 Requirements

- Basic knowledge of STM32F4 memory map and peripherals
- Understanding of ARM Cortex-M3/M4 architecture
- C compiler compatible with C99 or later standards

---

## 👨‍💻 Developer

**Volkan Sarı**  
[LinkedIn Profile](https://www.linkedin.com/in/volkansarii1/)  
📫 Contact: **vlkn.sarii@gmail.com**

