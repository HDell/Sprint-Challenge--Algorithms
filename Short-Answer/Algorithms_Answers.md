#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a) The runtime for this snippet is O(n) due to the fact that the condition of the loop is checking whether a is less than n^3 and on each iteration n^2 is added to a. So if a increases by n^2 on each iteration, all that remains for the condition is whether a is less than n (as in n^1).

b) The runtime for this snippet is O(nlogn) due to the fact that the outer for loop is runs one operation per the size of the input, while the inner for loop doubles the size of an integer for each iteration that it is less than the size of the input.

c) The runtime for this snippet is O(n) because the amount of times the function runs directly correlates with the size of the input of the first time it is called. For example, if bunnyEars(2) is called, it will return 4, after having called bunnyEars(1) and subsequently calling the bunnyEars(0) base case.

## Exercise II
