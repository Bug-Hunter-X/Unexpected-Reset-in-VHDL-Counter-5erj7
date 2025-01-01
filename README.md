# Unexpected Reset in VHDL Counter

This repository demonstrates a common error in VHDL code involving an unintended reset within a counter. The `buggy_counter.vhd` file contains the flawed code, while `fixed_counter.vhd` provides a corrected version.

The issue stems from the way the counter is reset within the `if` statement. A more robust and typical approach involves using a modulo operation to ensure smooth cycling without explicit resets.