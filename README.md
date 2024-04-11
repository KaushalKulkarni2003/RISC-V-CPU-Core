# RISC-V CPU Project

## Overview

This project aims to build a RISC-V CPU capable of executing instructions to perform basic arithmetic operations. Initially, the primary goal was to create a processor that could count the first 10 natural numbers using the ADDI (Add immediate) instruction. Subsequently, additional instructions were implemented to enhance functionality.

The CPU is developed using TL-Verilog Language on Makerchip software, facilitating efficient design and simulation.

## Implementation Steps

The implementation of the RISC-V CPU proceeded through the following steps:

1. **PC Logic:** Completed
2. **Instruction Memory:** Completed
3. **Decode Logic:** In Progress
4. **Register File Read**
5. **Arithmetic Logic Unit**
6. **Register File Write**
7. **Branch Logic**
8. **Jump Logic**
9. **Load, Store, and Data Memory**
![VIZ](LF_VIZ.png)

## Benefits of Makerchip Software

Makerchip software offers several advantages for developing and testing digital designs:

- **Visual Diagram Representation:** Provides visual aids for understanding the architecture and signal flow of the CPU.
- **Built-in Simulation Environment:** Eliminates the need for separate testbench development by providing waveform outputs directly within the software.
- **Signal Randomization:** Facilitates thorough testing by generating randomized signals for comprehensive simulation scenarios.

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository to your local machine.
2. Open the project in Makerchip software.
3. Explore the existing implementation and modify as needed.
4. Use the built-in simulation environment to test the CPU functionality.
5. Refer to the provided documentation or code comments for further details on specific components and functionality.

![Final Core](lib/riscv.svg)

## Finished!

Congratulations!!!

After completing this course, we hope you are inspired to continue your journey. These ideas might help:
  - Try the tutorials in [Makerchip](https://makerchip.com).
  - Learn more about [TL-Verilog](https://redwoodeda.com/tl-verilog).
  - Explore the [RISC-V](https://riscv.org) ecosystem.
  - Take [other courses](https://training.linuxfoundation.org/full-catalog/) from [Linux Foundation](https://www.linuxfoundation.org/)
  - Discover [other training](https://www.redwoodeda.com/publications) from [Redwood EDA, LLC](https://redwoodeda.com)
  - Get your core running on real hardware using FPGAs [in the cloud](https://github.com/stevehoover/1st-CLaaS) or [on your desktop](https://github.com/shivanishah269/risc-v-core/).
  - Install [TL-Verilog tools](https://www.redwoodeda.com/products).
  - Learn about the [WARP-V](https://github.com/stevehoover/warp-v) TL-Verilog CPU core generator.
