# Hybrid-Relay-MOSFET-DC-Motor-Driver
DCMotorDriver-Relay-MOSFET

A compact and cost-effective bidirectional brushed DC motor driver that combines **relay-based direction control** with **MOSFET-based PWM speed control**. The design provides H-bridge-like functionality while significantly reducing the number of power switching devices required.

---

##  Highlights

- Designed a **hybrid motor driver** using only:
  - 2 × SPDT Relays
  - 1 × Power MOSFET
  - 2 × Relay Driver Transistors
  - 1 × Mosfet Driver Transistor
- Achieved **bidirectional motor control** by reversing motor polarity through relays.
- Implemented **PWM-based speed control** using a single low-side MOSFET.
- Reduced component count compared to a conventional MOSFET H-bridge.
- Built a design that can be easily scaled for **high-power DC motors** by replacing only the MOSFET and relays with higher-rated components.
- Eliminated H-bridge shoot-through issues through mechanical direction switching.
- Designed the complete **schematic** and **PCB layout** from scratch.

---

## ⚙️ Working Principle

- Two SPDT relays determine the motor rotation direction by swapping the motor terminals.
- A single MOSFET controls the motor's ground path and receives a PWM signal for speed regulation.


---

## ✨ Features

- Bidirectional motor control
- PWM speed control
- Low component count
- Simple control interface
- High-current scalability
- Easy-to-design PCB
- Cost-effective alternative to conventional H-bridge drivers

---

## 🔧 Hardware Used

- IRFZ44N Power MOSFET
- 2 × SPDT Relays
- 2 × BC547 NPN Transistors
- 7805 Voltage Regulator
- Flyback Diode
- Passive Components (Resistors, Connectors)

---

## 🎯 Applications

- Mobile Robots
- Electric Actuators
- Conveyor Systems
- DIY Automation Projects
- High-Current Brushed DC Motor Control

---

## 📚 Engineering Concepts

- Power Electronics
- PWM Motor Speed Control
- Relay-Based Direction Switching
- MOSFET Switching
- Brushed DC Motor Control
- PCB Design
- Hardware Cost Optimization

---

## ⚠️ Limitations

- Not suitable for applications requiring rapid direction changes.
- Designed specifically for brushed DC motors.

---

## 📄 License

This project is released under the MIT License.
