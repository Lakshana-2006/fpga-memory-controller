# FPGA Memory Controller (8×8) using Verilog

## 📌 Project Description

This project focuses on the design and implementation of a **synchronous memory controller** using **Verilog HDL** on an FPGA platform. The controller operates on an **8×8 memory array** and supports both **read and write operations synchronized with the clock signal**.

The design is verified through simulation using a testbench, making it suitable for **academic learning and beginner FPGA projects**.

---

## 🎯 Objectives

* Develop a synchronous memory controller using Verilog HDL
* Implement clock-based read and write operations
* Validate functionality using a testbench simulation
* Implement and demonstrate the design on an FPGA

---

## ⚙️ Design Specifications

| Parameter       | Value       |
| --------------- | ----------- |
| Memory Depth    | 8           |
| Memory Width    | 8 bits      |
| Address Width   | 3 bits      |
| Read Type       | Synchronous |
| Write Type      | Synchronous |
| Target Platform | FPGA        |

---

## 🧠 Block Diagram

![Block Diagram](docs/block_diagram.png)

---

## 💻 RTL Code

Location: `rtl/memory_controller.v`

---

## 🧪 Testbench

Location: `testbench/memory_controller_tb.v`

---

## 📊 Simulation Output

![Simulation Waveform](simulation/waveform.png)

---

## 🔧 FPGA Implementation

![FPGA Output](implementation/fpga_output.png)

---

## 🚀 Features

* Simple and beginner-friendly design
* Fully synchronous operation
* Modular Verilog implementation
* Easy to extend for larger memory

---

## 🛠 Tools Used

* Verilog HDL
* Vivado (for simulation)
* FPGA Board (Xilinx)

---

## 📚 Learning Outcomes

* Understanding of memory architecture
* Hands-on experience with Verilog coding
* Simulation and verification using testbench
* FPGA implementation basics

---

## 👩‍💻 Author

Lakshana M

---
