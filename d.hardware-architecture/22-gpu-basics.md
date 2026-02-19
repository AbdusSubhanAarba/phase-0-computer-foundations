# 22 — GPU Basics

## Overview

A GPU (Graphics Processing Unit) is a specialized processor designed to handle parallel computations.

Originally built for rendering graphics, GPUs are now also used for:

- Video processing
- Scientific simulations
- Artificial intelligence
- Machine learning
- Data processing

GPUs excel at handling many similar tasks simultaneously.

---

## GPU vs CPU

The CPU is optimized for:

- General-purpose processing
- Complex logic
- Sequential tasks
- Operating system control

The GPU is optimized for:

- Massive parallel workloads
- Repetitive mathematical operations
- Pixel and image processing

CPUs have fewer powerful cores.
GPUs have thousands of smaller cores designed for parallel work.

---

## GPU Cores

GPU cores perform simple arithmetic operations.

They are designed to execute the same instruction on multiple data points at once.

This is ideal for:

- Rendering millions of pixels
- Matrix calculations
- Vector processing

Parallel execution increases throughput significantly.

---

## VRAM (Video Memory)

A dedicated GPU contains its own memory called VRAM.

VRAM stores:

- Textures
- Frame buffers
- 3D models
- Rendering data

Having dedicated memory prevents the GPU from competing with system RAM.

---

## Integrated vs Dedicated GPU

Integrated GPU:
- Built into the CPU
- Shares system RAM
- Lower power consumption
- Lower performance

Dedicated GPU:
- Separate hardware component
- Has its own VRAM
- Higher performance
- Used for gaming and professional workloads

---

## How the GPU Works

When rendering an image:

1. The CPU sends instructions to the GPU.
2. The GPU divides the task across many cores.
3. Each core processes a portion of the data.
4. The final image is assembled and sent to the display.

All of this is implemented using transistors and electrical switching.

---

## Why GPUs Matter

Modern applications rely heavily on GPUs for:

- High-resolution graphics
- Real-time rendering
- AI model training
- Complex visual effects

Without GPUs, performance in graphics-intensive tasks would be severely limited.

---

## Summary

A GPU is a parallel processor designed for handling large numbers of similar computations efficiently.

It complements the CPU by accelerating graphics and mathematical workloads.
