# RV32I Pipelined Processor

## Overview

This project involves designing and implementing a 5-stage pipelined processor supporting the RV32I instruction set. The processor is written in Verilog and targeted for an FPGA environment. The goal is to create an efficient and versatile processor architecture capable of handling a range of applications.

## Key Features

- **5-Stage Pipeline:** Designed a pipeline comprising fetching, decoding, execution, memory, and write-back stages for improved instruction overlap and execution speed.

- **Unified Memory Handling:** Addressed challenges related to unified memory for instructions and data using a dual-clock mechanism for efficient load instructions.

- **Efficient Instruction Execution:** Developed an Immediate Generator for quick generation of immediate values and a Forwarding Unit to handle data hazards, ensuring smooth execution.

- **Control Units:** Implemented specialized control units and an ALU control unit to generate precise control signals based on opcode and other inputs.

- **Bonus Features:** Extended functionality by adding support for multiplication, division, and remainder instructions, enhancing the processor's versatility.

## Contribution

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
