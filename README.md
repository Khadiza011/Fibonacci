# Fibonacci Sequence using Dynamic Programming (C++)

## Overview

This project generates the **nth Fibonacci number** using **Dynamic Programming (Tabulation)**. Instead of repeatedly calculating the same values, the program stores previously computed Fibonacci numbers in an array, making it efficient.

## Algorithm

1. Read the value of `n`.
2. Create a DP array of size `n + 1`.
3. Initialize:
   - `dp[0] = 0`
   - `dp[1] = 1`
4. Compute each Fibonacci number using the recurrence:
   - `dp[i] = dp[i-1] + dp[i-2]`
5. Display the nth Fibonacci number.

## Time Complexity

- **Time Complexity:** O(n)
- **Space Complexity:** O(n)

Where:
- **n** = Position of the Fibonacci number.

## Input

- An integer `n`

### Example Input

```
Enter the value of n:
10
```

## Example Output

```
FIB: 55
```

## How to Compile

```bash
g++ main.cpp -o main
```

## How to Run

### Linux/macOS

```bash
./main
```

### Windows

```bash
main.exe
```

## Features

- User input for `n`
- Dynamic Programming (Tabulation) approach
- Efficient O(n) solution
- Avoids redundant recursive calculations
- Simple C++ implementation
