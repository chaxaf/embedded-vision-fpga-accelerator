# Embedded Vision FPGA Accelerator

## Overview

This project implements a hardware-accelerated image processing pipeline targeting FPGA-based embedded systems.

The objective is to offload computationally intensive vision operations from software to dedicated hardware modules, improving throughput and enabling real-time performance under constrained resources.

The system combines:
- custom hardware modules
- a virtual prototype environment
- software control logic

to form a complete embedded vision processing chain.

---

## System Architecture

The design is structured around a hardware/software co-design approach:

- **Hardware (FPGA modules)**
  - Image processing pipeline
  - Custom accelerators for compute-heavy operations
  - Memory interfaces and data movement

- **Software (control & integration)**
  - System orchestration
  - Configuration and execution flow
  - Interaction with hardware blocks

- **Virtual Prototype**
  - System-level simulation of the architecture
  - Validation of functionality before deployment

---

## Key Features

- Hardware-accelerated image processing pipeline
- Modular FPGA design
- Virtual prototyping environment for validation
- Separation between computation (hardware) and control (software)
- Configurable processing flow

---

## Repository Structure

```text
embedded-vision-fpga-accelerator/
├── virtual_prototype/
│   ├── modules/       # Hardware modules
│   ├── systems/       # System-level integration
│   ├── programms/     # Control / execution logic
│   └── README.md
├── docs/
│   ├── report.pdf     # Full technical report
│   └── presentation.pptx
├── assets/
│   └── images/
│       └── demo.png   # Example output / visualization
├── .gitignore
└── README.md
```

---

## Build and Execution

The project relies on a virtual prototyping environment and FPGA toolchain.

Typical workflow:

1. Configure system in `virtual_prototype/`
2. Build and run simulation
3. Validate processing pipeline behavior
4. Iterate on hardware/software partitioning

(See project report for full details)

---

## Results

The project demonstrates:

- Acceleration of image processing tasks using FPGA modules
- Reduction of CPU workload through hardware offloading
- Viability of hardware/software co-design for embedded vision systems

Detailed benchmarks and evaluation are available in the report.

---

## Technical Highlights

- Hardware/software partitioning of a vision pipeline
- Dataflow-oriented architecture design
- Memory and bandwidth considerations
- Modular FPGA design for scalability
- System-level validation using virtual prototyping

---

## Learning Outcomes

This project demonstrates:

- FPGA-based system design
- Embedded hardware/software co-design
- Performance-oriented architecture decisions
- System integration and validation workflows
- Structured engineering approach to complex systems

---

## Documentation

- Full technical details: `docs/report.pdf`
- Project presentation: `docs/presentation.pptx`

---

## Author

- Charlotte Heibig
