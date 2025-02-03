# Bubble Sort in Python
This is a Python implementation of the Bubble Sort algorithm, which is a simple comparison-based sorting algorithm. It works by repeatedly stepping through the list, comparing adjacent elements, and swapping them if they are in the wrong order. With each pass through the list, the largest unsorted element "bubbles" up to its correct position.

# How It Works
Traversal: The algorithm repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order.
Bubble Up: After each pass, the largest unsorted element bubbles up to its correct position at the end of the list.
Reduction: The range of comparison is reduced after each pass, since the largest elements are already sorted and placed at the end.

# Time Complexity
Best case (already sorted): O(n)
Average and Worst case: O(n²)
Bubble Sort is easy to understand but not efficient for large datasets. It is mainly used for educational purposes or when simplicity is prioritized over performance.

# Limitations
Efficiency: The algorithm has a time complexity of O(n²) in the average and worst cases, which makes it slow for large datasets.
Not suitable for large inputs: While it’s easy to implement and understand, it is not efficient compared to other sorting algorithms like Quick Sort, Merge Sort, or Heap Sort when handling large arrays.

# License
This code is provided as-is and can be used freely for educational purposes.

