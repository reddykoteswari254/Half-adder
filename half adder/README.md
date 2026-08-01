# Half Adder using Verilog

## Overview
A Half Adder is a combinational logic circuit that adds two single-bit binary numbers.

Inputs:
- A
- B

Outputs:
- Sum
- Carry

## Truth Table

| A | B | Sum | Carry |
|---|---|-----|-------|
|0|0|0|0|
|0|1|1|0|
|1|0|1|0|
|1|1|0|1|

## Logic Equations

Sum = A XOR B

Carry = A AND B

## Files

- half_adder.v → Verilog design
- half_adder_tb.v → Testbench
- simulation.png → Simulation waveform

## Tools Used

- Verilog HDL
- ModelSim / Vivado / Icarus Verilog
- GTKWave (optional)

## Author

Your Name