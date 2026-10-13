# Half Adder in Verilog

## Overview
A beginner digital logic project implementing a half adder using Verilog HDL.

## Inputs
- A: First 1-bit input
- B: Second 1-bit input

## Outputs
- Sum = A XOR B
- Carry = A AND B

## Truth Table
| A | B | Sum | Carry |
|---|---|---|---|
| 0 | 0 | 0 | 0 |
| 0 | 1 | 1 | 0 |
| 1 | 0 | 1 | 0 |
| 1 | 1 | 0 | 1 |

## Files
- `half_adder.v`: RTL design
- `half_adder_tb.v`: Testbench

## Verification
The testbench applies all four possible input combinations. Run it using a Verilog simulator and check the output against the truth table.

## Tools
Verilog HDL; a compatible Verilog simulator is required for testing.
