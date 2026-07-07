## 📝 C++ Fundamentals Notes

This document contains quick reference notes and important concepts learned while studying C++ fundamentals for Data Structures & Algorithms.

---

## 📌 Constant Pointer

A constant pointer cannot point to another memory location after initialization.

```cpp
const int num = 3;
const int *const ptr = &num;
```

- `const int` → value cannot be modified.
- `const ptr` → pointer cannot be reassigned.
- Both the pointer and the value remain constant.

---

## 📌 Arrays

Arrays are collections of elements of the same data type stored in contiguous memory locations.

### Characteristics

- Static memory allocation
- Fixed size (decided during compile time)
- Stored in stack memory
- Fast random access using index

```cpp
int arr[5];
```

---

**Common STL Operations**

```cpp
sort(arr, arr + size);      // Ascending Order
reverse(arr, arr + size);   // Reverse Array
```

---

**Time Complexities**

| Operation | Complexity |
|-----------|------------|
| Access | O(1) |
| Traversal | O(n) |
| Insertion (End)* | O(1) |
| Searching (Linear) | O(n) |
| Binary Search (Sorted Array) | O(log n) |
| Reverse | O(n) |

*Insertion is only possible within the array's fixed capacity.

---

## 📌 Vectors

Vectors are dynamic arrays provided by the C++ STL.

Unlike arrays, vectors automatically resize themselves when new elements are added.

```cpp
vector<int> vec;
```

---

**Characteristics**

- Dynamic memory allocation
- Size changes during runtime
- Stored in heap memory
- Supports automatic resizing
- Part of the Standard Template Library (STL)

---

**Common Functions**

| Function | Description |
|----------|-------------|
| `push_back(x)` | Add element at the end |
| `pop_back()` | Remove last element |
| `insert()` | Insert element(s) |
| `size()` | Number of elements |
| `capacity()` | Allocated storage capacity |
| `front()` | First element |
| `back()` | Last element |
| `clear()` | Remove all elements |
| `empty()` | Check if vector is empty |
| `at(i)` | Access element with bounds checking |

---

**Size vs Capacity**

- **Size** → Number of elements currently stored.
- **Capacity** → Total elements the vector can hold before reallocating memory.

Example growth:

```
Capacity

1 → 2 → 4 → 8 → 16 → 32 ...
```

Vectors usually double their capacity whenever additional memory is required.

---

**Common STL Operations**

```cpp
sort(vec.begin(), vec.end());      // Ascending
sort(vec.rbegin(), vec.rend());    // Descending
reverse(vec.begin(), vec.end());   // Reverse
```

---

## 📌 Searching Algorithms

**Linear Search**

Checks every element one by one.

```
Time Complexity : O(n)
Space Complexity : O(1)
```

Best for:
- Small datasets
- Unsorted arrays

---

**Binary Search**

Repeatedly divides the search space into half.

```
Time Complexity : O(log n)
Space Complexity : O(1)
```

Requirement:
- Array **must be sorted**.

---

## 📌 Arrays vs Vectors

| Feature | Array | Vector |
|---------|-------|--------|
| Size | Fixed | Dynamic |
| Memory | Stack | Heap |
| STL Support | Limited | Extensive |
| Resize | ❌ No | ✅ Yes |
| Random Access | O(1) | O(1) |

---

## 📌 Useful Header Files

```cpp
#include <iostream>
#include <vector>
#include <algorithm>
#include <string>
#include <climits>
```

---

## 💡 Key Takeaways

- Arrays have fixed size and are efficient for static data.
- Vectors provide flexibility through dynamic resizing.
- Binary Search requires sorted data.
- STL functions significantly simplify coding.
- Understanding memory allocation is essential for efficient DSA implementations.

---

### Status

🟢 Active | Continuously Updated

---
## Contact

**Ananya Siju**  
[LinkedIn](https://www.linkedin.com/in/ananya-siju-a04835291/) | [GitHub](https://github.com/AnanyaIntech-source) | ananyasiju16@gmail.com

---

> **Author:** [Ananya Siju](https://github.com/AnanyaIntech-source)
> 

