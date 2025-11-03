Scrolling Display using 8051 Microcontroller

This project implements a scrolling text display on a 16x2 LCD module using an 8051 microcontroller. It demonstrates low-level embedded programming, efficient use of timers, and direct LCD interfacing in assembly language.

🧠 Project Overview

The goal of this project is to display a continuous scrolling message across an LCD screen. The implementation focuses on:

Understanding LCD command and data interface protocols.

Generating precise timing delays for smooth scrolling.

Implementing character buffering and text shifting logic using 8051 assembly.

⚙️ Hardware Requirements

AT89C51 / AT89S52 (8051 family) microcontroller

16x2 LCD module (HD44780 compatible)

Crystal oscillator (11.0592 MHz recommended)

Resistors, capacitors, potentiometer (for contrast control)

Breadboard / PCB and jumper wires

🧩 Software Tools

Keil µVision IDE for assembly programming

Proteus Design Suite (for simulation and verification)

Flash Magic / USB ASP Programmer (for hardware flashing)

🚀 Features

Smooth horizontal text scrolling on LCD

Configurable scrolling speed through delay adjustment

Modular code structure with LCD initialization and write routines

Compatible with standard HD44780 16x2 LCDs
