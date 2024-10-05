# Sorting Algorithms

This repository provides implementations of several sorting algorithms, widely used in computer science for ordering data. These algorithms differ in terms of complexity, efficiency, and use cases. Below is an introduction to each of them.

## 1. Bubble Sort

**Description**:  
Bubble Sort is one of the simplest sorting algorithms that repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order. The process repeats until the list is sorted.

**Time Complexity**:

- Best: O(n) (when already sorted)
- Average: O(n²)
- Worst: O(n²)

**Space Complexity**: O(1)

**Use Case**:  
Best for small data sets or when the list is almost sorted.

## 2. Selection Sort

**Description**:  
Selection Sort divides the list into a sorted and an unsorted section. It repeatedly selects the smallest (or largest, depending on the order) element from the unsorted section and moves it to the sorted section.

**Time Complexity**:

- Best: O(n²)
- Average: O(n²)
- Worst: O(n²)

**Space Complexity**: O(1)

**Use Case**:  
Simple and effective for small lists but not suitable for large datasets due to its quadratic time complexity.

## 3. Insertion Sort

**Description**:  
Insertion Sort builds the final sorted array one item at a time. It is much less efficient on large lists but performs well on smaller lists or when data is nearly sorted.

**Time Complexity**:

- Best: O(n) (when nearly sorted)
- Average: O(n²)
- Worst: O(n²)

**Space Complexity**: O(1)

**Use Case**:  
Ideal for small datasets or lists that are already partially sorted.

## 4. Quick Sort

**Description**:  
Quick Sort is a highly efficient, divide-and-conquer algorithm. It works by selecting a 'pivot' element from the array and partitioning the other elements into two sub-arrays according to whether they are less than or greater than the pivot. The sub-arrays are then sorted recursively.

**Time Complexity**:

- Best: O(n log n)
- Average: O(n log n)
- Worst: O(n²) (when the pivot is poorly chosen)

**Space Complexity**: O(log n)

**Use Case**:  
Works well with large datasets, but its performance depends on the pivot selection. With optimizations, it’s among the fastest sorting algorithms.

## 5. Merge Sort

**Description**:  
Merge Sort is another divide-and-conquer algorithm that splits the array into smaller subarrays, sorts each subarray, and then merges them back together in sorted order.

**Time Complexity**:

- Best: O(n log n)
- Average: O(n log n)
- Worst: O(n log n)

**Space Complexity**: O(n)

**Use Case**:  
Stable, consistent performance, and particularly good for large datasets or when stability is a concern.

## 6. Heap Sort

**Description**:  
Heap Sort is a comparison-based sorting algorithm that uses a binary heap data structure. It begins by building a max-heap (or min-heap), then repeatedly extracts the largest element and reconstructs the heap.

**Time Complexity**:

- Best: O(n log n)
- Average: O(n log n)
- Worst: O(n log n)

**Space Complexity**: O(1)

**Use Case**:  
Heap Sort is efficient for large datasets and is particularly useful when you need a stable O(n log n) performance.

## 7. Radix Sort

**Description**:  
Radix Sort is a non-comparative integer sorting algorithm. It sorts numbers by processing individual digits. The sorting starts from the least significant digit and moves towards the most significant digit using a stable sort like Counting Sort.

**Time Complexity**:

- Best: O(nk) (where `k` is the number of digits in the largest number)
- Average: O(nk)
- Worst: O(nk)

**Space Complexity**: O(n + k)

**Use Case**:  
Efficient for large datasets of numbers, especially when the range of digits is small compared to the number of items to sort.

---

## Conclusion

Each of these sorting algorithms has its own strengths and weaknesses. Choosing the right one depends on the size and nature of the data, as well as the constraints of the application. Some algorithms, like Quick Sort, are efficient for general-purpose use, while others, like Radix Sort, are tailored for specific types of data.
