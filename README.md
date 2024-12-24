# Off-by-One Error in C++ Vector Iteration

This repository demonstrates a common off-by-one error that occurs when iterating through a `std::vector` in C++. The error arises from incorrectly using the `<=` operator in the loop condition, resulting in accessing an element beyond the vector's valid index range.

The `bug.cpp` file contains the erroneous code, while `bugSolution.cpp` provides the corrected version.  Understanding this error is crucial for writing robust and correct C++ code.