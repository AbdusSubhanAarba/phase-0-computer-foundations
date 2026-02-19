# 11 — How SSDs Store Data

## Overview

An SSD (Solid State Drive) is a storage device that stores data permanently using electronic memory.

Unlike RAM, SSDs are non-volatile, meaning they retain data even when power is removed.

SSDs use NAND flash memory to store information.

---

## What Makes an SSD Different

Unlike HDDs, SSDs:

- Have no moving parts
- Use electronic circuits
- Store data using trapped electrical charges
- Access data much faster

This makes SSDs:

- Faster
- More durable
- More energy efficient

---

## NAND Flash Memory

SSDs use NAND flash memory cells.

Each memory cell stores data by trapping electrons inside a special structure called a floating gate.

- Electrons trapped → represents one binary value
- No trapped electrons → represents the opposite value

These electrical states remain even when power is removed.

---

## How Data Is Written

To write data:

1. A high voltage is applied.
2. Electrons are forced into the floating gate.
3. The trapped charge changes the cell’s state.
4. The cell now represents a binary value.

Writing requires precise electrical control.

---

## How Data Is Read

To read data:

1. A small voltage is applied.
2. The system checks how easily current flows.
3. The presence or absence of trapped electrons changes conductivity.
4. The controller interprets the result as 0 or 1.

Reading is much faster than writing.

---

## Erasing Data

Data in NAND flash cannot be erased one bit at a time.

It must be erased in blocks.

A block contains many memory cells grouped together.

When erased:

- The stored charge is removed.
- All cells in that block reset.

This block-based erasing is why SSD controllers are complex.

---

## The SSD Controller

An SSD contains a controller chip that manages:

- Wear leveling
- Error correction
- Block management
- Logical-to-physical address mapping

The controller ensures:

- Even usage of memory cells
- Long lifespan
- Data integrity

Without the controller, NAND memory would degrade quickly.

---

## Why SSDs Are Fast

SSDs are fast because:

- No mechanical movement is required.
- Data is accessed electronically.
- Many memory cells can be accessed in parallel.
- NVMe SSDs connect directly through PCIe lanes.

This allows extremely high data transfer speeds.

---

## SSD vs RAM

SSD:
- Non-volatile
- Slower than RAM
- Used for long-term storage

RAM:
- Volatile
- Extremely fast
- Used for active processing

Programs move from SSD to RAM before execution.

---

## Summary

SSDs store data using NAND flash memory.

Binary values are represented by trapped electrical charges inside memory cells.

Data is permanent because the charge remains even when power is removed.

SSDs are fast because they rely entirely on electronic, not mechanical, processes.
