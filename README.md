# Max Sub-Array W9D3

Understanding the Problem
-Inside each array, find the connecting sub-array with the greatest sum. The sub-array must have at least one number.
---Example Array = [1, 2, 3, -2, 3, 6]; Max Sub-Array = [3, 6]

-Input = Array of Integers (i.e., nums)
-Output = Max Sub-Array (see above e.g.)

Approach & Optimization
Kadane's algorithm has a time complexity of O(n). This means that the time to complete the task is based on the size of the input (i.e., n). In this case, it is the length of the array. The strength of this approach is that it iterates over the list once (i.e., O(n)) and keeps a running sum at each element of the array.
