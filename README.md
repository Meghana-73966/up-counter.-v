
Verilog 4-Bit Up Counter

Project Overview

An Up Counter is a digital circuit that counts upward by 1 for every positive edge of the clock.

A 4-bit counter counts:

"0 → 1 → 2 → 3 → ... → 14 → 15 → 0"

After reaching "15", the counter automatically returns to "0".

Features

- 4-bit synchronous up counter
- Reset input
- Counts on every positive clock edge
- Automatically wraps from "15" to "0"
- Designed using Verilog HDL

 Project Files

File| Description
"README.md"| Project documentation
"up_counter.v"| Verilog design code
"up_counter_tb.v"| Testbench
"simulation_output.txt"| Expected simulation output

 Inputs and Outputs

Signal| Direction| Description
"clk"| Input| Clock signal
"reset"| Input| Resets counter to 0
"count"| Output| 4-bit counter output

 Working Principle

- When "reset = 1", the counter is reset to "0".
- When "reset = 0", the counter increases by "1" at every positive edge of the clock.
- Since the counter is 4-bit, the maximum value is "15".
- After "15", it returns to "0".

Counting Sequence

0 → 1 → 2 → 3 → 4 → 5 → 6 → 7
→ 8 → 9 → 10 → 11 → 12 → 13 → 14 → 15
→ 0 → ...

Tools Used

- Verilog HDL
- Icarus Verilog
- GTKWave
- GitHub

Applications

Up counters are commonly used in:

- Digital clocks
- Frequency counters
- Timers
- Event counters
- Digital electronics
- Control systems

 Author

meghana 

