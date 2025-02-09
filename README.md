# Algorithms Course

> Prerequisites: Besides knowledge in pure C++ it is definitely mandatory to be familiar to topics presented in the Data Structures course, which you can find [here](https://github.com/Alohack/data-structures-course), especially with
- Asymptotic Analysis
- Vector
- Forward List
- List
- Stack
- Queue
- Recursion
- Binary search trees
- Heap
- Hash functions, hash tables
- Disjoint Sets
- Graphs

# Divide and conquer algorithms, Brute force algorithms 

1. **Sorting algorithms and their complexities** 
   - Merge Sort, Quick Sort, Heap Sort
   - Lower bound for comparison based sorting with the proof
   - Count sort, Radix sort
   - Complexity analysis
2. **Order Statistics** 
   - Definition of k-th order statistic, brute force methods
   - Using Heap for k-th order statistic computation, complexity analysis
   - Quickselect, complexity analysis, comparison with heap method
   - Median of medians algorithm, usage in QuickSelect and QuickSort, complexity analysis
3. **Other divide and conquer algorithms**
   - Binary search
   - Finding zeros of a given function
   - Closest pair of points on a plain, complexity analysis, brute force vs divide and conquer
   - Complexity analysis
4. **Brute force method**
   - Generating all possible subsets. Recursive and non-recursive methods
   - Using brute force to solve the [staircase problem](https://acmp.ru/index.asp?main=task&id_task=16)
   - Complexity analysis

# Greedy algorithms, Dynamic Programming

5. **Greedy algorithms vs Dynamic Programming, definitions and examples**
   - Definition of the Greedy algorithm approach, examples
   - Greedy approach behavior in [minimal path in table problem](https://acmp.ru/index.asp?main=task&id_task=120)
   - Definition of the Dynamic Programming approach, examples
   - Solving [minimal path in table problem](https://acmp.ru/index.asp?main=task&id_task=120) using Dynamic Programming
   - Complexity analysis
6. **Finding $C_n^k$**
   - Using simple formula, problem with storing the result in int
   - Using Dynamic programming
   - Memoization Optimization, complexity analysis
7. **Knapsack problems**
   - Solving fractional knapsack problem by greedy algorithm
   - Solving 0-1 knapsack problem by brute force
   - Solving 0-1 knapsack problem by Dynamic Programming in case of integer prices and weights
   - Complexity analysis
8. **String matching problems**
   - Finding Levenstein distance with DP
   - Solving Longest Common Subsequence problem with DP
   - Finding substring using sliding window principle with hash function and extended GCD
   - Finding substring using Z-function
   - Finding substring using Knuth-Morris-Pratt algorithm
   - Complexity analysis

# Graph algorithms

9. **Key concepts**
    - Definition of a graph
    - Ways to store a graph in memory. Adjacency matrix vs adjacency list
    - BFS / DFS, complexity analysis

10. **Topological sort**
    - Kahn's algorithm
    - Topological sort using DFS
    - Complexity analysis

11. **Shortest path problem**
    - Dijkstra's algorithm, correctness proof, counterexamples in case of negative vertices.
    - Bellman-Ford's algorithm
    - Floyd-Warshall's algorithm
    - Complexity analysis
  
12. **Minimum spanning tree problem**
    - Prim's algorithm
    - Kruskal's algorithm
    - Complexity analysis and usage of Heap and Disjoint Sets
  
13. **Strongly connected components**
    - Kosaraju's algorithm
    - Tarjan's algorithm
    - Complexity analysis