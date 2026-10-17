# Silicon Studio Abstract

Silicon Studio is an integrated digital chip design environment built on top of a customized fork of Visual Studio Code. It transforms a familiar software development IDE into an end-to-end Electronic Design Automation (EDA) toolchain.

By seamlessly integrating industry-standard open-source tools such as Yosys, ABC, Verilator, Icarus Verilog, OpenROAD, and KLayout, Silicon Studio enables developers to traverse the entire IC design flow from a single interface. The flow spans RTL writing (Verilog/SystemVerilog), linting, and simulation, through synthesis, floorplanning, power planning, placement, clock-tree synthesis, routing, signoff-style timing and power extraction, all the way to final GDSII layout generation.

Key features include:
- A stage navigator for ten distinct physical design steps.
- Real-time layout viewing and exploration of floorplan scenarios.
- Run reproducibility, snapshotting, and exporting as a handoff bundle.
- Built-in Synopsys-style command shells (DC, ICC2, PrimeTime) interacting natively with the underlying open engines.

Silicon Studio brings the agility, rich language features, and simplicity of VS Code to hardware design, offering a modern, accessible, and reproducible approach to digital chip creation.
