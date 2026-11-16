# Mikrainix

Mikrainix is a custom PCB design project for an embedded Linux mini PC based on the **Rockchip RV1106G3 MPU**, featuring integrated AI hardware acceleration and a **Lattice ECP5 FPGA** for programmable logic.

## MPU Specifications

- **CPU:** Single-core ARM Cortex-A7, up to 1.2 GHz.
- **Integrated MCU:** RISC-V architecture.
- **Memory:** 256 MB integrated DDR3L.
- **NPU:** 1 TOPS AI accelerator.
- **Interfaces:** USB 2.0, Ethernet, SDIO, UART, SPI, and I²C.

## FPGA Specifications

- **FPGA:** Lattice ECP5 LFE5U-25F-7BG256C.
- **Communication:** SPI interface with the Rockchip MPU and USB-UART interface.

## Board Architecture

The design also includes:

- An STM32L052 microcontroller for system management and control.
- An ESP32-MINI-1-N4 for Wi-Fi and Bluetooth connectivity.
- A USB-C Power Delivery interface for power management.
- A shared USB port between the MPU and FPGA.
- A dedicated FPGA subsystem with its own power supplies and communication interfaces.

## Project Status

**In progress** — schematic and PCB design phase.

## Author

**Kim Davy NDAYONGEJE**