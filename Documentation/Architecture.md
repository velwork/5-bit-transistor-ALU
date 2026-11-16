# Architecture notes

The ALU contains a 5-bit Ripple Carry Adder built from five Full Adder stages, separate AND, OR, and XOR logic units, an operation decoder, an output multiplexer, and input/selection circuitry.

Supported opcodes: `000` ADD, `001` SUB, `010` AND, `011` OR, `100` XOR.
