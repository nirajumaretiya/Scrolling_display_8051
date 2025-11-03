# Scrolling Display using 8051 Microcontroller

This project implements a **scrolling text display** on a **16x2 LCD module** using an **8051 microcontroller**.  
It demonstrates low-level embedded programming, LCD interfacing, and timing-based message scrolling using **Keil µVision** and **Proteus**.

---

## 🧠 Project Overview

The goal of this project is to display a **continuous scrolling message** across a 16x2 LCD.  
The implementation focuses on:
- Understanding **LCD command and data interface protocols**  
- Generating precise **timing delays** for smooth text scrolling  
- Implementing **character shifting and buffer logic** using 8051 assembly  

---

## ⚙️ Hardware Requirements

- **AT89C51 / AT89S52 (8051 family)** microcontroller  
- **16x2 LCD module** (HD44780 compatible)  
- **Crystal oscillator** (11.0592 MHz recommended)  
- **Resistors**, **capacitors**, and **potentiometer** (for contrast control)  
- **Breadboard / PCB** and **jumper wires**

---

## 🧩 Software Tools

- **Keil µVision IDE** – for writing and compiling assembly code  
- **Proteus Design Suite** – for emulation and circuit simulation  
- **Flash Magic / USB ASP Programmer** – for uploading firmware to hardware (optional)

---

## 🚀 Features

- Smooth **horizontal scrolling** of alphanumeric text  
- Adjustable **scrolling speed** using delay loops  
- Modular assembly routines for **LCD initialization** and **data writing**  
- Works with standard **HD44780-compatible LCDs**

---

## 🧰 Getting Started

### 1️⃣ Compilation (Keil µVision)
1. Open the project or create a new **Keil µVision** project.  
2. Add the source file: `SCROLLING.asm`.  
3. Configure the target device as **AT89C51 / AT89S52**.  
4. Build the project to generate the **HEX file**.

### 2️⃣ Simulation (Proteus)
1. Open **Proteus Design Suite**.  
2. Create a new schematic with:
   - 8051 microcontroller (AT89C51 or AT89S52)
   - 16x2 LCD module  
   - Crystal oscillator (11.0592 MHz)
3. Connect LCD data and control pins to appropriate 8051 I/O ports.  
4. Load the compiled **HEX file** into the 8051 in Proteus.  
5. Run the simulation to view the **scrolling text** on the LCD.

---


