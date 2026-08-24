# NumPy — Features and Installation

## Overview

NumPy is a Python library used for numerical computing and working efficiently with arrays.

It provides concise and readable code and allows mathematical operations to be performed directly on arrays. This makes code more Pythonic and can reduce the need for repetitive `for` loops.

---

## Key Features of NumPy

### 1. Concise and Readable Code

NumPy allows mathematical operations to be expressed in a way that closely resembles standard mathematical notation.

For example, mathematical operations such as:

* Addition
* Subtraction
* Multiplication
* Division

can be performed directly on arrays.

This makes numerical code easier to write, read, and maintain.

---

### 2. Vectorization

Vectorization allows operations to be performed element-by-element on arrays without explicitly writing traditional `for` loops.

Instead of repeatedly processing individual elements using loops, NumPy can perform operations directly on an entire array.

This results in:

* More concise code
* More readable code
* Less repetitive code
* More efficient numerical operations

The source highlights that nested or multiple loops can become difficult to understand and maintain, while NumPy provides a more Pythonic approach.

---

### 3. Broadcasting

Broadcasting is one of NumPy's important features.

It allows operations between arrays with different shapes when the smaller array can be expanded to match the shape of the larger array in an unambiguous way.

#### Basic Idea

```text
Array A        Array B
[1, 2, 3]   +     10

Result
[11, 12, 13]
```

The scalar value is applied element-by-element to the array.

Broadcasting can therefore make array calculations much simpler without manually changing the dimensions of the data.

---

## Installation

### Step 1 — Install Python

Before installing NumPy, Python needs to be installed on the system.

Python can be downloaded from:

**https://www.python.org/downloads/**

The source recommends having a recent version of Python installed.

After installation, verify Python from the terminal:

```bash
python --version
```

You can also open Python and execute Python commands directly.

---

### Step 2 — Install NumPy

After Python is installed, NumPy can be installed using `pip`.

```bash
python -m pip install numpy
```

Using `python -m pip` ensures that the package is installed through the Python interpreter being used.

The source demonstrates installing the required packages from the command prompt and notes that packages are downloaded and installed successfully.

---

## Other Useful Libraries

The tutorial also mentions installing libraries commonly used alongside NumPy, including:

* **NumPy** — numerical computing and arrays
* **Matplotlib** — graphical/data visualization
* **Pandas** — data structures and data manipulation
* **SciPy** — scientific computing

These libraries can be installed using `pip`.

```bash
python -m pip install numpy matplotlib pandas scipy
```

After installation, the packages can be imported into Python programs.

---

## 🔍 Verify NumPy Installation

After installing NumPy, its installed version can be checked from Python.

```python
import numpy as np

print(np.__version__)
```

The tutorial demonstrates checking the installed NumPy version after completing the installation. The version shown in the tutorial is **1.16.4**.

> **Note:** The version shown in the tutorial is historical. Your installed version may be different depending on when you install NumPy.

---

## Basic Example

```python
import numpy as np

numbers = np.array([1, 2, 3, 4, 5])

result = numbers * 2

print(result)
```

### Output

```text
[ 2  4  6  8 10]
```

This demonstrates NumPy's element-by-element operation and its concise syntax.

---

## Concepts Learned

| Concept              | Description                                                         |
| -------------------- | ------------------------------------------------------------------- |
| NumPy                | Python library for numerical computing                              |
| Vectorization        | Performing operations on arrays without explicit loops              |
| Broadcasting         | Performing operations between compatible arrays of different shapes |
| Array Operations     | Mathematical and logical operations performed on arrays             |
| NumPy Installation   | Installing NumPy using Python's package manager                     |
| Version Checking     | Checking the installed NumPy version                                |
| Supporting Libraries | Matplotlib, Pandas and SciPy                                        |

---

## Learning Summary

In this tutorial, I learned the basic features and installation process of NumPy.

### Main Takeaways

1. NumPy makes numerical code more concise and readable.
2. Vectorization reduces the need for repetitive `for` loops.
3. Broadcasting allows operations between compatible arrays of different shapes.
4. Python must be installed before installing NumPy.
5. NumPy and other Python libraries can be installed using `pip`.
6. The installed NumPy version can be verified using `np.__version__`.

These concepts provide a foundation for working with NumPy arrays and performing numerical operations in Python.

---

## References

* Python: https://www.python.org/
* NumPy: https://numpy.org/
* Matplotlib: https://matplotlib.org/
* Pandas: https://pandas.pydata.org/
* SciPy: https://scipy.org/

