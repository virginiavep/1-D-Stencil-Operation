# 1-D-Stencil-Operation
C Program demonstrating how to obtain memory addresses that implements a 1-D stencil operation
Prints out the memory address (& operator) and the size (sizeof operator) of each variable.
Array bracket operators act as address calculation operations which use the base+offset formula to determine the address of a specific array element.
Calculates the address of array element B[i] using an iterator so values can be assigned to it.
Performs the operation B2[i] = (B[i-1] + B[i] + B[i+1])/3.
Calculates the address of array element B2[i] so values can be read for printing.
