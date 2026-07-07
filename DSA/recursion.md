## 📝 Recursion Notes

This document contains concise notes and important concepts related to **Recursion** in C++. It serves as a quick revision guide covering recursion fundamentals, recursive thinking, backtracking, recursion trees, divide-and-conquer algorithms, and complexity analysis.

---

## 📌 What is Recursion?

Recursion is a programming technique where a function calls **itself** to solve a problem by breaking it into smaller subproblems.

A recursive solution continues until a **base case** is reached.

```cpp
void solve(){
    solve();
}
```

Without a base case, recursion leads to **infinite recursive calls** and eventually causes a **Stack Overflow**.

---

## 📌 Components of Recursion

Every recursive function contains two essential parts:

**Base Case**

Stops the recursion.

```cpp
if(n == 0)
    return;
```

##

**Recursive Call**

Function calls itself with a smaller problem.

```cpp
solve(n - 1);
```

##

**📌 Recursive Flow**

```
Function Call
      ↓
Check Base Case
      ↓
Recursive Call
      ↓
Base Case Reached
      ↓
Function Returns
```

##

**📌 Recursion Stack**

Each recursive call is stored in the **Call Stack**.

```
main()

↓

fun(5)

↓

fun(4)

↓

fun(3)

↓

fun(2)

↓

fun(1)

↓

fun(0)

↑

Returns back one by one
```

Recursion uses **stack memory**, unlike vectors which use heap memory.

##

**📌 Forward Recursion**

Work is performed **before** the recursive call.

Example:

```
5 4 3 2 1
```

```cpp
cout << n;
solve(n-1);
```

##

**📌 Backtracking**

Work is performed **after** the recursive call.

Example:

```
1 2 3 4 5
```

```cpp
solve(n-1);
cout << n;
```

Backtracking occurs naturally while returning from recursive calls.

---

## 📌 Common Recursive Problems

- Print N to 1
- Print 1 to N (Backtracking)
- Sum of N Natural Numbers
- Factorial
- Power (xⁿ)
- Fibonacci Series
- Reverse String
- Binary Search
- Merge Sort

---

## 📌 Divide and Conquer

Many recursive algorithms follow the **Divide and Conquer** strategy.

Steps:

1. Divide the problem
2. Solve each subproblem recursively
3. Combine the results

Examples:

- Merge Sort
- Quick Sort
- Binary Search

---

## 📌 Recursion Tree

A recursion tree visually represents recursive function calls.

Example:

```
factorial(4)

↓

4 × factorial(3)

↓

3 × factorial(2)

↓

2 × factorial(1)

↓

1
```

---

## 📌 Merge Sort

Merge Sort repeatedly divides the array into two halves until only one element remains.

Then, the sorted halves are merged together.

**Steps**

```
Divide

↓

Left Half

↓

Right Half

↓

Merge
```

Time Complexity:

```
O(n log n)
```

Stable Sorting Algorithm:

✅ Yes

---

## 📌 Binary Search using Recursion

Binary Search repeatedly divides the search space into halves.

Conditions:

- Array must be sorted
- Middle element compared with target

Time Complexity:

```
O(log n)
```

---

## 📌 Base Case Importance

A missing base case causes:

- Infinite recursion
- Stack Overflow
- Program crash

Always ensure the problem size decreases with every recursive call.

---

## 📌 Advantages of Recursion

- Cleaner code
- Easier implementation
- Natural solution for trees and graphs
- Simplifies Divide & Conquer algorithms

##

## 📌 Disadvantages of Recursion

- Extra stack memory
- Function call overhead
- Slower than iteration in some cases
- Risk of Stack Overflow

---

## 📌 Recursion vs Iteration

| Recursion | Iteration |
|-----------|-----------|
| Uses function calls | Uses loops |
| Uses call stack | Uses variables |
| Easier to write | Usually faster |
| More memory usage | Less memory usage |

---

## 📌 Time Complexity

| Problem | Complexity |
|---------|-----------:|
| Print N Numbers | O(n) |
| Sum of N Numbers | O(n) |
| Factorial | O(n) |
| Reverse String | O(n) |
| Binary Search | O(log n) |
| Merge Sort | O(n log n) |
| Fibonacci (Basic Recursive) | O(2ⁿ) |

---

## 📌 Space Complexity

| Algorithm | Space |
|-----------|-------:|
| Factorial | O(n) |
| Sum of N Numbers | O(n) |
| Binary Search | O(log n) |
| Merge Sort | O(n) |

---

## 📌 STL Functions Used

| Function | Purpose |
|----------|---------|
| `swap()` | Exchange two values |
| `getline()` | Read complete string |
| `vector` | Dynamic array used in Merge Sort |

---

## 💡 Key Takeaways

- Every recursive function must contain a base case.
- Recursion solves problems by reducing them into smaller subproblems.
- Backtracking occurs while recursive calls return.
- Binary Search and Merge Sort are classic Divide-and-Conquer algorithms.
- Recursion simplifies many complex algorithms but consumes additional stack memory.
- Choosing recursion or iteration depends on the problem and memory constraints.

---

## Status

🟢 Active | Continuously Updated

---

## Contact

**Ananya Siju**  
[LinkedIn](https://www.linkedin.com/in/ananya-siju-a04835291/) | [GitHub](https://github.com/AnanyaIntech-source) | ananyasiju16@gmail.com

---

> **Author:** [Ananya Siju](https://github.com/AnanyaIntech-source)
> 
