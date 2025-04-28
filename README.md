# ESP3A-Class-AB-Audio-Amplfier
This project reverse engineers and simulates the ESP P3a 100W Class AB amplifier. I analyzed each analog stage, tuned biasing in LTSpice, and validated performance on a ±10V breadboard before designing a custom 2-layer PCB in KiCad.
This project documents my full reverse engineering, simulation, validation, and PCB implementation of the ESP P3a 100W Class AB audio power amplifier, a well-regarded discrete analog design by Rod Elliott.

As part of my goal become an electrical hardware engineer, I studied the internal behavior and purpose of each stage (input differential, current mirror, VAS, bias, output, and feedback), reproduced the schematic in LTSpice, tuned biasing parameters, and ultimately implemented the circuit on both breadboard (±10V rails) and a custom 2-layer PCB designed in KiCad.

Key Highlights:
Reverse engineered ESP P3a from schematics and functional descriptions

Simulated quiescent current, FFT/THD, slew rate, and stability (Bode plot)

Breadboard-tested at reduced voltage to verify bias and zero-crossing behavior

Designed PCB with proper trace widths for >3A output paths (2.3mm)

Included thermal and power considerations for TO-264 output transistors

This repo includes:

Full annotated schematic

LTSpice simulations

Final KiCad PCB layout

Design notes and lessons learned
