# Java Data Structures and Algorithms
Notes for data structures and algorithms. Language used is Java.

## Data Structures

### Arrays and ArrayList

### LinkedList

### Stacks

### Queues

## Object-Oriented Programming

## Time and Space Complexity

## Recursion

What is Recursion?

## Sorting Algorithms

### Linear Search

What is Linear Search?

### Binary Search

What is Binary Search?

Used for sorted arrays. 

Given a target value or index position, find the middle position or value of an array or list. Then, if the target is less than the middle, only search from the start of the array/list to the middle position.

This is because in a sorted array, all of the smaller numbers are on the left side of the array or list.

If the target is greater than the middle, only search from the middle of the array/list to the end.

This is because in a sorted array, all of the larger numbers are on the right side of the array or list.

Otherwise, if the target is the same as the middle, there is no need to search either side.

In both search cases (left and right searching), you are only searching half of the array and this is what makes it a binary search.

Why use binary search?
It is a more optimized search than linear search.

In the best case scenario, the target element is the middle element. So, there is no searching that would be required. The time complexity would be constant: O(1)

In the worse case scenario, the maximum number of comparisons is the size of the array divided by 2: n/2

With each search, the array size (n) to search will be reduced aka divided in half (divided by 2): 
- first search: n/2 
- 2nd search: n/2^2
- 3rd search: n/2^2, etc.

Generically this would be n/2^k = 1, where k is the number of searches and 1 is ultimately what we would eventually get n/2^k to equal. 

To find the time complexity, we need to solve for the exponent k: n = 2^k

We apply log (multiply log on both sides) to solve an exponential equation, to get rid of the exponent and solve for k. This makes the equation: log(N) = log(2^k)

This is simplified to: logN = k 

Remember, the exponent comes down (gotten rid of it) when multiplied by log.

So, the time complexity would be: O(logN)

### Bubble Sort

What is Bubble Sort?

### Selection Sort

What is Selection Sort?

Select an element and move it (sort it) to its correct position.

### Insertion Sort

What is Insertion Sort?

### Cycle Sort

What is Cycle Sort?

### Merge Sort

What is Merge Sort?

### Quick Sort

What is Quick Sort?
