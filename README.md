STM32F407 Low-Level Driver Library
📋 Project Description
This project provides custom low-level drivers for the STM32F407 microcontroller, written without using STM32CubeMX or the HAL/LL libraries.
All peripheral drivers were manually implemented to give complete control over hardware resources.

🚀 Features
Manual peripheral initialization and configuration

No dependency on STM32CubeMX or STM32 HAL

Clean and modular driver architecture

Focused on bare-metal embedded development

📂 Implemented Drivers
GPIO: General Purpose Input/Output initialization and configuration (input, output, alternate function, pull-up, pull-down)

EXTI: External Interrupt controller setup

I2C: Inter-Integrated Circuit (I2C) master mode initialization

RCC: Reset and Clock Control configuration

SPI: Serial Peripheral Interface setup

USART: Universal Synchronous/Asynchronous Receiver/Transmitter configuration

Specific_Header_File: Device-specific definitions and configuration headers

🛠️ Compilation and Usage
You can integrate these drivers into any STM32F407 project.
Recommended environment:

Toolchain: ARM GCC / STM32CubeIDE / Keil MDK / IAR Embedded Workbench

Device: STM32F407 series (F407VG, F407ZG, etc.)

📜 Requirements
Basic knowledge of STM32F4 memory map and peripheral registers

ARM Cortex-M3/M4 architecture understanding

A supported C compiler (C99 or later)
