# ActionScript 3 ArrayIndexOutOfBoundsException
This repository demonstrates a common ActionScript 3 error: the `ArrayIndexOutOfBoundsException`.  The exception arises when trying to access an array element using an index that's either negative or larger than or equal to the array's length.  The example highlights the problem and provides a solution using a simple bounds check.

## How to Reproduce
1.  Clone this repository.
2.  Open `bug.as` in an ActionScript 3 editor (like FlashDevelop).
3.  Compile and run the code.  You'll see the exception being thrown.

## Solution
The solution, shown in `bugSolution.as`, incorporates a check to ensure the index is within the valid range before accessing the array element. This prevents the `ArrayIndexOutOfBoundsException`.