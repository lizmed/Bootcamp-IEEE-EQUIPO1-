<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works
This project is a simple Half Adder circuit designed to perform binary addition using two 1-bit inputs (A and B).
The circuit uses two logic gates:
XOR Gate: Calculates the Sum (S) output.
AND Gate: Calculates the Carry (C) output.
The Half Adder adds the two binary inputs and produces two outputs: the sum bit and the carry bit.
The Boolean expressions are:
Sum: S = A ⊕ B
Carry: C = A · B
| Input A | Input B | Sum (S) | Carry (C) |
|:-------:|:-------:|:-------:|:---------:|
|    0    |    0    |    0    |     0     |
|    0    |    1    |    1    |     0     |
|    1    |    0    |    1    |     0     |
|    1    |    1    |    0    |     1     |

## How to test
Follow these steps to test the Half Adder simulation:
Click the green Play button to start the simulation.
Change the binary input values using the input switches (A and B).
Press the Step button to advance the clock and update the circuit.
Observe the output LEDs and seven-segment display to verify the Sum (S) and Carry (C) results.
Repeat the process for all four possible input combinations and compare the results with the truth table.

## External hardware

No external physical hardware is required. This project is implemented and tested entirely in a digital circuit simulation environment.
The simulation includes:
Input switches for binary values (A and B).
XOR and AND logic gates.
Clock and reset controls.
Output LEDs to indicate the Sum and Carry signals.
A seven-segment display for output visualization.
