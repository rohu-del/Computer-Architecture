# 🧪 Lab 2: VHDL Code for Realizing Logic Gates

## 🎯 Objective
- Write VHDL code for basic logic gates: **AND, OR, NOT, NAND, NOR, XOR, XNOR**  
- Simulate each gate and verify its truth table using **GTKWave**

---

## 📖 Theory
Logic gates are the fundamental building blocks of all digital circuits.  
Each gate performs a basic Boolean operation on one or more binary inputs to produce a single binary output.

---

## 🔑 Gate Operators and Boolean Expressions

| Gate   | VHDL Operator | Boolean Expression |
|--------|---------------|--------------------|
| AND    | `and`         | Y = A · B          |
| OR     | `or`          | Y = A + B          |
| NOT    | `not`         | Y = A̅              |
| NAND   | `nand`        | Y = (A · B)̅        |
| NOR    | `nor`         | Y = (A + B)̅        |
| XOR    | `xor`         | Y = A ⊕ B          |
| XNOR   | `xnor`        | Y = (A ⊕ B)̅        |

---

## Output

![image](gates.png)

## 💬 Discussion
We explored how different logic gates function and implemented them using **VHDL**.  
Each gate was described with its Boolean expression and tested through simulation.  
The outputs were verified against the expected truth tables using **GTKWave**.

---

## ✅ Conclusion
- Successfully implemented **seven basic logic gates** in VHDL.  
- Verified their functionality by simulating and observing waveforms.  
- Learned how Boolean algebra maps directly into VHDL operators and how simulation tools like GTKWave help confirm correctness.

---
