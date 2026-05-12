# Sparta ION Repair & Restoration Project

This project is a functional, production-ready fork of the [InfantEudora/sparta_ion](https://github.com) repository.

## Overview

This repository implements a custom approach to repairing and restoring the functionality of all generations of the e-bikes popular in the Netherlands that feature the iconic **"banana-shaped" battery** and a **rear hub motor** (e.g., Sparta ION, Batavus, Koga).

## What's Inside

Everything needed to replicate or repair the electronics is included:

*   **Schematics:** Detailed circuit diagrams.
*   **PCB Files:** Design files ready for manufacturing (Gerber files).
*   **Firmware:** Source code and binaries for the microcontrollers.
*   **Documentation:** Step-by-step instructions for assembly, flashing, and system configuration. (in progress)

## Getting Started

1.  Review the **ion2\HW** to understand the hardware modifications.
2.  Order PCBs using the provided files in the `ion2\HW\BATT_ctrl_v3\Gerbers3.4` directory.
3.  Flash the microcontrollers using the code in the `ion2\batt_ctrl` and `ion2\bldc_mmu_firmware` folders.
4.  Follow the **ion2\docs** for final installation and tuning.

## Acknowledgments

This work is based on the original research and development found in the [sparta_ion](https://github.com) project.
![alt text](https://github.com/Virviglaz/sparta_ion/blob/master/ion2/docs/bike.jpg)


