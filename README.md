# Sorting Algorithms in C++

Name: Pal Jain  
Class: ENTC A3  
PRN: 24070123067

**Aim:**
To understand and implement different sorting techniques in C++ for arranging array elements in ascending order.


---

## Theory

**Sorting** is the process of arranging data in a specific order, usually **ascending** or **descending**. Sorting not only organizes data but also enhances the efficiency of searching and data processing. Common sorting algorithms include **Selection Sort**, **Bubble Sort**, and **Quick Sort**.

* **Selection Sort:**
  Repeatedly selects the minimum (or maximum) element from the unsorted portion of the array and swaps it with the first unsorted element.

  * Time Complexity: O(n²)
  * Simple but inefficient for large datasets.

* **Bubble Sort:**
  Compares adjacent elements and swaps them if they are in the wrong order, causing the largest element to “bubble” to the end in each pass.

  * Time Complexity: O(n²)
  * Easy to implement but slow for large arrays.

* **Quick Sort:**
  A divide-and-conquer algorithm that selects a pivot, partitions the array around it, and recursively sorts the partitions.

  * Average Time Complexity: O(n log n)
  * Efficient and suitable for large datasets, though recursion uses extra stack space.

**Key Points:**

* Selection and Bubble Sort are simple but not suitable for large arrays.
* Quick Sort is faster and widely used in practice.
* Sorting improves the efficiency of algorithms such as **binary search**.

---

## Program 1: Selection Sort

**Logic:**
Continuously find the minimum element from the unsorted portion and swap it with the first element of that portion until the array is sorted.

**Algorithm:**

1. Start
2. Input array size and elements
3. For each index, find the minimum element in the unsorted part
4. Swap minimum element with the first element of the unsorted portion
5. Repeat until all elements are sorted
6. Display the sorted array
7. End

---

## Program 2: Bubble Sort

**Logic:**
Repeatedly compare adjacent elements and swap them if they are in the wrong order. Each pass moves the largest unsorted element to its correct position.

**Algorithm:**

1. Start
2. Input array size and elements
3. Repeat for each element:

   * Compare adjacent elements
   * Swap if needed
4. Continue passes until array is fully sorted
5. Display the sorted array
6. End

---

## Program 3: Quick Sort

**Logic:**
Select a pivot element, partition the array into two halves (elements smaller than pivot on left, larger on right), and recursively apply the same process to each partition.

**Algorithm:**

1. Start
2. Input array size and elements
3. Choose a pivot element
4. Partition the array around the pivot
5. Recursively sort left and right partitions
6. Display the sorted array
7. End

---

## Conclusion

Sorting is essential for organizing and processing data efficiently.

* **Selection Sort** and **Bubble Sort** are easy to implement but slow for large arrays.
* **Quick Sort** is highly efficient for large datasets due to its divide-and-conquer approach.
  A good understanding of these techniques helps in **algorithm design**, **data organization**, and preparing arrays for faster searching methods.
