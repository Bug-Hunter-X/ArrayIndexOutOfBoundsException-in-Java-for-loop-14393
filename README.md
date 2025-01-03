# Java ArrayIndexOutOfBoundsException Bug

This repository demonstrates a common Java programming error: an `ArrayIndexOutOfBoundsException` caused by an incorrect loop condition when iterating over an array.

The `BuggyArray.java` file contains the buggy code.  The `FixedArray.java` file provides the corrected version.

The bug is in the loop condition.  The loop iterates one time too many which cause an ArrayIndexOutOfBoundsException.

## How to reproduce the bug
1. Compile `BuggyArray.java`
2. Run the compiled code.
3. Observe the `ArrayIndexOutOfBoundsException`.

## How to fix the bug
1. Replace the faulty loop condition (`i <= arr.length`) in `BuggyArray.java` with the corrected condition (`i < arr.length`).
2. Compile and run the corrected code.
3. Verify that the program now runs without exceptions.