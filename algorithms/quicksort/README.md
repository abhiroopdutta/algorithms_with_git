# Quicksort

This is a divide and conquer sorting algorithm, it takes an array, picks an element as pivot(in our implementation, we pick the last element as pivot), and partitions the array around the pivot, i.e., all the elements less than the pivot are moved to the left side of it, and those greater are moved to the right side. This process is repeated again and again for the sub-arrays that are formed on the left and right side in each iteration.

Average case running time - O(nlogn)
Worst case running time - O(n^2)

### Input Format

- The input consists of two lines.
- In the first line, there will be a single integer **N** (number of elements).
- In the second line, there will be **N** integer elements.

### Output Format

- A single line consisting of the sorted array with space separated elements.

### Sample Input

```
6

6
5
4
3
2
1

 
```

### Sample Output

```
 1 2 3 4 5 6
```

### Implemented in:

- [C++](quicksort.cpp)

