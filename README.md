# FPGA Reduced Instruction Set Computer (RISC) Project

## Introduction

The project involves designing, building, and testing a simple multi-cycled Reduced Instruction Set Computing (RISC) processor using Verilog.

## Project Features

- **RISC Processor Design:** Implements a simple RISC processor architecture.
- **Verilog Implementation:** Written in Verilog hardware description language.
- **Simulation and Testing:** Includes testbenches for thorough verification of the processor.
- **FPGA Deployment:** Configured to run on an FPGA development board (DE1-Soc).

## Supported Instructions

The processor can execute a variety of ARM instructions. The following diagram illustrates the ARM instruction encodings that the machine can run:
![294788885-803b9642-d9c8-4102-ba90-291692835259](https://github.com/user-attachments/assets/79f892f6-46ba-4f79-8f29-117b0704b804)
![294788895-0a883541-2534-45bb-bd96-481d11b98fd3](https://github.com/user-attachments/assets/640ce76f-16c8-49fe-a44b-0b1ef5f74b38)

## Hardware Components

- **FPGA Board:** DE1-SoC development board
- **Processor Design:** Custom RISC processor implemented in Verilog
- **Memory:** On-chip memory for instruction and data storage

## Software Description

### Verilog Code

The processor is designed in Verilog and includes several modules for different components of the processor. The main design files are:

- `RISC_top.sv`: Top-level module for the RISC processor
- `cpu.sv`: Central Processing Unit module
- `datapath.sv`: Datapath module
- `alu.sv`: Arithmetic Logic Unit module
- `instruction_decoder.sv`: Instruction Decoder module
- `finite_state_machine.sv`: Finite State Machine module
- `regfile.sv`: Register File module
- `shifter.sv`: Shifter module

### Testbenches
- `cpu_tb.sv`: Testbench for the CPU
- `datapath_tb.sv`: Testbench for the datapath
- `RISC_top_tb.sv`: Testbench for the top-level module
- `RISC_check.sv`: Verification module

## Project Demonstration

- A video demonstration of the RISC processor in action voiced by my partner Afeef can be found linked here: https://youtu.be/biTuX5kdb8c

## Future Improvements

- Enhance the processor design to support more complex instructions.
- Implement pipelining for improved performance.
- Expand the testbench coverage to include more edge cases and scenarios.

## Contributors
Steven Chen, Afeef Mir Ruwayd

