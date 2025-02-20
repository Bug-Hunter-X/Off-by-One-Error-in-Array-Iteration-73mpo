# Off-by-One Error in Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating over an array.  The `Bug.java` file contains the erroneous code, while `BugSolution.java` provides the corrected version.

The bug arises from an incorrect loop condition that attempts to access an index beyond the array's bounds.  This leads to an `ArrayIndexOutOfBoundsException` at runtime.  The solution shows how to adjust the loop condition to prevent this issue. 