# Off-by-one error in array iteration

This repository demonstrates a common off-by-one error in Java when iterating over arrays. The `BuggyArray.java` file contains the erroneous code, which attempts to access an array element beyond its bounds.  The `FixedArray.java` file provides the corrected version.

The error is subtle, making it easy to miss during code review. It's crucial to carefully consider array bounds when iterating.

**To run the code:**

1.  Clone the repository.
2. Compile and run `BuggyArray.java`. Observe the `ArrayIndexOutOfBoundsException`.
3. Compile and run `FixedArray.java`. Observe the correct output.