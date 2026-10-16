# Mikrainix

Mikrainix is a custom PCB design project for an embedded Linux mini PC based on the **Rockchip RV1106G3 MPU**, with hardware acceleration for AI.

## MPU Specifications

- **CPU:** Single-core ARM Cortex-A7, up to 1.2 GHz.
- **Integrated MCU:** RISC-V architecture.
- **Memory:** 256 MB integrated DDR3L.
- **NPU:** 1 TOPS AI accelerator.
- **Interfaces:** USB 2.0, Ethernet, SDIO, UART, SPI, and I²C.

## Board Architecture

The board also integrates:

- An STM32L052 microcontroller for system management and control.
- An ESP32-C6 for Wi-Fi and Bluetooth Low Energy (BLE) connectivity.
- A USB-C Power Delivery interface for power management.
- A shared USB port between the processors.

## Project Status

**In progress** — schematic and PCB design phase.

## Author

**Kim Davy NDAYONGEJE**