#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n^3) - quadratic


b) O(log(n)) - logarithmic


c) O(c^n) - linear

## Exercise II

Starting at the top - always cut search space in half using binary search. Should have a run time complexity of O(log(n)) because it is a binary search. So if the egg breaks at the top, go to the middle and try there. If it does break in the middle, we know that the floor is between middle and top and try there. If it does break at the throw in the middle, we know to keep going lower with the algorithm. Repeat this pattern of halving the number of floors you're dropping an egg at as much as necessary to find the floor.
