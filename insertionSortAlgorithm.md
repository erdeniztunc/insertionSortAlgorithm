# Insertion Sort:

Insertion sort compares the elements one by one and places them in the correct position.

If we sort the set of numbers [7, 3, 5, 8, 2, 9, 4, 15, 6] according to the insertion sort algorithm, we follow the steps below:

Starting from the second element of the list, we place each element in its correct position by comparing it with the elements preceding it.

We repeat this process until the end of the list.

In the first step, we place 3 to the left of 7 since 3 is less than 7 in the array [7, 3, 5, 8, 2, 9, 4, 15, 6] and [3, 7, 5, 8, 2, 9, 4, 15, 6]

Next, we move the 5 to the left of the 7, the 2 to the left of the 3, the 9 to the right of the 8, and the 4 to the left of the 9, sequentially moving them to their correct positions:

[3, 5, 7, 8, 2, 9, 4, 15, 6]
[2, 3, 5, 7, 8, 9, 4, 15, 6]
[2, 3, 5, 7, 8, 9, 4, 15, 6]
[2, 3, 4, 5, 7, 8, 9, 15, 6]
[2, 3, 4, 5, 6, 7, 8, 9, 15]

As a result, the string [7, 3, 5, 8, 2, 9, 4, 15, 6] becomes [2, 3, 4, 5, 6, 7, 8, 9, 15] sorted according to the insertion sort algorithm.

### Big O Notation of Insertion Sort

The Big O representation of the Insertion sort algorithm is O(n^2). This means that the running time of the algorithm will increase quadratically as the number of elements to be sorted (n) increases. That is, the insertion sort algorithm is not suitable for use on large data sets. However, it can be used as a fast and efficient sorting method on small datasets.

### Time Complexity
18 is an average case as it is located near the middle.

## Selection Sort

It finds the smallest element in the array and replaces it with the first element, then replaces the smallest element with the second element, and so on until the sorting is complete.


[7,3,5,8,2,9,4,15,6] Write the first 4 steps of the sequence according to the Selection Sort.

Solition:
[7,3,5,8,2,9,4,15,6]

[2,3,5,8,7,9,4,15,6]

[2,3,4,8,7,9,5,15,6]

[2,3,4,5,7,9,8,15,6]

[2,3,4,5,6,9,8,15,7]