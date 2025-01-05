# Unexpected Behavior with CSS calc() for viewport width

This repository demonstrates a problem with the CSS `calc()` function when calculating the width of an element based on the viewport width. The calculated width is smaller than expected.  The `bug.css` file contains the problematic CSS, while `bugSolution.css` offers a solution.

## Bug Report

The expected behavior is that the element's width should be 50% of the viewport width. However, the actual width is significantly smaller.

## Solution

The issue is likely due to the presence of other styles or incorrect use of `calc()`. The solution may involve checking for conflicting styles, ensuring correct unit usage, and confirming the element's parent container dimensions.