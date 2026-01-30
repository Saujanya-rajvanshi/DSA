# DSA

### INDEX
- [roadmap](#roadmap)
- [checklist](#checklist)
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
- [basic data structure](#basic-data-structure)
- [Tree Data Structures](#Tree-Data-Structures)
- [Graph Data Structure](#Graph-Data-Structure)
- [Advanced Data Structures](#Advanced-Data-Structures)
- [Complex Data Structures](#Complex-Data-Structures)
- [Indexing](#Indexing)
- [Problem Solving Techniques](#Problem-Solving-Techniques)
- [Platforms for Practice](#Platforms-for-Practice)


###### roadmap
# 🌟 ROADMAP
 🌿 - [roadmap](https://roadmap.sh/datastructures-and-algorithms?fl=0)


## basic data structure

* **array** - [array repository](https://github.com/Saujanya-rajvanshi/Arrays-)

* **list** - [list repository](https://github.com/Saujanya-rajvanshi/linked-list)

* **stack** - [stack repository](https://github.com/Saujanya-rajvanshi/stack)

* **queue** - [queue repository](https://github.com/Saujanya-rajvanshi/queue)

* **tree** - [tree repository](https://github.com/Saujanya-rajvanshi/trees)

* **graph** - [graph repository](https://github.com/Saujanya-rajvanshi/graph)


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
it cannot be set as time taken because every machine will take different time.

2️⃣ Space Complexity
Space Complexity = total memory used by an algorithm.
📌 Components
Fixed part → constants, variables
Variable part → input size, recursion stack, dynamic memory
