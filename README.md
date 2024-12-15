# Uncommon CSS `calc()` Errors and Debugging

This repository demonstrates some uncommon errors that can occur when using the `calc()` function in CSS and how to debug them.  The `calc()` function is powerful, but improper use can lead to subtle, hard-to-find bugs.

## Bugs

The `bug.css` file contains examples of:

- Invalid arithmetic within `calc()` (e.g., missing closing parenthesis)
- Incorrect unit mixing within `calc()` (e.g., adding pixels and percentages)

## Solutions

The `bugSolution.css` file provides corrected versions of the problematic CSS code. The solutions carefully address unit consistency and proper use of mathematical operators.  Good comments explaining the corrections are included. 

## Debugging Tips

- **Browser Developer Tools:** Use your browser's developer tools (usually F12) to inspect the calculated values of your CSS properties.  This can reveal the actual values being used, helping pinpoint where the calculation goes wrong.
- **Simplify:** Break down complex `calc()` expressions into smaller, simpler parts to isolate potential issues.
- **Unit Consistency:** Ensure you are using compatible units in your calculations. Avoid directly adding or subtracting different units without conversion.
- **Parentheses Matching:** Pay close attention to parentheses to ensure proper order of operations. 