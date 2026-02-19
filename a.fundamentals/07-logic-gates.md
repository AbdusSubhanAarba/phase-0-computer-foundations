# 07 — Logic Gates

## Overview

Logic gates are the basic building blocks of digital circuits.

They take binary inputs (0 or 1) and produce a binary output.

Logic gates are built using transistors.  
All computation inside a computer is performed by combinations of logic gates.

---

## Why Logic Gates Exist

Transistors act as switches (on or off).

When transistors are combined in specific ways, they perform logical operations such as:

- AND
- OR
- NOT
- NAND
- NOR
- XOR
- XNOR

These operations allow computers to make decisions.

---

## Basic Logic Gates

### AND Gate

Output is 1 only if both inputs are 1.

Truth Table:

A | B | Output  
0 | 0 | 0  
0 | 1 | 0  
1 | 0 | 0  
1 | 1 | 1  

---

### OR Gate

Output is 1 if at least one input is 1.

Truth Table:

A | B | Output  
0 | 0 | 0  
0 | 1 | 1  
1 | 0 | 1  
1 | 1 | 1  

---

### NOT Gate

Reverses the input.

Truth Table:

A | Output  
0 | 1  
1 | 0  

---

## Advanced Logic Gates

### NAND Gate

NOT + AND combined.

Output is 0 only when both inputs are 1.

NAND gates are extremely important because any digital circuit can be built using only NAND gates.

---

### NOR Gate

NOT + OR combined.

Output is 1 only when both inputs are 0.

---

### XOR (Exclusive OR)

Output is 1 only when inputs are different.

Truth Table:

A | B | Output  
0 | 0 | 0  
0 | 1 | 1  
1 | 0 | 1  
1 | 1 | 0  

XOR is used heavily in arithmetic circuits.

---

### XNOR

Opposite of XOR.

Output is 1 only when inputs are the same.

---

## Why Logic Gates Matter in Computing

Logic gates are used to build:

- Adders (for arithmetic)
- Comparators
- Memory cells
- Registers
- CPU control units

Billions of logic gates inside a processor work together to execute instructions.

---

## From Logic to Computation

When logic gates are combined in layers, they form:

- Arithmetic Logic Units (ALUs)
- Control units
- Entire processors

Every software instruction ultimately becomes a series of logic gate operations.

---

## Summary

Logic gates are circuits built from transistors that perform basic logical operations on binary inputs.

They are the fundamental decision-making units of digital systems.

All modern computing is built from combinations of logic gates.
