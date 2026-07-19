# ARMOS Architecture (Conceptual Reference & PoC)

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![Architecture: ARM64](https://img.shields.io/badge/Architecture-ARM64%20%2F%20aarch64-orange.svg)]()
[![Stage: Academic Research / PoC](https://img.shields.io/badge/Stage-Research%20%26%20PoC-green.svg)]()

An open-source **Architectural Reference** and **Proof-of-Concept (PoC)** for **ARMOS**, a unified, hybrid operating system environment designed for foldable hardware. 

The core mission of **ARMOS** is to demonstrate the technical feasibility of running native mobile (`.apk`) and desktop Linux (`.deb`) runtimes concurrently under a **single, shared Linux Kernel**, without binary translation or virtualization overhead, while maintaining the host system's strict security baselines.

---

## 💡 The Core Vision

Modern ARM64 SoCs possess desktop-class computing power, yet mobile operating systems artificially restrict user autonomy and productivity. Conversely, traditional desktop environments lack the interface fluidity, power management, and sensor integration required for mobile hardware.

**ARMOS** breaks this wall by proposing a system that is unified on the inside and adaptive on the outside:
*   **No Dual-Boot or Emulation:** Native execution of both mobile and desktop runtimes directly on the `arm64` CPU.
*   **Adaptive Liquid UI:** A single user session that dynamically transitions from a touch-focused mobile layout to a multi-window desktop workstation based on the folding state of the hardware.
*   **Unified Data Persistence:** A single file explorer orchestrating data transparently, bypassing storage fragmentation.

---

## 🏗️ Architectural Blueprint
