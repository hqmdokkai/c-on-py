# My C Library

My C Library is a Python package that allows you to execute C code from within Python. It uses a C extension to provide fast execution of C code, making it suitable for performance-critical applications.

## Features

- Execute arbitrary C code from Python.
- Lightweight and easy to use.
- Fast execution due to native C performance.

## Installation

You can install the package using pip:

```bash
pip install c_on_py
```
Usage
Here's a quick example of how to use the library:
import c_on_py

#Execute C code to print the sum of 5 and 1
my_c_library.c("printf(\"%d\\n\", 5 + 1);")
Development
