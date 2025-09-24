# STM32WL Sensor Board – Analog Front-End + LoRa System

This repository showcases the design, simulation, and hardware implementation of a custom **STM32WL-based analog sensor node**, integrating:
- High-fidelity analog front-end (AFE)
- ADC signal conditioning and filtering
- LoRa RF communication subsystem

The project demonstrates end-to-end hardware development, simulation (LTspice + Python), and manufacturing documentation for a LoRa-enabled sensor device.

## 🔧 Project Features

- ✅ **STM32WL MCU** with integrated Sub-GHz LoRa transceiver
- ✅ **Analog Front-End** for sensor signal conditioning
- ✅ **Low-Noise Filter** (Sallen-Key, pseudo-differential output)
- ✅ **Simulation** in LTspice and Python for SNR, bandwidth, and transient response
- ✅ **LoRa RF Path** with matching network + filtering
- ✅ **Production-ready** schematics and PCB layout

---

## 📊 Block Diagram

[📂 View Full Block Diagram (PDF)](https://github.com/CDonohoe-Designs/STM32WL-Sensor-Board-Report_Showcase/blob/main/STM32WL-Sensor-Board-Report%20(1)/Hardware/BlockDiagram_STM32_LoRa_Sens_ADC_AFE1.pdf)

---

## 📁 Repository Structure

```
STM32WL-Sensor-Board-Report_Showcase/
├── STM32WL-Sensor-Board-Report (1)/
│   ├── Report/
│   │   ├ STM32WL_Lora_ADC_System_V1.1.pdf
│   │   └ README.md
│   │
│   ├── Simulation/
│   │   ├ LTspice/
│   │   │   ├ LTspice_Sallen_Key_Diff_Output.asc
│   │   │   ├ LTspice_Sallen_Key_Diff_Output.net
│   │   │   ├ LTspice_Sallen_key_MCP6001_filter.asc
│   │   │   ├ [Various .JPG result plots]
│   │   │   └ README.md
│   │   │
│   │   └ Python Analysis/
│   │       ├ [Python SNR, FFT, Pulse, Step .JPGs]
│   │       └ README.md
│   │
│   ├── Hardware/
│   │   ├ Schematic_TopLevel.pdf
│   │   ├ PCB_TopLayer.png
│   │   ├ BlockDiagram_STM32_LoRa_Sens_ADC_AFE1.pdf
│   │   └ STM32WL_Schematics_PCB_Overview.pdf
│
│   └ README.md   ← Project-specific overview
│
├── LICENSE
└── README.md     ← [You are here] Repo landing page
```

---

© 2025 Caoilte Donohoe | [GitHub](https://github.com/CDonohoe-Designs)