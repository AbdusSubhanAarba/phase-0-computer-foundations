# 31 — How a Computer Boots

## Overview

Booting is the process that starts a computer and loads the operating system into memory.

It begins the moment the power button is pressed and ends when the operating system takes control.

Booting transforms powered hardware into a usable system.

---

## Step 1 — Power On

When the power button is pressed:

- The Power Supply Unit (PSU) activates.
- AC power is converted to DC.
- Electricity flows to the motherboard, CPU, RAM, and storage.

The CPU becomes active.

---

## Step 2 — Firmware Execution

The CPU begins executing instructions from a fixed memory address.

This location points to firmware (BIOS or UEFI) stored on the motherboard.

Firmware starts running immediately.

---

## Step 3 — Hardware Initialization

The firmware:

- Performs POST (Power-On Self Test).
- Checks RAM, CPU, storage, and basic devices.
- Initializes hardware settings.

If errors are detected, the system may stop or display diagnostic messages.

---

## Step 4 — Locate Boot Device

The firmware searches for a bootable device, such as:

- SSD
- HDD
- USB drive
- Network source

It looks for a bootloader on the selected device.

---

## Step 5 — Load the Bootloader

A bootloader is a small program stored on the boot device.

It is responsible for:

- Loading the operating system kernel into RAM.
- Preparing the system for OS control.

Examples include:

- Windows Boot Manager
- GRUB (Linux)

---

## Step 6 — Load the Operating System

The bootloader loads the OS kernel into RAM.

The kernel:

- Takes control of the CPU.
- Initializes drivers.
- Starts system services.
- Mounts the file system.

At this point, the operating system is active.

---

## Step 7 — User Interface

After system initialization:

- The login screen appears.
- User credentials are verified.
- The desktop environment loads.

The computer is now ready for use.

---

## Electrical Perspective

During boot:

- Transistors switch billions of times.
- Instructions execute in sequence.
- Memory is populated with system data.
- Control transfers from firmware to the OS.

Booting is an organized chain of electrical events.

---

## Why Booting Matters

Understanding the boot process explains:

- Why corrupted firmware prevents startup.
- Why missing bootloaders cause errors.
- Why hardware failures stop initialization.
- How secure boot protects systems.

Booting connects hardware, firmware, and software into a working system.

---

## Summary

Booting is the process of powering hardware, executing firmware, loading a bootloader, and starting the operating system.

It transforms electrical hardware into an operational computing environment.
