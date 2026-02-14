# 12 — How HDDs Store Data

## Overview

An HDD (Hard Disk Drive) is a storage device that stores data using magnetism.

Unlike SSDs, HDDs use mechanical components to read and write data.

HDDs are non-volatile, meaning they retain data even when power is removed.

---

## Main Components of an HDD

An HDD contains:

- Spinning magnetic disks (platters)
- A read/write head
- An actuator arm
- A motor

The platters rotate at high speeds (commonly 5400 or 7200 RPM).

---

## How Data Is Stored

Each platter is coated with a magnetic material.

Data is stored by magnetizing tiny regions on the surface.

Each region can be magnetized in one of two directions:

- One direction → represents 1
- Opposite direction → represents 0

These magnetic states remain even when power is off.

---

## How Data Is Written

To write data:

1. The disk spins.
2. The actuator arm moves the read/write head to the correct location.
3. The head generates a magnetic field.
4. That magnetic field changes the orientation of tiny regions on the platter.

This process physically changes magnetic alignment.

---

## How Data Is Read

To read data:

1. The disk spins.
2. The read head passes over magnetized regions.
3. Changes in magnetic orientation induce small electrical signals.
4. The system interprets those signals as binary data.

Reading depends on detecting magnetic differences.

---

## Why HDDs Are Slower

HDD performance is limited by mechanical movement:

- The disk must spin.
- The head must move to the correct position.
- Mechanical delays add latency.

This is much slower than electronic access in SSDs.

---

## Advantages of HDDs

Despite being slower, HDDs:

- Offer large storage capacity.
- Are generally cheaper per gigabyte.
- Are useful for backups and archives.

---

## HDD vs SSD

HDD:
- Uses magnetism
- Contains moving parts
- Slower access time
- Lower cost per gigabyte

SSD:
- Uses electronic memory
- No moving parts
- Much faster
- More durable

---

## Why HDDs Still Matter

For large-scale storage:

- Backups
- Media libraries
- Data archives

HDDs remain cost-effective.

However, for operating systems and applications, SSDs provide significantly better performance.

---

## Summary

HDDs store data by magnetizing tiny regions on spinning disks.

Binary values are represented by magnetic orientation.

Because they rely on mechanical movement, HDDs are slower than SSDs but remain useful for large-capacity storage.
