# Automatic Night Lamp PCB

An automatic night lamp PCB designed in **EasyEDA** using an **LDR** and **BC547 transistor**, documenting the complete PCB design workflow from schematic capture to PCB layout.

---

## 📖 Project Overview

This project implements an **Automatic Night Lamp** that detects ambient light using a **Light Dependent Resistor (LDR)** and automatically controls an LED through a **BC547 transistor**.

The primary objective of this project was to learn the complete PCB design process using **EasyEDA**, including:

- Circuit schematic design
- Electronic component selection
- PCB layout design
- Component placement
- PCB routing
- Design Rule Check (DRC)
- 3D PCB visualization
- Gerber file generation for manufacturing

This repository documents my learning journey and serves as my first PCB design project.

---

## ✨ Features

- Automatic light detection using an LDR
- BC547 transistor used as an electronic switch
- Single-layer PCB designed in EasyEDA
- Beginner-friendly analog electronics project
- Complete PCB design documentation
- Ready for Gerber file generation

---

## ⚙️ Specifications

| Specification | Details |
|---------------|---------|
| Project Type | Automatic Night Lamp |
| PCB Software | EasyEDA |
| PCB Type | Single Layer |
| Sensor | Light Dependent Resistor (LDR) |
| Switching Device | BC547 NPN Transistor |
| Output | LED |
| Input Supply | DC Power Source |

---

## 🧰 Components Used

| Component | Quantity |
|-----------|---------:|
| BC547 Transistor | 1 |
| LDR | 1 |
| LED | 1 |
| 100kΩ Resistor | 1 |
| 220Ω Resistor | 1 |


---

## 🔄 Working Principle

The circuit operates based on the surrounding light intensity.

- In darkness, the resistance of the LDR increases.
- This changes the transistor's biasing conditions.
- The BC547 transistor turns ON.
- The LED glows automatically.

When sufficient light falls on the LDR, its resistance decreases, turning the transistor OFF and switching the LED OFF.

---

## 🖼️ Project Gallery

### Circuit Schematic

![Circuit Schematic](images/Circuit_Schematic.png)

---

### PCB Top View

![PCB Top](images/PCB_Top.png)

---

### PCB Bottom View

![PCB Bottom](images/PCB_Bottom.png)

---

### PCB 3D Front View

![PCB 3D Front](images/PCB_3D_Front.png)

---

### PCB 3D Back View

![PCB 3D Back](images/PCB_3D_Back.png)

---

### PCB Routing

![PCB Routing](images/PCB_Tracing.png)

---

## 📂 Repository Structure

```
Automatic-Night-Lamp-PCB
│
├── images/
│   ├── Circuit_Schematic.png
│   ├── PCB_Top.png
│   ├── PCB_Bottom.png
│   ├── PCB_3D_Front.png
│   ├── PCB_3D_Back.png
│   └── PCB_Tracing.png
│
├── hardware/
│   ├── easyeda/
│   ├── gerber/
│   └── bom/
│
├── docs/
│
├── datasheets/
│
├── LICENSE
└── README.md
```

---

## 📚 Lessons Learned

This project helped me understand several important PCB design concepts, including:

- Difference between a circuit schematic and PCB layout
- Importance of proper component placement
- PCB routing techniques
- Electrical connectivity through copper traces
- Design Rule Check (DRC)
- Preparing PCB files for manufacturing
- Understanding how electronic circuits become physical hardware

---

## 🚀 Future Improvements

- Manufacture and test the PCB
- Improve component placement
- Reduce PCB dimensions
- Convert the design to SMD components
- Improve routing efficiency
- Add silkscreen improvements
- Perform real-world hardware validation

---

## 👨‍💻 Author

**Akhya Bairi**

B.Tech Electronics and Communication Engineering (ECE)

Currently exploring:

- PCB Design
- Embedded Systems
- IoT
- Robotics
- Firmware Development

---

## 📄 License

This project is licensed under the MIT License.
