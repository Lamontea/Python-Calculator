# Python-Calculator
A calculator written in Python which can do addition, subtraction, multiplication, subtraction, remainder, and exponents

## Features
- Simple CLI: prompts for two numbers and a single operator
- Supported operators: `+`, `-`, `*`, `/`, `%`, `**` (exponent)
- Basic validation for division/modulo by zero and invalid operations
- modulo supports floats 

## Files
- `Python Calc V1` — the main CLI calculator script (run this file)
- `README.md` — this file

## Requirements
- Python 3.6+

## Notes:
- Division and modulo by zero will be rejected with an error message.
- Inputs are parsed as floats, so operations on floats are supported (e.g. `5.5 % 2`).

## Examples
- Addition: `2 + 3` -> `2.0 + 3.0 = 5.0`
- Exponent: `2 ** 3` -> `2.0 ** 3.0 = 8.0`
- Remainder: `5 % 2` -> `5.0 % 2.0 = 1.0`
