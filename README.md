# 🐐 GoatFC-Bones - Open Source FPV Flight Controller

<div align="left">
  <p>
    <strong>GoatFC-Bones</strong> is a compact, cheap, open-source FPV drone flight controller designed for racing builds without sacrificing performance. It’s ideal for hobbyists who want simple hardware so that they can easily understand what is happening in their quadcopter.
  </p>
</div>

<img src="/pictures/top-side.jpg" alt="GoatFC-Bones Flight Controller" align="right" width="400">

## 🔧 Key Features

- **Voltage Regulation:**
  - 5V and 12V BEC outputs
  - Dual 3.3V LDOs:
    - One dedicated to the IMU for **noise isolation**
    - One for the rest of the system

- **Connectivity:**
  - Micro-USB for configuration
  - 20x20mm standard mounting pattern
  - ESC connector for clean wiring
  - 6-pin HD video system plug

- **Software:**
  - Compatible with [Betaflight](https://betaflight.com/) no official target yet!

- **License & Use:**
  - **Open-source** – build it, modify it, improve it
  - **Non-commercial** – redistribution for sale is **not allowed**
## 🧷 Pinout Diagram

Below is the pinout for the GoatFC-Bones flight controller. Make sure to reference the silkscreen labels when wiring your components.

<img src="pictures/pinout goatfc bones.png" alt="GoatFC-Bones Pinout" width="400">

> ⚠️ **Note:** The dedicated 3.3V regulators *are* broken out on the board, but **they are not intended for external use**. If you're curious about their exact location or implementation, please refer to the KiCad design files. Avoid connecting anything to these lines unless you fully understand the design — using them improperly may cause instability or damage.


> 🔌 Always double-check with a multimeter before connecting components!

