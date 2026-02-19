# 10 — RAM and Volatile Memory

## Overview

RAM (Random Access Memory) is the computer’s temporary working memory.

It stores data and instructions that the CPU is actively using.

RAM is called volatile memory because it loses all stored data when power is removed.

---

## What RAM Does

RAM holds:

- Active programs
- Operating system processes
- Temporary calculation data
- Currently used files

The CPU reads from and writes to RAM constantly during operation.

Without RAM, the CPU would have no fast place to access instructions.

---

## Why It Is Called "Random Access"

Random access means:

- Any memory location can be accessed directly.
- The CPU does not need to search sequentially.
- All memory addresses are reachable in roughly equal time.

This makes RAM extremely fast compared to storage drives.

---

## How RAM Stores Data

RAM stores data using electrical states.

Modern RAM uses tiny electronic circuits made from transistors and capacitors.

Each memory cell stores a bit (0 or 1) as:

- Charged state → 1
- Uncharged state → 0

These stored charges represent binary data.

---

## Why RAM Is Volatile

The stored charge inside RAM cells slowly leaks away.

To maintain data:

- RAM must be continuously powered.
- Memory cells are refreshed thousands of times per second.

If power is lost:
- The electrical charge disappears.
- All stored data is erased.

This is why unsaved work is lost during power failure.

---

## RAM vs Storage

RAM:
- Fast
- Temporary
- Directly accessed by CPU
- Erased when power is off

Storage (SSD/HDD):
- Slower than RAM
- Permanent
- Used for long-term data

When you open a program:
1. It is loaded from storage.
2. It is copied into RAM.
3. The CPU executes it from RAM.

---

## Capacity and Performance

More RAM allows:

- More programs to run simultaneously.
- Larger files to be processed.
- Less reliance on slow storage.

Insufficient RAM causes the system to use virtual memory (disk swapping), which reduces performance.

---

## Why RAM Matters in Computing

RAM acts as the CPU’s workspace.

The CPU cannot efficiently operate directly from storage devices.

RAM provides the speed necessary for real-time processing.

All modern software depends on fast, volatile memory.

---

## Summary

RAM is temporary, high-speed memory used by the CPU to store active data and instructions.

It stores binary information using electrical charges.

When power is removed, all stored data is lost.
