# CS 245 (Fall, 2018) PracticeAssignment02
Big O notation for function wait time-

Iterative Function:
This function is O(n) because the function contains one for loop which will run the if statement within it n times. everything else in the function is either a constant or nondominant.

Recursive Function:
This function is also O(n). This is because each statement within it is just O(1) but to the fact its recursive and the base case compares the index counter to the length of the array given, it is O(n).
