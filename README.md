# project-nandtestris-part-1-project02
project-02
# Project 2 Repository Files

Below are the complete contents for the GitHub repository for **Nand2Tetris Project 2**. You can copy each block into separate files.

---

## 📌 `README.md`

```markdown
# Nand2Tetris – Project 2: Boolean Arithmetic

This repository contains the HDL implementations for **Project 2** of the Nand2Tetris course. The goal of this project is to build:

- `Add16` – a 16‑bit ripple‑carry adder
- `Inc16` – a 16‑bit incrementer
- `ALU` – a 16‑bit Arithmetic Logic Unit supporting a wide range of operations

These chips form the core arithmetic components of the Hack computer.

---

## 🚀 Files Included

| File | Description |
|------|-------------|
| `Add16.hdl` | 16‑bit adder using cascaded FullAdders |
| `Inc16.hdl` | 16‑bit incrementer implemented using Add16 |
| `ALU.hdl` | Hack ALU supporting zeroing, negation, AND/ADD, and output control |

All files are written in standard Nand2Tetris HDL and are fully compatible with the Hardware Simulator.

---

## 📘 Project Objective

Implement the basic arithmetic components of the Hack architecture by combining primitive logic gates previously implemented in Project 1.

---

## 🧪 Testing

The chips can be tested using the official Nand2Tetris test scripts:

- `Add16.tst`
- `Inc16.tst`
- `ALU.tst`

These scripts verify:
- Correct bitwise operations
- Ripple‑carry behavior
- Zero/negative output flags (for ALU)

---

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for more information.

---

## 📚 References

- *The Elements of Computing Systems*, Nisan & Schocken
- Official Nand2Tetris website: https://www.nand2tetris.org
- Course Part I – Projects 1–6

---

## 👨‍💻 Author

ARAVINDKUMAR GS – BE CSE, Meenakshi College of Engineering
```

---

## 📌 `DESCRIPTION.md`

```markdown
# Project Description – Nand2Tetris Project 2

### Overview
Project 2 focuses on implementing arithmetic chips using fundamental logic gates designed in Project 1.

### Chips Built
- **Add16** – Adds two 16‑bit binary inputs
- **Inc16** – Increments a 16‑bit binary number by 1
- **ALU** – Performs AND, ADD, negate, zero‑out, and output selection

### Learning Outcomes
- Understanding ripple‑carry addition
- Building hierarchical components
- Implementing control logic for ALU operations
- Working with multi‑bit buses in HDL
```

---

## 📌 `LICENSE`

```text
MIT License

Copyright (c) 2025 Aravind Kumar GS

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 📌 `REFERENCES.md`

```markdown
# References

These resources were used for completing the Nand2Tetris Project 2.

1. **The Elements of Computing Systems** – Noam Nisan & Shimon Schocken
2. Official Project Page: https://www.nand2tetris.org
3. HDL Survival Guide – Nand2Tetris Forum
4. Course Videos (Coursera – Part I)
5. Hack Architecture Documentation (Chapter 5)
