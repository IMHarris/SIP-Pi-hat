# SIP Pi HAT

Raspberry Pi HAT for the [SIP (Smart Irrigation Program)](https://github.com/Dan-in-CA/SIP) irrigation controller.

## Features

- Designed to interface with SIP irrigation controller on Raspberry Pi
- Outputs for relay control of up to 16 stations with 74HC595 output header for more
- XAIO ESP32C3 module for flow sensor monitoring with inputs for hall flow sensor
- Communicates flow sensor data to Pi via UART
- 5v I2c headers. Great for LCD plugin.

## Hardware

This project contains KiCad 7+ design files:
- `SPI_Hat.kicad_sch` - Schematic
- `SPI_Hat.kicad_pcb` - PCB layout
- `SPI_Hat.kicad_pro` - Project file
- `Gerber/` - Manufacturing files

## Firmware

The ESP32C3 firmware is available in the companion repository: [flow-sensor-esp32](https://github.com/IMHarris/flow-sensor-esp32)

## Bill of Materials

See `SPI_Hat.csv` for the complete BOM.

## Related Projects

- [SIP Irrigation Controller](https://github.com/Dan-in-CA/SIP)
- [SIP Plugins](https://github.com/Dan-in-CA/sip_plugins)
- [ESP32C3 Flow Sensor Firmware](https://github.com/IMHarris/flow-sensor-esp32)