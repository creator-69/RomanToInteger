# RomanToInteger

A Python solution for converting a Roman numeral string into an integer.

## How it works

The `Solution.romanToInt()` method maps single-character numerals and the subtractive pairs `IV`, `IX`, `XL`, `XC`, `CD`, and `CM` to their numeric values. It scans the input from left to right, consuming a two-character pair when one is present; otherwise, it adds the current single-character value.

## Example

```python
from Roman import Solution

print(Solution().romanToInt("MCMXCIV"))  # 1994
```

## Run

Requires Python 3. Save the example above in a small script or call the method from a Python interpreter.

## Learning focus

Dictionary lookups, string slicing, loop boundaries, and handling subtractive Roman numeral pairs.

**Current limitation:** the method assumes valid Roman numeral input; it does not validate malformed strings.
