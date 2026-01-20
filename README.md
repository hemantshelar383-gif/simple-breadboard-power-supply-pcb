# Simple Breadboard Power Supply PCB

This repository contains the design files for a **simple breadboard-compatible power supply PCB** developed using **KiCad**.  
The board is intended to provide **stable and reliable DC power rails** for electronics prototyping, testing, and educational experiments on a standard breadboard.

The project focuses on applying **fundamental power electronics and PCB layout principles**, including voltage regulation, grounding, component placement, and design verification.

---

## Project Overview

During prototyping, powering circuits directly from adapters or loose wires often leads to unstable operation and poor reliability.  
This PCB addresses that problem by offering a **compact, reusable, and breadboard-friendly power module** with both **fixed and adjustable voltage outputs**.

The design converts a DC input voltage into regulated outputs using widely used linear voltage regulators, making it suitable for beginner to intermediate electronics projects.

---

## Features

- DC barrel jack input for external power adapters  
- Onboard power ON/OFF switch for safe operation  
- **LM7805** linear regulator for fixed **5V output**  
- **LM317** adjustable regulator with resistor network for variable output voltage  
- Input and output filtering capacitors to improve voltage stability  
- Power indicator LED with current-limiting resistor  
- Screw terminals and pin headers for easy breadboard and external connections  
- Compact PCB layout verified using DRC and 3D visualization  

---

## Major Components Used

- **DC Barrel Jack** – External DC power input (typically 9–12V)  
- **LM7805** – Fixed 5V linear voltage regulator  
- **LM317** – Adjustable linear voltage regulator  
- **Resistors** – Voltage setting for LM317 and LED current limiting  
- **Capacitors** – Input and output filtering for noise reduction and stability  
- **LED** – Visual power indication  
- **SPST Switch** – Power control  
- **Screw Terminals** – Secure wire connections  
- **Pin Headers** – Direct interface with breadboard power rails  

---

## Design Workflow

The project followed a complete PCB development flow:

1. Schematic design with proper component selection  
2. Footprint assignment and PCB layout  
3. Power routing and grounding considerations  
4. Design Rule Check (DRC) verification  
5. 3D PCB visualization to validate placement and orientation  

This workflow ensures the design is **manufacturing-ready and easy to assemble**.

---

## Tools Used

- **KiCad** – Schematic capture, PCB layout, and 3D visualization  

---

## Applications

- Power supply for breadboard-based electronics projects  
- Testing sensors, microcontrollers, and logic circuits  
- Educational demonstrations of linear voltage regulation  
- Rapid prototyping in labs and personal projects  

---

## Project Status

- Schematic completed  
- PCB layout completed  
- DRC passed  
- Design ready for fabrication  

---

## Future Improvements

- Addition of protection features (reverse polarity, fuse)  
- Heat sink support for higher current operation  
- Optional dual-sided GND plane optimization  
- Current measurement or voltage monitoring features  

---

## Author

Designed and documented by **Hemant**  
Electronics & Telecommunication Engineering (ENTC)

---

## License

This project is shared for **educational and learning purposes**.

