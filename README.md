# Custom ESP32-S3 PCB Design (Altium Designer)

## Overview
This project showcases the design of a **4-layer custom PCB** built around the **ESP32-S3** microcontroller. It includes **dual USB-C ports**—one for **native USB** and one for **UART communication via FTDI**—and features a **low-noise LDO regulator** to supply a stable 3.3V to the system.

The board is designed using **Altium Designer** for embedded applications that require robust connectivity and clean power delivery.

## Components Used
- **Microcontroller:** ESP32-S3-WROOM-1-N8R8  
- **Voltage Regulator:** TL1963A-33DCYR (Ultra-Low Dropout, 3.3V, 1.5A)  
- **USB-C Ports:**
  - 1 × USB-C (Native USB with ESD protection)
  - 1 × USB-C (UART via FTDI FT232RL)
- **USB-UART Bridge:** FTDI FT232RL  
- **Capacitors:** Decoupling (0.1µF, 1µF, 10µF), Bulk (100µF tantalum) – X7R, 0603/0805  
- **Protection Components:** TVS diode for USB, ferrite beads for power filtering  
- **Connectors:** Standard 2.54mm headers for I/O and debugging  

## Features
✔️ **ESP32-S3** with integrated Wi-Fi + BLE  
✔️ **Two USB-C ports** (native + UART)  
✔️ **Clean 3.3V power** via TL1963A LDO  
✔️ **4-layer PCB** for improved signal integrity and EMI control  
✔️ **Optimized layout** for power and high-speed USB signals  
✔️ **Designed in Altium Designer** for professional prototyping  

## Files Included
📁 **Altium Project Files** (`.SchDoc`, `.PcbDoc`)  
📁 **Layer Stack Manager Configuration**  
📁 **Gerber Files** (for PCB fabrication)  
📁 **BOM (Bill of Materials)**  
📁 **PDF Schematics** and assembly drawings  

## Installation & Usage
1. Open the project in **Altium Designer**.
2. Review the schematic (`.SchDoc`) and PCB layout (`.PcbDoc`).
3. Inspect the 4-layer stack configuration and routing for USB and power domains.
4. Generate the **Gerber files** and **NC Drill files** for fabrication.
5. Assemble the PCB and program the ESP32-S3 using:
   - The **native USB-C** port (DFU mode)
   - The **FTDI UART USB-C** port with flashing tool

## TOP

![Image Alt](https://github.com/FaresAmor/ESP32_ALTIUM_DESIGNER/blob/main/top.png)

## BOTTOM

![Image Alt](https://github.com/FaresAmor/ESP32_ALTIUM_DESIGNER/blob/main/bottom.png)

## Contribution
Feel free to explore, modify, and contribute! If you find any issues or improvements, open a pull request or raise an issue. 🚀





## Demo
Below is a preview of the PCB design:

![Demo](https://github.com/FaresAmor/ESP32_ALTIUM_DESIGNER/blob/main/vedio.gif)


---
> 💡 **Tip:** This board is ideal for use in embedded prototyping platforms, USB device development, or wearable tech applications.
