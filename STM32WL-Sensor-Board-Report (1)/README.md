# STM32WL Sensor Board with Analog Front-End and LoRa

This repository documents the design, simulation, and implementation of a custom sensor board based on the STM32WL microcontroller, featuring:
- Analog signal acquisition chain with anti-aliasing filter
- LoRa wireless communication
- Environmental and motion sensors (BME280, MPU6050)
- SMA and BNC interfaces for external sensors

The project is structured into 3 key areas:
- 📘 **Report/**: Final PDF technical design report
- ⚙️ **Simulation/**: LTspice and Python simulations for filter + bias circuit
- 🔧 **Hardware/**: Schematics and PCB layout exports

Designed to demonstrate full-lifecycle embedded hardware development, analog signal integrity, and RF-aware PCB design using STM32WL.

---

## Folder Overview

| Folder | Description |
|--------|-------------|
| `Report/` | Full technical design report in PDF format |
| `Simulation/` | LTspice + Python simulation files and plots |
| `Hardware/` | Schematic and layout images from Altium exports |

> 📍 For further info, contact: caoiltedonohoe@gmail.com
