# Off-by-One Error in Java Array

This repository demonstrates a common off-by-one error in Java that can lead to an `ArrayIndexOutOfBoundsException`. The `bug.java` file contains the erroneous code, while `bugSolution.java` provides the corrected version.

The error occurs due to an incorrect loop condition in the array traversal. The loop iterates one time too many, causing an attempt to access an index that is beyond the array's valid range.  This is a frequent mistake in programming and highlights the importance of careful array indexing.