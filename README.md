# CS211: Computer Organisation

This repository contains coursework assignments for **CS211: Computer Organisation**, completed during Semester 1, 2025. The projects focus on solving computational problems using machine language, assembly language, and digital logic design.

---

## 👤 Author Information
* **Name:** Ronil Prasad
* **Student ID:** S11231541
* **Institution:** University of the South Pacific

---

## 📂 Repository Structure

### 📁 [Assignment 1](./A1/) — Wombat 1 Machine Language
Development of a machine language program for the Wombat 1 architecture to compute a specific piecewise function:
* **Mathematical Function $f(n)$:**
    * $n^2$ for $n < 1$
    * $n - 5$ for $n = 1$
    * $n^2 + 3n + 1$ for $n > 1$
* **Key Concepts:** Binary instruction formatting (opcode/operand), direct memory addressing, and conditional jumps.
* **Main File:** `S11231541.txt`.

### 📁 [Assignment 2](./A2/) — Wombat 2 Assembly Language
Modification of the Wombat computer to support **Stack** operations and **Subroutines**. This program implements the logic from Assignment 1 using structured programming:
* **Subroutines Included:**
    * `input_check`: Pops $n$ from the stack and determines the calculation path.
    * `Print`: Handles the final output display.
    * `case_1`/`case_2`/`case_3`: Specific subprograms for each mathematical condition.
* **Components:** Custom machine definition file (`Wombat2.cpu`) and assembly source code.

### 📁 [Assignment 3](./A3/) — Digital Logic Circuits
Implementation of a digital logic circuit using **Logisim** based on a provided schematic.
* **Functionality:** A circuit designed to process inputs $A$, $B$, and $Cin$ to produce outputs $S$ (Sum) and $Cout$ (Carry Out).
* **Key Deliverables:** * Logisim circuit file (`A3.circ`) utilizing NAND gate logic.
    * Truth table documentation covering all 8 input combinations.

---

## 🛠️ Tools Used
* **CPUSim:** For executing and testing Wombat machine and assembly code.
* **Logisim (v2.7.1):** For digital circuit design and simulation.

---

## ⚖️ License & Academic Integrity
This project is submitted for academic grading. All rights reserved.

**Academic Integrity Notice:** These materials are intended to showcase personal academic progress. Do not copy or distribute these files for plagiarism purposes, in accordance with the University's academic integrity policies.
