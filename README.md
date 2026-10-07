# Sorting Algorithms in Python

This repository contains Python implementations of five fundamental sorting algorithms. Each program takes user input, sorts the array, displays the sorted output, prints the time complexity, and measures the execution time for better understanding.

## 📂 Files Included

- `bubblesort.py` – Bubble Sort
- `insertionsort.py` – Insertion Sort
- `selectionsort.py` – Selection Sort
- `mergesort.py` – Merge Sort
- `quicksort.py` – Quick Sort

## 🚀 Features

- User input for array elements
- Displays sorted array
- Measures execution time using `time.perf_counter()`
- Prints Best, Average, and Worst Case Time Complexity
- Easy-to-understand implementation for beginners

## 🧠 Practical Summary: 2 to 8

### Practical 2 – Search Algorithms
- Covers linear search and binary search.
- Demonstrates how linear search checks each element one by one.
- Shows binary search on sorted data using divide-and-conquer logic.
- Compares execution time and explains why binary search is faster than linear search for large datasets.

### Practical 3 – Heap Sort
- Implements heap sort using a max-heap structure.
- Explains heapify and extraction of maximum elements.
- Shows how repeated swapping and heap adjustment produce a sorted array.
- Highlights heap sort as an efficient sorting algorithm with O(n log n) time complexity.

### Practical 4 – Recursion vs Iteration
- Compares recursive and iterative methods using the factorial problem.
- Shows that recursion breaks the problem into smaller subproblems until a base case is reached.
- Demonstrates that iteration uses loops to achieve the same result with less function call overhead.
- Helps understand when recursion is useful and when iteration is more efficient.

### Practical 5 – 0/1 Knapsack Problem
- Solves the classic knapsack problem using dynamic programming.
- Uses a table to track the best value for each weight and item combination.
- Implements both recursive memoization and iterative DP approaches.
- Demonstrates maximizing total value without exceeding the knapsack capacity.

### Practical 6 – Matrix Chain Multiplication
- Explains how matrix multiplication order affects the number of scalar multiplications.
- Uses dynamic programming to minimize multiplication cost.
- Shows recursive memoization and iterative tabulation strategies.
- Illustrates the importance of optimal parenthesization in matrix computations.

### Practical 7 – Coin Change Problem
- Finds the minimum number of coins needed to make a given amount.
- Uses recursion with memoization and dynamic programming.
- Explains how subproblems are reused to reduce repeated calculations.
- Demonstrates optimization for problems involving making change with limited denominations.

### Practical 8 – Graph Traversal: BFS and DFS
- Implements Breadth-First Search (BFS) and Depth-First Search (DFS).
- Uses an adjacency list to represent a graph.
- BFS explores neighbors level by level, while DFS explores as deeply as possible before backtracking.
- Helps understand graph traversal techniques used in networking, pathfinding, and connectivity analysis.

## 🛠 Requirements

- Python 3.x

No external libraries are required.

## ▶️ How to Run

Clone the repository:

```bash
git clone https://github.com/your-username/sorting-algorithms-python.git
```

Navigate to the project folder:

```bash
cd sorting-algorithms-python
```

Run any sorting algorithm:

```bash
python bubblesort.py
```

or

```bash
python insertionsort.py
```

or

```bash
python selectionsort.py
```

or

```bash
python mergesort.py
```

or

```bash
python quicksort.py
```

## 📥 Sample Input

```
Enter number of elements:
5

Enter elements:
5 3 1 4 2
```

## 📤 Sample Output

```
Sorted Array:
1 2 3 4 5

Time Complexity:
Best Case : O(n)
Average Case : O(n²)
Worst Case : O(n²)

Execution Time: 25.67 microseconds
```

## 📊 Time Complexity Comparison

| Algorithm | Best Case | Average Case | Worst Case |
|-----------|-----------|--------------|------------|
| Bubble Sort | O(n) | O(n²) | O(n²) |
| Insertion Sort | O(n) | O(n²) | O(n²) |
| Selection Sort | O(n²) | O(n²) | O(n²) |
| Merge Sort | O(n log n) | O(n log n) | O(n log n) |
| Quick Sort | O(n log n) | O(n log n) | O(n²) |

## 📚 Learning Objectives

This project helps in understanding:

- Bubble Sort
- Insertion Sort
- Selection Sort
- Merge Sort
- Quick Sort
- Time Complexity Analysis
- Execution Time Measurement in Python
- Search algorithms
- Dynamic programming
- Recursion and iteration
- Graph traversal methods

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository and submit a pull request.

## 📄 License

This project is open-source and available under the MIT License.

---

⭐ If you found this project useful, consider giving it a star on GitHub!
