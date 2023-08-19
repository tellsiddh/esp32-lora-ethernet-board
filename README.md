# Custom LoRa and Ethernet Communication Board

> :warning: **Notice**: This repository is in the process of being updated. The complete project content, including source code, schematics, and documentation, will be uploaded soon. Stay tuned for updates!

## Overview

This repository contains the design, implementation, and firmware for a custom communication board using the ESP32 chip. The board integrates both LoRa (RFM95W) and Ethernet (LAN8720) capabilities, providing a versatile and robust communication solution for IoT applications.

### Key Features

- **ESP32 Chip**: Utilizes the dual-core Xtensa LX7 processor, running at 240 MHz, with integrated Wi-Fi and Bluetooth.
- **LoRa Connectivity**: Features the RFM95W transceiver, operating at 915 MHz, achieving a range up to 15 km with configurable power levels.
- **Ethernet Support**: Incorporates the LAN8720 Ethernet PHY for 10/100 Mbps wired connectivity.
- **RTOS Integration**: Implemented with FreeRTOS, enabling efficient multitasking and concurrent execution of network tasks.
- **Power Management**: Includes advanced power-saving modes to maximize battery life.

## Hardware Specifications

- **Microcontroller**: ESP32 dual-core with 520 KB SRAM
- **LoRa Module**: Semtech RFM95W
- **Ethernet Module**: Microchip LAN8720
- **PCB Design**: 4-layer design with 50-ohm controlled impedance for RF signals
- **Interfaces**: SPI, I2C, UART

## Firmware

- **Language**: Embedded C
- **RTOS**: FreeRTOS
- **OTA Updates**: Supports over-the-air firmware updates
- **Networking Protocols**: MQTT, TCP/IP, UDP

## Getting Started

1. **Clone the Repository**: `git clone https://github.com/tellsiddh/esp32-lora-ethernet-board.git`
2. **Install Dependencies**: Refer to the 'Installation Guide' section in the documentation.
3. **Build and Flash the Firmware**: Instructions available in the `BUILD.md` file.

## Documentation

Comprehensive documentation, including schematics, PCB layout, firmware API, and user guides, is available in the `docs/` directory.

## Contributing

We welcome contributions! Please see the [CONTRIBUTING.md](CONTRIBUTING.md) file for guidelines.

## Support

For support or inquiries, please open an issue or contact the repository owner.

---

Developed with dedication by [Siddharth Jain](https://github.com/tellsiddh)
