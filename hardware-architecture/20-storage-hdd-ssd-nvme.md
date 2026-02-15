# 20 — Storage: HDD, SSD, and NVMe

## Overview

Storage devices are used to permanently store data, including:

- Operating systems
- Applications
- Files
- System data

There are three main storage technologies:

- HDD (Hard Disk Drive)
- SSD (Solid State Drive)
- NVMe (Non-Volatile Memory Express)

Each differs in speed, architecture, and performance.

---

## HDD (Hard Disk Drive)

HDDs store data using magnetism on spinning disks.

Characteristics:

- Mechanical components
- Slower read/write speeds
- Higher latency due to physical movement
- Lower cost per gigabyte

Best suited for:

- Large storage capacity
- Backups
- Archives

---

## SSD (Solid State Drive)

SSDs store data electronically using NAND flash memory.

Characteristics:

- No moving parts
- Much faster than HDDs
- Lower latency
- More durable

SSDs use the SATA interface in many systems.

SATA limits maximum speed to approximately 550 MB/s.

---

## NVMe

NVMe is not a type of memory, but a communication protocol.

NVMe SSDs:

- Use NAND flash memory (like regular SSDs)
- Connect directly through PCIe lanes
- Bypass SATA limitations
- Achieve much higher speeds

PCIe allows multiple data lanes operating in parallel.

This enables speeds such as:

- 3,500 MB/s (PCIe 3.0)
- 7,000 MB/s (PCIe 4.0)
- Even higher in newer generations

---

## Key Differences

HDD:
- Magnetic storage
- Mechanical movement
- Slower
- Cost-effective

SATA SSD:
- Electronic storage
- Faster than HDD
- Limited by SATA interface

NVMe SSD:
- Electronic storage
- Uses PCIe lanes
- Much faster data transfer
- Lower latency

---

## Why NVMe Is Faster

NVMe improves performance because:

- It connects directly to the CPU through PCIe.
- It supports parallel command queues.
- It reduces protocol overhead.

This allows much higher throughput and responsiveness.

---

## Practical Impact

Using HDD:
- Slower boot times
- Slower application loading

Using SATA SSD:
- Faster system responsiveness
- Quick program launches

Using NVMe SSD:
- Extremely fast file transfers
- Faster large data processing
- Better performance in high-demand tasks

---

## Summary

HDDs store data magnetically and are slower but cost-effective.

SSDs store data electronically and are significantly faster.

NVMe is a high-speed protocol that allows SSDs to connect through PCIe, greatly increasing performance.
