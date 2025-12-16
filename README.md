# Automatic-Lamp-Controller

## Overview
This project simulates an **automatic lamp system** with independent control of **servo motors and LEDs**, implemented on an **FPGA Cyclone III (EP3C16F484C6)**. The system provides multiple operating modes for both motors and LEDs, demonstrating concepts of **digital design, hardware description languages, and embedded control**.

The design combines a **VHDL-based core** with a **Verilog wrapper**, enabling full functionality of the simulated device.

---

## Hardware and Tools
- **FPGA:** Cyclone III – EP3C16F484C6  
- **Servo Motors:** SG90  
- **HDLs:** VHDL (core) and Verilog (integration layer)  
- **Simulation and Development Tools:**
  - Intel Quartus II 13.1
  - ModelSim

---

## System Features

### Motor Control
The system supports three operating modes for the servo motors:
- **Horizontal movement**
- **Vertical movement**
- **Rotational movement**

---

### LED Control
The LEDs operate independently from the motors and support three modes:
- **On**
- **Blink**
- **Fade** (smooth transition effect)

---

## Simulation Setup
To simulate the automatic lamp behavior, a physical-inspired configuration was replicated:

- **LED Assembly:**  
  LEDs were modeled as being soldered onto a metal container, representing their physical placement and light emission.

- **Motor Integration:**  
  The LED assembly was attached to two servo motors, responsible for **rotational** and **vertical** movements.

- **Horizontal Motion Structure:**  
  An additional structure was modeled to enable **horizontal movement**, completing the lamp’s range of motion.

This setup allows the simulation to closely resemble the behavior of a real automatic lamp with combined mechanical and lighting control.

---

## Implementation Details
- Core logic implemented in **VHDL**
- System integration and interfacing implemented in **Verilog**
- Functional verification performed using **ModelSim**
- Synthesis and project management performed in **Quartus II**

![Imagem do WhatsApp de 2023-12-11 à(s) 23 53 39_7c6eaff8](https://github.com/cyberdebb/abajur-automatico/assets/107296659/ad33e1a0-e33f-4b7d-b476-13cc5579c4a8)

---

## Notes
- This project focuses on **simulation and digital design concepts**
- Intended for **educational and experimental purposes**
