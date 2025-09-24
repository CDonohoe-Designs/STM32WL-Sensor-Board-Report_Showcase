# Simulation Folder

This folder contains analog simulation data supporting the STM32WL Sensor Board's analog front-end.

### 🔧 Subfolders
- `LTspice/` – SPICE simulations for analog filter, bias generation, and differential ADC drive.
- `Python Analysis/` – Time-domain, frequency-domain, and SNR evaluation using NumPy/Matplotlib.

Simulations validate:
- Filter frequency response
- Time-domain ringing and pulse handling
- FFT noise attenuation
- Bias reference stability
