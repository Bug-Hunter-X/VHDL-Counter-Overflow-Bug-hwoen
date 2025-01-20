# VHDL Counter Overflow Bug
This repository demonstrates a common bug in VHDL code: an integer counter that overflows without proper handling. The `buggy_counter.vhdl` file contains the buggy code, while `fixed_counter.vhdl` provides a corrected version.

## Bug Description
The original counter increments indefinitely, causing an integer overflow when it reaches its maximum value (15). This can lead to unexpected behavior in the system.

## Solution
The corrected code in `fixed_counter.vhdl` uses a modulo operation to wrap the counter back to 0 after it reaches 15, providing a more controlled and predictable behavior.
