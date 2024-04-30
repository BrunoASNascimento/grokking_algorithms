# Grokking Algorithms
This repository contains Python and Rust implementations of various algorithms discussed in the book "Grokking Algorithms." Each chapter's code focuses on different fundamental algorithms, showcasing their implementation and effectiveness.

## Chapter 1: Introduction to Binary Search
### Binary Search
Binary search offers a significantly faster approach to searching sorted lists compared to linear search. This method improves efficiency by repeatedly dividing the search interval in half.

#### How Binary Search Works:
1. **Start by examining the middle item of the list.**
2. **If the middle item is equal to the target, the search is complete.**
3. **If the target is less than the middle item, focus on the left half of the list; otherwise, focus on the right half.**
4. **Repeat the process on the new half-list until the item is found or the sublist is empty.**

#### Implementation:
You can find the implementation of binary search in the file: [Python Binary Search Code](directory_python/binary_search.py) and [Rust Binary Search Code](directory_rust/binary_search/main.rs).

#### Performance Comparison
In addition to implementing binary search, this chapter includes a performance comparison between binary search and linear search:

- **Observations**: Binary search was found to be approximately 10 times faster than linear search in tests using Python.
- **Logging**: The code logs processing times for both searches, illustrating the efficiency gains with binary search.
