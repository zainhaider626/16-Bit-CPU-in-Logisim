# 16-Bit CPU Architecture in Logisim

## 📌 Project Overview
This project goes beyond basic logic circuits—it is an exploration of how a processor truly “thinks” at scale. Scaling up to a 16-bit architecture introduces advanced challenges in bus routing, memory addressing, and data flow. By recreating the exact fundamentals that power modern embedded processors from the ground up, this project demonstrates complete CPU execution in a simplified, highly visual environment.

## 💻 Core Specifications
* **Architecture:** 16-bit (expanded data range: 0–65,535).
* **Program Counter:** 16-bit with synchronous clock and reset control, enabling a vastly larger memory address space.
* **Accumulator Register:** 16-bit central unit for heavy arithmetic and logic results.
* **ALU (Arithmetic Logic Unit):** Supports advanced 16-bit addition, subtraction, AND, OR, XOR, and high-speed comparison operations.
* **Control Unit:** Hardwired to decode complex machine instructions, generate precise control signals, and orchestrate wider data flow across the internal bus.
* **General Purpose Registers (I/O):** Expanded for smooth, high-bandwidth communication with external inputs and outputs.
* **RAM Integration:** 16-bit word-addressable temporary memory for larger program instructions and data storage.
* **ROM / Instruction Set:** A custom set of predefined machine-level instructions optimized for 16-bit operations.
* **Output:** Connected to a multi-digit Hex/7-Segment Display array to visualize 16-bit real-time computation results.
* **Cycle Execution:** Implements the classic, robust Fetch → Decode → Execute instruction cycle.

## 🎯 Key Highlights
* **From Gates to CPU:** Shows how fundamental binary logic and flip-flops scale into a highly capable, complete working processor.
* **Real-World Parallels:** Demonstrates the exact same instruction cycle used by commercial processors—built visibly into a 16-bit framework.
* **Functional Execution:** Goes beyond basic simulation; this CPU actually executes complex instructions step-by-step with real-time visible output.
* **Practical Learning:** Deepened my practical understanding of instruction pipelining, extended memory management, control flow, and hardware-software interaction.

## ✨ Conclusion & Future Outlook
Every powerful processor—from the one in a smartphone to supercomputers running AI—is built on these exact same principles. By designing this 16-bit CPU, I have bridged the gap between theoretical logic and practical hardware design, strengthening my foundation in computer architecture. 

This project is a massive leap forward in my journey toward creating more advanced embedded systems, and exploring how custom hardware innovation can drive the future of intelligent robotics and real-world automation.


## How to Run the Simulation
1. Download and install [Logisim](http://www.cburch.com/logisim/).
2. Clone this repository or download the `.circ` files.
3. Open the main circuit file in Logisim.
4. Load your 16-bit machine code or test program into the ROM module.
5. Enable the clock ticks (`Ctrl + K` or `Simulate > Ticks Enabled`) to watch the flip-flops update and the CPU execute the code.
