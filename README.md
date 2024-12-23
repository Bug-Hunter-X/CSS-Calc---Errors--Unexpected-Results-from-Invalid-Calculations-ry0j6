# CSS Calc() Errors: Unexpected Results from Invalid Calculations

This repository demonstrates an uncommon CSS bug related to the `calc()` function.  Incorrect mathematical expressions within `calc()` can lead to unexpected behavior, particularly when negative values are involved.  Different CSS properties handle negative values differently, making debugging challenging.

The `bug.css` file contains the problematic CSS, while `bugSolution.css` offers a corrected version.  See the detailed explanation in the respective files for a comprehensive understanding.

This bug is subtle and can be hard to identify.  Always carefully review and test your `calc()` expressions to prevent this type of error.