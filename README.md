# 74HCng
ngspice model for 74HC logic gate. This library is forked from https://ngspice.sourceforge.io/experimental/74HCng.lib
This library can be used for simulating logic circuits in KiCAD.

# Features
Previous simulation model in the 74HCng.lib has only 3 + 2 pins (in1 in2 out vcc gnd).
But this library has 3 * 4 + 2 pins (74HC04 has 2 * 6 + 2 pins). So you can easily to simulate logic gates.

# Suppported series
* 74HC00 (NAND)
* 74HC02 (NOR)
* 74HC08 (AND)
* 74HC32 (OR)
* 74HC86 (XOR)
* 74HC04 (NOT)

# LICENSE
[MIT License](/LICENSE)
