UART Controller RTL-to-GDSII ASIC Flow

RTL Design → Synthesis → Floorplan → Placement → CTS → Routing → STA → DRC → LVS → GDSII

This project builds upon my earlier UART Controller RTL implementation, which focused on functional design and simulation.

Original repository:
https://github.com/spandanfoldt/UART-controller

This repository extends that work through the complete ASIC implementation flow using OpenLane 2 and the Sky130 PDK, covering synthesis, floorplanning, placement, clock tree synthesis, routing, physical verification, and GDSII generation.

Verification Results

✔ RTL Simulation Passed
✔ Logic Synthesis Completed
✔ Floorplanning Completed
✔ Placement & Routing Completed
✔ DRC Passed
✔ LVS Passed
✔ Antenna Checks Passed
⚠ KLayout XOR reported one minor difference between Magic and KLayout generated GDS (1 XOR difference), while LVS and DRC both passed successfully.
