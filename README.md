# Object-Oriented Modeling of Electronic Circuits

This repository contains C++ and SystemC assignments and projects focused on object-oriented hardware modeling, RTL design, and processor architecture. 

These projects demonstrate a progression from basic logic simulation in C++ to advanced RTL design and instruction set simulation using SystemC.

## 🗂️ Projects Overview

### [HW1: Simulation Engines](./HW1_Simulation_Engines)
* A study of continuous time, cycle based, and event-based simulation engines[cite: 11].

### [HW2: Basic Logic Simulation](./HW2_Basic_Logic_Simulation)
* Implementation of a cascadable 8-bit comparator using logic functions[cite: 10]. 
* Design and C++ simulation of a Mealy machine that detects a 11010 sequence[cite: 10].

### [HW3: Gate Classes](./HW3_Gate_Classes)
* Development of a cascadable comparator and an 8-bit register using C++ gate classes[cite: 9]. 
* Building a circuit that holds the largest of all incoming 8-bit data[cite: 9].

### [HW4: Polymorphism](./HW4_Polymorphism)
* Using the flipflop abstract class to develop JK and T flip-flops[cite: 8]. 
* Cascading four T flip-flops to develop a modulo-16 synchronous up-counter[cite: 8].

### [HW5: SystemC RTL & BFM](./HW5_SystemC_RTL_Divider)
* Designing an 8-bit sequential divider at the RT level for unsigned integers[cite: 7]. 
* Extending the system to handle signed integer division using a bus interface without modifying the internal logic[cite: 7].

### [HW6: SAYAC ISS & Custom Instructions](./HW6_SAYAC_Custom_Instructions)
* Accelerating drone navigation by computing distance and angle using custom instructions on the SAYAC embedded system[cite: 6]. 
* Implementing a C program for the calculation and running it on the SAYAC ISS[cite: 6]. 
* Adding custom instructions to the SAYAC ISA[cite: 6].

## 🛠️ Technologies & Tools
* **Languages:** C++, SystemC, C
* **Concepts:** Object-Oriented Hardware Design, RTL Modeling, Instruction Set Simulation (ISS), Mealy/Moore State Machines, Datapath & Controller Design.

---
*Developed as part of the Object-Oriented Modeling of Electronic Circuits course at the University of Tehran.*
