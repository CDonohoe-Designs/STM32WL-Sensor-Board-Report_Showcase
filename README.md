# STM32WL Sensor Board – Analog Front-End & LoRa System

This repository showcases a complete STM32WL-based sensor node design integrating analog front-end (AFE), ADC signal conditioning, and LoRa communication. It demonstrates a modular, simulation-backed hardware design suitable for real-time environmental monitoring and remote sensing applications.

---

## Project Overview

This project includes:
-  Low-noise analog front-end for signal acquisition
-  LoRa wireless communication using STM32WL
-  LTspice + Python simulation of filter and ADC behavior
-  Full schematic, PCB layout, and 3D render documentation
-  Designed with DFM/EMC in mind, for ISO/ETSI/FCC readiness

---

## Folder Structure

```bash
STM32WL-Sensor-Board-Report_Showcase/
├── Report/
│   ├ STM32WL_Lora_ADC_System_V1.1.pdf
│   └ README.md
│
├── Simulation/
│   ├ LTspice/
│   │   ├ .asc / .net files for analog signal path
│   │   ├ Simulation plots (.JPG)
│   │   └ README.md
│   └ Python Analysis/
│       ├ FFT, SNR, Pulse Response plots (.JPG)
│       └ README.md
│
├── Hardware/
│   ├ Schematic_TopLevel.pdf
│   ├ PCB_TopLayer.png
│   ├ STM32WL_Schematics_PCB_Overview.pdf
│   └ README.md
│
├── LICENSE
└── README.md  ← (you are here)
```

---

## System Architecture

![Block Diagram](Hardware/BlockDiagram_STM32_LoRa_Sens_ADC_AFE1.pdf)

---

## 📌 Highlights

- 📐 Designed for analog signal fidelity (filtered + buffered ADC input)
- 📡 Integrated LoRa RF front-end with matching/filtering
- 📁 Full documentation, analysis & PCB-ready design

---

© 2025 Caoilte Donohoe | [GitHub](https://github.com/CDonohoe-Designs)
