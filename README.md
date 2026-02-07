# DSA

solve problems not theory 
give contest solve 

### INDEX
- [roadmap](#roadmap)
- [checklist](https://1drv.ms/x/c/467360d9dc29e9d6/IQCTuQ4ppoMwQpQ19YAvi3vTAQlD6POMfeIAZ_kF691xJOM?e=DVvxoN)
- [Programming Language](https://github.com/Saujanya-rajvanshi/C-)
- [OOPs basic](https://github.com/Saujanya-rajvanshi/THEORY)
- [dsa definition and types](https://github.com/Saujanya-rajvanshi/DSA-basic)
- [striver pattern](https://github.com/Saujanya-rajvanshi/Striver)
- [stl](https://github.com/Saujanya-rajvanshi/STL)
- [basic maths codes](https://github.com/Saujanya-rajvanshi/basic-maths)
- [Algorithmic Complexity](#Algorithmic-Complexity)
- [recusion repository](https://github.com/Saujanya-rajvanshi/recursion)
- [hashing](https://github.com/Saujanya-rajvanshi/recursion/blob/main/README.md#hashing)
- [sorting repository](https://github.com/Saujanya-rajvanshi/Sorting-and-searching-)
- [searching repository](https://github.com/Saujanya-rajvanshi/Sorting-and-searching-/blob/main/README.md#searching-2)
- [binary search]()
- [binary tree]()
- [binary search tree]()
- [string]()
- [bit manipulation]()
- [sliding window & two pointer combined]()
- [greedy algorithm]()
- [Array Data Structures](https://github.com/Saujanya-rajvanshi/Arrays-)
- [List Data Structures](https://github.com/Saujanya-rajvanshi/linked-list)
- [Stack Data Structures](https://github.com/Saujanya-rajvanshi/stack)
- [Queue Data Structures](https://github.com/Saujanya-rajvanshi/queue)
- [Tree Data Structures](https://github.com/Saujanya-rajvanshi/trees)
- [Graph Data Structure](https://github.com/Saujanya-rajvanshi/graph)
- [heap Data Structures](#Advanced-Data-Structures)
- [trie Data Structures](#Complex-Data-Structures)
- [dynamic programming]()
- [Indexing](#Indexing)
- [Problem Solving Techniques](#Problem-Solving-Techniques)
- [Platforms for Practice](#Platforms-for-Practice)


###### roadmap
# 🌟 ROADMAP
 🌿 - [roadmap](https://roadmap.sh/datastructures-and-algorithms?fl=0)




---

# Algorithmic Complexity

Algorithm complexity measures how efficient an algorithm is in terms of

### type of algorithm complexity 

* 1. **Time Complexity**
Measures **execution time** with respect to input size. <br>
Examples: O(1), O(n), O(n log n) <br>

* 2. **Space Complexity**
Measures **memory usage** with respect to input size. <br>
Includes stack, heap, variables, recursion. <br>

* 3. **Auxiliary Space Complexity**
Extra space used **excluding input space** <br>
Important for in-place algorithms. <br>

* 4. **Worst-Case Complexity**
Maximum time/space taken. <br>
Most commonly analyzed. <br>

* 5. **Average-Case Complexity**
Expected performance for random inputs. <br>

* 6. **Best-Case Complexity**
Minimum time/space required. <br>

* 7. **Amortized Complexity**
Average cost per operation over a sequence. <br>
Example: Dynamic array resizing. <br>

* 8. **Input Size Complexity**
Performance based on **size of input (n)** <br>
Example: number of elements, vertices, characters. <br>

* 9. **Output Complexity**
Depends on size of output. <br>
Example: Printing all subsets → O(2ⁿ) <br>

* 10. **Parameterized Complexity**
Complexity expressed using multiple parameters. <br>
Example: O(f(k) · n) <br>

* 11. **Probabilistic / Randomized Complexity**
Depends on probability and randomness. <br>
Used in randomized algorithms. <br>

* 12. **Communication Complexity**
Measures data exchanged between processes. <br>
Used in distributed systems. <br>

* 13. **I/O Complexity**
Measures disk read/write operations. <br>
Important for external memory algorithms. <br>

* 14. **Circuit Complexity**
Measures size and depth of logic circuits. <br>
Used in theoretical CS. <br>

* 15. **Energy Complexity**
Measures power consumption. <br>
Used in embedded and mobile systems. <br>

* 16. **Cache Complexity**
Measures cache misses and memory hierarchy use. <br>

* 17. **Parallel Complexity**
Measures time using multiple processors. <br>
Includes work and span. <br>

## Asymptotic Notations

Asymptotic notations describe how **time/space grows as input size (n) → ∞**.

### 1. **Big-O Notation — `O(f(n))`**
**Upper bound** (worst-case)
> Algorithm will **not take more than** this time.

### 2. **Big-Ω (Omega) — `Ω(f(n))`**
**Lower bound** (best-case)
> Algorithm will take **at least** this much time.

### 3. **Big-Θ (Theta) — `Θ(f(n))`**
**Tight bound** (exact growth)
> Both upper and lower bound.

### 4️. **Little-o Notation — `o(f(n))`**
**Strict upper bound**
> Grows **slower than** `f(n)`.

### 5️. **Little-ω (Omega) — `ω(f(n))`**
**Strict lower bound**
> Grows **faster than** `f(n)`.

## Time Complexity

Time Complexity = how the execution time grows with input size n.<br>
it is not equal to the actual time taken by the program to be executed <br>
it cannot be set as time taken because every machine will take different time. <br>
<br>
* TC considers worst case scenerrio
* Avoid constants : In time complexity we don’t measure the exact running time in seconds. <br>
We measure how the time grows when input size n becomes very large. <br>
A constant like +3, +1000, or even +1,000,000 does not grow with n. <br>
* Avoid lower values.

1s -> 10^8 operations <br>
2s -> 2 * 10^8 operations <br>
5s -> 5 * 10^8 operations <br>
ns -> n * 10^8 operations <br>

## Space Complexity

Space complexity = total memory used by an algorithm.

1. **Input space** → memory to store input data.
2. **Auxiliary space** → extra memory used by the algorithm (variables, arrays, recursion stack).
In Big-O we usually talk about **auxiliary space**.

Examples:

* Only few variables → `O(1)` (constant space)

  ```cpp
  int a, b, sum;
  ```
* Extra array of size `n` → `O(n)`

  ```cpp
  vector<int> temp(n);
  ```
* 2D array `n × n` → `O(n²)`

Recursion:

* Each recursive call uses stack memory.
  If depth = `n` → space `O(n)`.

Rules:

* Ignore constant space: 5 variables → still `O(1)`
* Count only space that grows with `n`.

Goal in optimization:
Use less extra memory while keeping good time complexity.

