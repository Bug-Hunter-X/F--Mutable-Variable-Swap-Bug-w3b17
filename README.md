# F# Mutable Variable Swap Bug

This repository demonstrates a common error encountered when working with mutable variables in F#. The provided code attempts to swap the values of two mutable variables using a swap function. However, due to the way F# handles mutable variables within functions, the swap operation does not produce the expected outcome.

The `bug.fs` file contains the erroneous code, while `bugSolution.fs` offers a corrected version that addresses the issue. The primary cause of the error is improper handling of mutable variables within the scope of the function.  The solution utilizes techniques to ensure the values are correctly exchanged.