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

Below is the pinout for the GoatFC-Bones flight controller. Make sure to reference this schematic when wiring your components.

<img src="pictures/pinout goatfc bones.png" alt="GoatFC-Bones Pinout" width="400">

> ⚠️ **Note:** The dedicated 3.3V regulators *are* broken out on the board, but **they are not intended for external use**. If you're curious about their exact location or implementation, please refer to the KiCad design files. Avoid connecting anything to these lines unless you fully understand the design — using them improperly may cause instability or damage.


> 🔌 Always double-check with a multimeter before connecting components!
## 🛠️ Building Your Own GoatFC-Bones

Amazing that you want to build one!

You can order the PCBs from your favorite PCB manufacturer — the Gerber files are available in the folder:  
[Gerber Files Folder](./gerber%20files)

### 📦 Bill of Materials (BOM)

The BOM is provided as an **interactive iBOM**, which you can view here:  
**[insert iBOM link or path here]**

The iBOM makes it easy to locate and identify all the required components. Just search for the parts and order them from your preferred distributor.

### 🔧 Assembly Tips

- Solder all components following the iBOM placement guide
- Use **solder paste** and a **hot air station** for best results
- All components are **0402 size** — small, but manageable with some patience
- If you're new to SMD soldering, it's a good idea to practice on a scrap board first!

Good luck, and enjoy flying with your custom GoatFC-Bones FC!


