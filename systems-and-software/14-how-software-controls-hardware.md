# 14 — How Software Controls Hardware

## Overview

Software controls hardware by sending structured instructions that are translated into electrical signals.

At a high level:

Application → Operating System → Device Driver → Hardware → Electrical Signals

All hardware behavior is ultimately triggered by software instructions executed by the CPU.

---

## Step 1 — Application Level

When you interact with a program (for example, clicking a button):

- The application generates instructions.
- These instructions request services from the operating system.

Applications do not directly control hardware.

---

## Step 2 — Operating System

The operating system acts as a manager.

It:

- Interprets requests from applications.
- Determines which hardware resources are needed.
- Ensures safe and controlled access.

The OS prevents applications from directly manipulating hardware.

---

## Step 3 — Device Drivers

Device drivers are specialized software components that:

- Translate OS instructions into hardware-specific commands.
- Understand the electrical and communication requirements of the device.

Each hardware component has its own driver.

Examples:
- Graphics driver
- Network driver
- Storage driver

Drivers act as translators between software and physical components.

---

## Step 4 — CPU Execution

When software instructions reach the CPU:

- They are converted into machine code.
- The CPU executes them using the fetch–decode–execute cycle.
- Electrical signals are sent to the appropriate hardware interface.

The CPU becomes the control center for all hardware activity.

---

## Step 5 — Electrical Response

Once hardware receives signals:

- Transistors switch.
- Voltage levels change.
- Mechanical or electronic actions occur.

Examples:

- GPU renders pixels.
- Storage reads or writes data.
- Network card transmits packets.
- Speaker converts signals to sound.

All actions are physical processes triggered by electrical control.

---

## Example: Pressing a Key

1. You press a key.
2. The keyboard sends an electrical signal.
3. The OS receives the signal through a driver.
4. The application interprets the input.
5. The CPU processes it.
6. The screen updates.

This entire chain happens in milliseconds.

---

## Why This Structure Matters

This layered structure ensures:

- Stability
- Security
- Hardware abstraction
- Efficient resource usage

Without this separation, systems would be unstable and unsafe.

---

## Summary

Software controls hardware through a layered system:

Applications request actions.
The operating system manages access.
Device drivers translate commands.
The CPU executes instructions.
Electrical signals trigger physical responses.

All hardware behavior is the result of software-controlled electrical switching.
