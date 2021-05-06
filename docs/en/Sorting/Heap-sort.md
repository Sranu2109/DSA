# Heap Sort
Heap Sort is a comparison based sorting algorithm. It uses one of the tree concepts called Heap Tree. We use Max Heap to arrange list of elements in Descending order and Min Heap to arrange list of elements in Ascending order. 
### Complexity
Worst Case : O(n*logn)
Best Case : O(n*logn)
Average Case : O(n*logn)
Space Complexity : O(1)

## Steps
1. Construct a binary tree with given list of elements.
2. Transform the Binary Tree into Min Heap.
3. Delete the root elements from Min Heap using Heapify method.
4. Put the deleted element into the sorted list.
5. Repeat the same until Min Heap becomes empty and display.

## Example
Given array is 
**82 90 10 12 15 77 23** 

Sorted array is 
**10 12 15 23 77 82 90**

## Implementation
- [Java](../../../algorithms/Java/sorting/heap-sort.java)
- [C](../../../algorithms/C/sorting/heap-sort.c)
- [Python](../../../algorithms/Python/sorting/heap-sort.py)
- [C++](../../../algorithms/C++/sorting/heap-sort.cpp)

## Video URL
[Youtube Video about Heap Sort]( https://www.youtube.com/watch?v=HqPJF2L5h9U) 

## Others
[Wikipedia]( https://en.wikipedia.org/wiki/Heapsort)


