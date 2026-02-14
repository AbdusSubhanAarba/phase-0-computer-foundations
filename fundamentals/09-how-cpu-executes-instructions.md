# 09 — How the CPU Executes Instructions

## Overview

The CPU (Central Processing Unit) executes instructions using a repeating process called the instruction cycle.

Every program — from a simple calculator to a web browser — is ultimately a sequence of instructions executed by the CPU.

These instructions are stored in memory as binary values.

---

## The Instruction Cycle

The CPU operates using a continuous three-step cycle:

1. Fetch
2. Decode
3. Execute

This process repeats billions of times per second.

---

## Step 1 — Fetch

The CPU retrieves the next instruction from memory (RAM).

- The instruction is stored at a specific memory address.
- The Program Counter (PC) holds the address of the next instruction.
- The instruction is copied into a special register inside the CPU.

At this stage, the CPU has the instruction but has not yet acted on it.

---

## Step 2 — Decode

The CPU determines what the instruction means.

Instructions may tell the CPU to:

- Add two numbers
- Move data between registers
- Compare values
- Jump to another location
- Read or write memory

The Control Unit interprets the binary pattern and activates the correct internal circuits.

---

## Step 3 — Execute

The CPU performs the required action.

Examples:

- Arithmetic operations are performed in the ALU (Arithmetic Logic Unit).
- Data may be written to memory.
- The Program Counter may change to a new location.

After execution, the cycle repeats with the next instruction.

---

## What Is Actually Happening Electrically

Inside the CPU:

- Transistors switch on and off.
- Logic gates evaluate binary inputs.
- Electrical signals move between registers.
- The clock synchronizes every operation.

Each instruction triggers a carefully coordinated pattern of electrical activity.

---

## The Role of the Clock

The CPU is synchronized by a clock signal.

The clock:

- Produces regular electrical pulses.
- Controls when instructions move forward.
- Ensures operations happen in sequence.

Higher clock speed means more cycles per second.

---

## Registers

Registers are small, very fast storage locations inside the CPU.

They hold:

- Instructions being processed
- Data used for calculations
- Memory addresses

Registers are critical for high-speed execution.

---

## Example Instruction Flow

If a program says:

Add 5 + 3

The CPU:

1. Fetches the add instruction.
2. Decodes it.
3. Loads values into registers.
4. Uses the ALU to compute 8.
5. Stores the result.

All of this happens through electrical switching in nanoseconds.

---

## Why This Matters

Understanding the instruction cycle explains:

- Why clock speed matters
- Why CPU architecture matters
- How programs become electrical operations
- How performance is determined

Software is ultimately a sequence of instructions executed electrically by the CPU.

---

## Summary

The CPU executes instructions using a repeating fetch–decode–execute cycle.

Instructions are stored in memory as binary.

The CPU interprets them and performs operations through coordinated transistor switching.

All program execution reduces to controlled electrical activity.
