# GCD Calculator Documentation

## Overview

The GCD Calculator is a lightweight Python package designed to compute the Greatest Common Divisor (GCD) of two integers using the efficient Euclidean algorithm. It provides a simple interface for developers and mathematicians to quickly determine GCD values in their applications.

## Features

- Calculates the GCD of two integers.
- Utilizes the efficient Euclidean algorithm for fast computation.
- Easy to install and use.

## Installation

To install the GCD Calculator package, use pip:

```bash
pip install gcd_calculator
```

## Usage

After installation, you can use the GCD Calculator in your Python projects as follows:

```python
from gcd_calculator.gcd import gcd

# Example usage
result = gcd(10, 5)
print(f"The GCD of 10 and 5 is: {result}")  # Output: The GCD of 10 and 5 is: 5
```

### Function Details

The package provides the following function:

```python
def gcd(a: int, b: int) -> int:
    """Calculate the GCD of two integers a and b."""
```

- **Parameters**:
  - `a` (int): The first integer.
  - `b` (int): The second integer.
  
- **Returns**: 
  - int: The GCD of `a` and `b`.

### Example

Here's an additional example demonstrating the use of the `gcd` function:

```python
# Calculate GCD of two numbers
result1 = gcd(48, 18)
print(f"The GCD of 48 and 18 is: {result1}")  # Output: 6

result2 = gcd(100, 75)
print(f"The GCD of 100 and 75 is: {result2}")  # Output: 25
```

## Contributing

Contributions are welcome! If you would like to contribute to the GCD Calculator, please follow these steps:

1. Fork the repository.
2. Create your feature branch: `git checkout -b my-feature`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin my-feature`.
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Author

**Usmonov Shoxruxmirzo**  
Email: [usmonovshohruxmirzo@gmail.com](mailto:usmonovshohruxmirzo@gmail.com)  
GitHub: [webbro-software](https://github.com/webbro-software)

---

![PyPI Downloads](https://static.pepy.tech/badge/gcd-calculator)

