# CSS `calc()` Unexpected Behavior with Percentages and Other Units

This repository demonstrates an unexpected behavior of the `calc()` function in CSS when combining percentages and other units.  The calculated value doesn't produce the expected result.  The `bug.css` file shows the problematic code. The solution is provided in `bugSolution.css`.

**Problem:** The `width` of the element is not calculated correctly. The expected width is 50% + 50px = 200px (assuming a parent container of 300px width). The actual width varies and is incorrect. 

**Solution:** Using only percentages or pixels for the calculation, avoiding the mixed unit types.