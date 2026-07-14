# Length of the Longest Subarray with Zero Sum

## Problem Statement

Given an array containing both positive and negative integers, find the length of the longest subarray whose sum is equal to `0`. If no such subarray exists, return `0`.

---

## Brute Force Approach

* Consider every possible starting index of the subarray.
* For each starting index, initialize the sum to `0`.
* Extend the subarray one element at a time by moving the ending index.
* Continuously add the current element to the running sum.
* Whenever the running sum becomes `0`, calculate the length of the current subarray and update the maximum length if it is larger.
* Continue this process until all possible subarrays have been checked.

---

## Algorithm

1. Read the input array.
2. Initialize `maxLen` to `0`.
3. Traverse the array by choosing each index as the starting point.
4. Reset the running sum to `0` for every new starting index.
5. Extend the subarray one element at a time and update the running sum.
6. If the running sum becomes `0`, update the maximum length.
7. Print the maximum length after checking all subarrays.

---

## Complexity Analysis

* **Time Complexity:** `O(N²)`
* **Space Complexity:** `O(1)`

---

## Key Concepts

* Brute Force
* Nested Loops
* Running Sum
* Longest Subarray
* Array Traversal
