# TP5100 Switch-Mode Li-Ion Battery Charging Module (TP5100-Charging-Module)

A modular, high-efficiency lithium-ion battery management and charging board powered by the **TP5100** synchronous buck controller IC, designed in KiCad with detailed schematic, PDF layer plots, and 3D photorealistic visualization.

---

## Features

- **Wide Input Voltage Range**:
  - Accepts 5V to 18V DC inputs with built-in thermal and reverse protection.
- **Synchronous Buck Charging Architecture**:
  - Significantly reduced heat dissipation and higher energy conversion efficiency compared to standard linear regulators.
  - Supports programmable charging currents up to 2A with Constant Current (CC) and Constant Voltage (CV) modes.
- **Dual Status Indication**:
  - Onboard bi-color or dual LED indicators for active charging state and charge completion / battery standby.
- **Comprehensive Visual Documentation**:
  - Complete multi-layer assembly plots (`pcb.pdf`, `TP5100_Charging_Module-F_Cu.pdf`, `TP5100_Charging_Module-B_Cu.pdf`).
  - High-resolution schematic diagrams (`Schematic.pdf`, `Schematic.png`).
  - Front and back photorealistic 3D board renders (`Front.png`, `Back.png`).

---

## Hardware Specification

| Parameter | Specification | Details |
| :--- | :--- | :--- |
| **Controller IC** | TP5100 | Synchronous Step-Down Lithium Battery Charger |
| **Input Supply** | 5V – 18V DC | Suitable for DC adapters, USB supplies, or solar panels |
| **Output Voltage** | 4.2V (1S) / 8.4V (2S)| Solder-jumper selectable |
| **Max Charge Current**| 2.0A | Current programming resistor dependent |
| **Switching Freq** | ~400 kHz | High-frequency operation for miniature power inductors |
| **Layer Stackup** | 2-Layer FR4 | Optimized ground return planes and thermal relief vias |

---

## Project Structure

```text
TP5100-Charging-Module/
├── Front.png                         # 3D PCB top surface render
├── Back.png                          # 3D PCB bottom surface render
├── Schematic.pdf                     # High-resolution vector schematic
├── Schematic.png                     # Raster schematic preview
├── pcb.pdf                           # Complete board outline and trace plots
├── TP5100_Charging_Module.kicad_sch  # KiCad schematic design file
├── TP5100_Charging_Module.kicad_pcb  # KiCad PCB board layout
├── TP5100_Charging_Module.kicad_pro  # KiCad project file
├── TP5100_Charging_Module-F_Cu.pdf   # Front copper layer plot
├── TP5100_Charging_Module-B_Cu.pdf   # Back copper layer plot
├── .gitignore                        # Git ignore patterns
└── README.md                         # Project documentation
```

---

## License

Open hardware design. All rights reserved by the author.
