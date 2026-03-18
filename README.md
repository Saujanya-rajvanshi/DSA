# DSA

solve problems not theory <br>
give contest solve

### INDEX
- [roadmap](#roadmap)
- [checklist](https://1drv.ms/x/c/467360d9dc29e9d6/IQCTuQ4ppoMwQpQ19YAvi3vTAQlD6POMfeIAZ_kF691xJOM?e=DVvxoN)
- [Programming Language](https://github.com/Saujanya-rajvanshi/C-)
- [OOPs basic](https://github.com/Saujanya-rajvanshi/THEORY)
- [dsa definition and types](#DSA-basic)
- [Algorithmic Complexity](#Algorithmic-Complexity)
- [striver pattern](https://github.com/Saujanya-rajvanshi/Striver)
- [stl](https://github.com/Saujanya-rajvanshi/STL)
- [basic maths codes](https://github.com/Saujanya-rajvanshi/basic-maths)
- [recusion repository](https://github.com/Saujanya-rajvanshi/recursion-and-hashing?tab=readme-ov-file#recursion)
- [hashing](https://github.com/Saujanya-rajvanshi/recursion-and-hashing?tab=readme-ov-file#hashing)
- [sorting repository](https://github.com/Saujanya-rajvanshi/Sorting-and-searching-)
- [searching repository](https://github.com/Saujanya-rajvanshi/Sorting-and-searching-/blob/main/README.md#searching-2)
- [Array Data Structures](https://github.com/Saujanya-rajvanshi/Arrays-)
- [binary search](https://github.com/Saujanya-rajvanshi/Sorting-and-searching-?tab=readme-ov-file#binary-searching)
- [binary tree]()
- [binary search tree]()
- [string]()
- [bit manipulation]()
- [sliding window & two pointer combined]()
- [greedy algorithm]()
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

### Step 1 — Foundation (Must Be Strong)
* Arrays
* Strings
* Recursion
* Hashing
* Sorting
* Binary Search
* Sliding Window
* Stack / Queue
* Linked List
<br>
Without this → DP will feel impossible.

### Step 2 — Core Structures
* Binary Tree
* BST
* Heap
* Graph
<br>
Now your thinking level increases.

### Step 3 — Then Greedy & DP
* Greedy
* Backtracking
* Dynamic Programming
<br>
DP is not a beginner topic.
It needs strong recursion + pattern recog
<br>

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




<img width="620" height="654" alt="image" src="https://github.com/user-attachments/assets/2e4b7360-e439-41ad-8b13-fc22384fc109" />


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















## DSA basic

## INDEX 
- [definition](#definition)
- [Types](#Types)

## definition

Data structures are specialized formats for organizing and storing data in a computer so that it can be used efficiently. They provide a means to manage large amounts of data efficiently for uses such as large databases and internet indexing services. They are critical to programming and are used in almost all software systems including web development, operating systems, image editing, and much more. Some common types of data structures are arrays, linked lists, queues, stacks, trees, and graphs. The choice of the data structure often begins from the choice of an abstract data type, a broad type encapsulating various possible data structures."


### Importance of Data Structures

* Organize and store data efficiently
* Foundation of algorithm design
* Improve program performance
* Enable fast data access, insertion, and deletion
* Help in sorting, searching, and ordering data
* Reduce code complexity
* Make programs scalable and flexible
* Essential for software and database development


## Types
- [primitive and non primitive](#primitive-and-non-primitive)
- [linear and non linear](#linear-and-non-linear)
- [static and dynamic](#static-and-dynamic)

```cpp
                      Data Structure Types
                              |
              ---------------------------------------------
              |                                            |
     Primitive Data Structure                 Non-Primitive Data Structure
              |                                            |
   --------------------------------          --------------------------------------------------------------------
   |        |        |        |              |                             |                                 |
 Integer   Float  Character   pointer      Linear DS                   Non-Linear DS                      hashing
                                              |                             |                                |
                                   -------------------          --------------------------            ----------------
                                   |    |      |     |          |     |     |     |      |            |       |      |    
                                 Array Linked Stack Queue    Tree  Heap   Trie Graph   Hash         hash     hash   hash  
                                       List                                                         set      map    table
```

###### primitive and non primitive
##  Primitive vs Non-Primitive Data Types

* **Primitive:** Basic built-in data types that store **single values directly** (e.g., int, char, float).
* **Non-Primitive:** Complex data types that store **multiple values or references** (e.g., arrays, vector, classes, objects).

| **Aspect**       | **Primitive Data Types**        | **Non-Primitive Data Types**             |
| ---------------- | ------------------------------- | ---------------------------------------- |
| **Definition**   | Store **single, simple values** | Store **multiple or complex data**       |
| **Data Storage** | Hold **actual value**           | Hold **reference/address of data**       |
| **Memory Size**  | Fixed size                      | Dynamic or variable size                 |
| **Complexity**   | Simple and lightweight          | Complex and structured                   |
| **Access Speed** | Faster                          | Slower compared to primitive             |
| **Operations**   | Limited operations              | Support advanced operations              |
| **Mutability**   | Immutable by default            | Mostly mutable                           |
| **Scalability**  | Less scalable                   | Highly scalable                          |
| **Usage**        | Basic data storage              | Data organization and management         |
| **Performance**  | High performance                | Depends on structure                     |
| **Flexibility**  | Less flexible                   | More flexible                            |
| **Examples**     | `int`, `float`, `char`, `bool`  | Array, String, Structure, Class, Pointer |

---




######  linear and non linear
## Linear vs Non-Linear Data Structures 

* **Linear:** Elements are arranged in a **sequential order**, one after another (e.g., array, linked list).
* **Non-Linear:** Elements are arranged in a **hierarchical** or interconnected way (e.g., tree, graph).

| **Aspect**                    | **Linear Data Structures**                                            | **Non-Linear Data Structures**                          |
| ----------------------------- | --------------------------------------------------------------------- | ------------------------------------------------------- |
| **Definition**                | Data elements are arranged sequentially, one after another            | Data elements are arranged hierarchically or graph-like |
| **Data Relationship**         | Each element has a **single predecessor and successor** (except ends) | An element can have **multiple relationships**          |
| **Traversal**                 | Traversed in a **single run** (one direction)                         | Traversed in **multiple ways** (DFS, BFS, etc.)         |
| **Storage Order**             | Stored in **contiguous or logical sequence**                          | Stored in **non-sequential manner**                     |
| **Memory Utilization**        | Simpler memory usage                                                  | More complex memory management                          |
| **Complexity of Structure**   | Easy to implement and understand                                      | More complex to implement                               |
| **Data Access**               | Sequential access                                                     | Non-sequential access                                   |
| **Search Efficiency**         | Slower for large data sets                                            | Faster for complex relationships                        |
| **Insertion / Deletion**      | Costly (especially arrays)                                            | Efficient with proper structure                         |
| **Scalability**               | Less scalable                                                         | Highly scalable                                         |
| **Data Representation**       | Simple list-like structure                                            | Tree or network-like structure                          |
| **Real-World Mapping**        | Suitable for simple data flow                                         | Suitable for real-world hierarchical data               |
| **Performance**               | Efficient for small datasets                                          | Efficient for large and complex datasets                |
| **Implementation Difficulty** | Low                                                                   | Medium to High                                          |
| **Use Cases**                 | Simple applications                                                   | Complex applications                                    |
| **Examples**                  | Array, Stack, Queue, Linked List                                      | Tree, Graph, Heap, Trie, Hash Table                     |


---

###### static and dynamic 
## Static vs Dynamic 

* **Static:** Memory size is **fixed at compile time** and cannot change (e.g., arrays).
* **Dynamic:** Memory size can **grow or shrink at runtime** (e.g., linked list, vector).


| **Aspect**          | **Static**                             | **Dynamic**                            |
| ------------------- | -------------------------------------- | -------------------------------------- |
| **Definition**      | Memory allocated at **compile time**   | Memory allocated at **runtime**        |
| **Memory Size**     | Fixed and known in advance             | Flexible, decided during execution     |
| **Allocation Time** | Compile time                           | Runtime                                |
| **Memory Location** | Stack / Static memory                  | Heap                                   |
| **Resizing**        | Not possible                           | Possible                               |
| **Lifetime**        | Exists till program ends or scope ends | Exists until manually deallocated      |
| **Flexibility**     | Less flexible                          | Highly flexible                        |
| **Speed**           | Faster access                          | Slightly slower                        |
| **Memory Wastage**  | Possible if size unused                | Minimal (allocated as needed)          |
| **User Control**    | Limited control                        | Full control                           |
| **Complexity**      | Simple to use                          | More complex to manage                 |
| **Error Risk**      | Low                                    | High (memory leaks, dangling pointers) |
| **Best Used When**  | Size is known and fixed                | Size is unknown or variable            |
| **Examples**        | Static array, global variables         | Dynamic array, linked list, vector     |


# Problem Solving Techniques

- [array](https://github.com/Saujanya-rajvanshi/Arrays-?tab=readme-ov-file#problem-solving-techniques)


# Platforms for Practice

- [array](https://github.com/Saujanya-rajvanshi/Arrays-?tab=readme-ov-file#platforms-for-practice)








