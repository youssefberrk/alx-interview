
```markdown
# 0x00. Pascal's Triangle

## Description

This project involves generating Pascal's Triangle, a triangular array of binomial coefficients. Each number is the sum of the two directly above it. Pascal's Triangle has various applications in mathematics, particularly in algebra and combinatorics.

## Table of Contents

- [Introduction](#introduction)
- [Usage](#usage)
- [Example](#example)
- [Files](#files)
- [Requirements](#requirements)
- [Installation](#installation)
- [Testing](#testing)
- [Author](#author)

## Introduction

Pascal's Triangle is a triangular array constructed as follows:
- The top row is `[1]`.
- Each subsequent row is formed by adding the number above and to the left with the number above and to the right, treating empty elements as `0`.

For example, the first five rows of Pascal's Triangle are:
```
     1
    1 1
   1 2 1
  1 3 3 1
 1 4 6 4 1
```

## Usage

This project includes a Python module that generates Pascal's Triangle up to a specified number of rows. You can use this module in your own projects or run it as a standalone script.

### Example Usage

```python
from pascals_triangle import generate_pascals_triangle

# Generate the first 5 rows of Pascal's Triangle
triangle = generate_pascals_triangle(5)
for row in triangle:
    print(row)
```

### Command Line Usage

You can also run the script from the command line to print Pascal's Triangle:

```sh
python pascals_triangle.py 5
```

This will output:
```
[1]
[1, 1]
[1, 2, 1]
[1, 3, 3, 1]
[1, 4, 6, 4, 1]
```

## Files

- `pascals_triangle.py`: Python module containing the function to generate Pascal's Triangle.
- `README.md`: This file.
- `tests/`: Directory containing unit tests for the module.

## Requirements

- Python 3.6 or higher

## Installation

Clone the repository to your local machine:

```sh
git clone https://github.com/youssefberrk/alx-interview.git
cd 0x00-pascals-triangle
```

## Testing

To run the tests, use the `unittest` module:

```sh
python -m unittest discover tests
```

## Author

Youssef Berrakouan

- GitHub: [youssefberrk](https://github.com/youssefberrk)
- Email: yberrakouan.lol@gmail.com
