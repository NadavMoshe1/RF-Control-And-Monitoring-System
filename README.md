# RF Control and Monitoring System

A CPLD-based wireless RF control and monitoring system implementing a master–slave architecture.  
The system is designed for reliable remote control and status monitoring using RF communication modules and multiple industrial interfaces.

## Project Overview
This project implements a generic electronic control platform based on an Intel (Altera) MAX 10 CPLD.  
Two identical hardware units are used as **MASTER** and **SLAVE**, communicating wirelessly over an RF link.  
The MASTER sends control commands, while the SLAVE interfaces with external devices and returns status information.

## Key Features
- Wireless RF communication (XBee / Zigbee / RF modules)
- Master–Slave architecture
- CPLD-based control logic
- VHDL firmware
- Multiple communication interfaces:
  - UART
  - RS422
  - RS485
  - SPI
  - I2C
- Digital I/O (TTL / LVTTL)
- PWM outputs for servo motor control
- Relay control and debounced switch inputs
- On-board monitoring (voltage, current, temperature)
- External SDRAM support

## Hardware
- Intel (Altera) MAX 10 CPLD
- RF transceiver modules (XBee / Zigbee / XTend / NRF24)
- Multi-layer PCB
- Power regulation and protection circuits
- Industrial communication buffers and isolation

## Software
- VHDL firmware for CPLD
- UART-based RF communication protocol
- Modular design:
  - Communication interfaces
  - System manager
  - Message encoder / decoder
  - PWM controller
  - I/O control logic

## Development Tools
- Intel Quartus (CPLD development)
- ModelSim (simulation)
- XCTU (RF module configuration)
- OrCAD (schematic design)

## Use Cases
- Wireless control systems
- Remote monitoring applications
- Industrial and embedded control platforms
- Academic final project

## Author
**Nadav Moshe**

## Notes
This project was developed as a final practical engineering project and focuses on reliability, modularity.
