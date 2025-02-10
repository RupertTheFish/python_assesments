# Studying Python for Technical Job Interviews

This repository contains a range of Python exercises commonly seen in technical assessments. They vary in difficulty, covering basic to advanced concepts. Practicing these types of problems will help in preparing for upcoming assessments.

## Assessments

### 1. String Manipulation
**Problem:** Write a function that takes a string and returns the longest palindrome within it.  
**Example:**  
```python
longest_palindrome("babad")  # Output: "bab" or "aba"
```

### 2. Array/Lists
**Problem:** Write a function that finds the two numbers in a list that add up to a specific target.  
**Example:**  
```python
two_sum([2, 7, 11, 15], 9)  # Output: [0, 1]
```

### 3. Binary Search
**Problem:** Implement binary search on a sorted list and return the index of a target element.  
**Example:**  
```python
binary_search([1, 3, 5, 7, 9], 5)  # Output: 2
```

### 4. Recursion
**Problem:** Write a function to compute the nth Fibonacci number using recursion.  
**Example:**  
```python
fibonacci(6)  # Output: 8
```

### 5. Sorting Algorithms
**Problem:** Implement the quicksort algorithm.  
**Example:**  
```python
quicksort([3, 6, 8, 10, 1, 2, 1])  # Output: [1, 1, 2, 3, 6, 8, 10]
```

### 6. Data Structures: Stacks and Queues
**Problem:** Implement a stack with push, pop, and min operations, all in O(1) time.  
**Example:**  
```python
stack.push(5)
stack.min()  # Output: 5
stack.push(3)
stack.min()  # Output: 3
```

### 7. Dynamic Programming
**Problem:** Solve the "coin change" problem: given a list of coin denominations and an amount, find the minimum number of coins needed to make that amount.  
**Example:**  
```python
coin_change([1, 2, 5], 11)  # Output: 3 (5 + 5 + 1)
```

### 8. Graph Traversal
**Problem:** Implement depth-first search (DFS) and breadth-first search (BFS) for a graph.  
**Example:**  
```python
dfs(graph, start)  # Output: Nodes visited in DFS order
bfs(graph, start)  # Output: Nodes visited in BFS order
```

### 9. Database-like Queries
**Problem:** Given a list of dictionaries representing records, filter and sort them by specific fields.  
**Example:**  
```python
filter_and_sort(records, 'age', 30)  # Output: Filtered and sorted records
```

### 10. File Handling
**Problem:** Write a script to read a log file, extract error messages, and write them to a new file.  
**Example:**  
```python
extract_errors('log.txt', 'errors.txt')
```

---


Feel free to contribute by adding more problems, optimizing solutions, or improving documentation!

## License
This project is licensed under the MIT License.

