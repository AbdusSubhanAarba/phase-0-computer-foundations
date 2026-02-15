# 30 — BIOS and UEFI

## Overview

BIOS and UEFI are firmware systems stored on the motherboard.

They run immediately when the computer is powered on.

Their primary role is to initialize hardware and start the operating system.

---

## What Is Firmware?

Firmware is low-level software stored in non-volatile memory on hardware devices.

It:

- Controls hardware behavior
- Runs before the operating system
- Is stored on flash memory chips

BIOS and UEFI are types of motherboard firmware.

---

## What Is BIOS?

BIOS (Basic Input/Output System) is the traditional firmware used in older systems.

It performs:

- Hardware checks
- Basic initialization
- Boot device selection

BIOS has limited features and uses a legacy architecture.

---

## What Is UEFI?

UEFI (Unified Extensible Firmware Interface) is the modern replacement for BIOS.

It provides:

- Faster boot times
- Graphical interface
- Support for large storage drives
- Secure Boot functionality

Most modern systems use UEFI instead of legacy BIOS.

---

## What Happens at Startup

When power is applied:

1. The CPU begins execution.
2. The firmware is loaded from flash memory.
3. Hardware components are initialized.
4. A boot device is located.
5. The operating system loader is executed.

Firmware prepares the system before the OS takes control.

---

## POST (Power-On Self Test)

During startup, the firmware performs POST.

It checks:

- RAM
- CPU
- Storage devices
- Basic hardware functionality

If hardware fails, the system may:

- Emit error beeps
- Display error messages
- Refuse to boot

---

## Secure Boot

UEFI supports Secure Boot.

Secure Boot ensures:

- Only trusted software loads during startup.
- Unauthorized bootloaders are blocked.

This improves system security.

---

## Why BIOS/UEFI Matter

Without firmware:

- The CPU would not know how to initialize hardware.
- Storage devices would not be detected.
- The operating system would not load.

Firmware acts as the first control layer of the computer.

---

## Summary

BIOS and UEFI are motherboard firmware systems that initialize hardware and start the operating system.

UEFI is the modern and more advanced implementation.

They operate before the OS and prepare the system for boot.
