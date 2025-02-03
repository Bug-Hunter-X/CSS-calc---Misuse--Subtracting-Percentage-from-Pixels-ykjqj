# CSS calc() Misuse: Subtracting Percentage from Pixels

This repository demonstrates a common error when using the `calc()` function in CSS: attempting to subtract a percentage from a fixed pixel value. This often leads to unexpected layout issues and inconsistent rendering across different browsers.

The `bug.css` file contains the incorrect CSS, while `bugSolution.css` provides the corrected code.

## Problem

The browser struggles to resolve the subtraction of a percentage from a pixel value, leading to layout inconsistencies.  The percentage is calculated relative to *what*?

## Solution

The solution restructures the calculation to ensure that all values are either percentages or pixels.  If you need to subtract a percentage from a fixed dimension, you might need to use JavaScript to calculate the value dynamically.