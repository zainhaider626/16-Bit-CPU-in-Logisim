# 16 Bit CPU in Logisim

A 16 bit processor datapath built from gates, registers and arithmetic blocks in Logisim Evolution, with a dot matrix display for visual output.

## Overview

This project extends the principles of a simple 8 bit design to a 16 bit data width. Each major block is a separate sub circuit, and the processor drives a frame buffer so results can be seen on a dot matrix display and a terminal.

## Architecture

| Block | Purpose |
|---|---|
| Program counter | Counter with clock enable and reset control |
| Accumulator | Primary register for arithmetic results |
| B register | Second ALU operand |
| X and Y registers | Additional working registers with separate read and write control |
| ALU | Add, subtract, AND, OR, XOR, NAND, NOR and NOT operations |
| Comparator | Equal, greater and less comparison |
| Flags register | Carry, borrow, zero, equal, greater and less flags |
| Frame buffer | Stores pixel data for the dot matrix display |
| Output | Dot matrix display and TTY terminal |

Control signals such as `ADD`, `SUB`, `JUMP`, `HALT` and `RESET` are exposed as labeled inputs, with a manual clock tick for step by step execution.

## Repository Contents

| Path | Description |
|---|---|
| `circuit/CPU16Bit.circ` | Complete CPU project |

## Running the Simulation

1. Install [Logisim Evolution](https://github.com/logisim-evolution/logisim-evolution) version 4.0 or newer.
2. Open `circuit/CPU16Bit.circ` and select the `main` circuit.
3. Enable clock ticks with `Ctrl + K`, or step manually with the tick control.
4. Observe the registers, flags and display while the CPU runs.

## Author

Zain Haider, Hardware and Robotics Engineer. Co founder of Robetix and founder of [Nvisco](https://nvisco.com).
