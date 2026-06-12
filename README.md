# 12V Isolated Flyback Power Supply (CSC7225)

![Status: Completed](https://img.shields.io/badge/Status-Completed-success)
![EDA: EasyEDA](https://img.shields.io/badge/EDA-EasyEDA-blue)
![Manufacturer: JLCPCB](https://img.shields.io/badge/Manufacturer-JLCPCB-red)

A professionally designed, manufactured, and validated 12V Flyback Switched-Mode Power Supply (SMPS) utilizing the highly integrated CSC7225 controller. This project demonstrates the practical application of power electronics concepts, from theoretical design to physical validation.

<p align="center">
  <img src="https://raw.githubusercontent.com/YairOlvera130703/POWER-SUPPLY-12V/main/Images/3D-DESIGN.png" alt="3D PCB Design in EasyEDA" width="600"/>
</p>

## 📌 Project Overview
Converting AC mains voltage to low-voltage DC using linear power supplies is inefficient and bulky. The goal of this project was to design a compact and efficient SMPS that guarantees galvanic isolation for user safety.

By utilizing the integrated **CSC7225** controller, this design minimizes parasitic inductances, optimizes PCB space, and achieves a highly stable 12V output.

### ✨ Key Features
* **Topology:** Isolated Flyback Converter.
* **Operation Mode:** Discontinuous Conduction Mode (DCM).
* **Controller:** CSC7225 (Integrated PWM and Power BJT).
* **Input Voltage:** 127V AC / 220V AC.
* **Output Voltage:** 12V DC (Adjustable via trimpot).
* **Output Ripple:** ~0.017% (Measured at 2.08 mV peak-to-peak).
* **Safety:** Full galvanic isolation (Transformer + Optocoupler PC817) and Class Y capacitor integration.

## 🗂️ Repository Structure

```text
📁 POWER-SUPPLY-12V/
├── 📁 Docs/
│   ├── Final Project Report.pdf
│   └── Final_Project_report
├── 📁 Hardware/
│   └── 📁 Gerbers/
│       ├── Final Project PDF.pdf
│       ├── Gerber_PCB1_2025-30-11.zip
│       └── Schematic
├── 📁 Images/
│   ├── 📁 Oscilloscope/
│   │   ├── Images2
│   │   ├── as.png
│   │   ├── as1.png
│   │   └── as2.png
│   ├── 3D-DESIGN.png
│   └── Image1
└── README.md
