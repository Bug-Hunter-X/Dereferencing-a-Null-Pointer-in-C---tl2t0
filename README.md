# Dereferencing a Null Pointer in C++

This repository demonstrates a common error in C++: dereferencing a null pointer.  Dereferencing a null pointer means trying to access the memory location pointed to by a pointer that is currently set to null. This usually results in a segmentation fault or a crash.

The `bug.cpp` file contains the erroneous code. The `bugSolution.cpp` file shows how to correctly handle pointers to avoid this error.

**How to reproduce:**
1. Compile the `bug.cpp` code.
2. Run the compiled executable.
3. Observe the segmentation fault or unexpected behavior.

**Solution:**
Always check if a pointer is null before attempting to dereference it.  The corrected code includes this check to prevent the error. 