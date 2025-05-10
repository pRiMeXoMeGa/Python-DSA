# Array Problems Collection

## Table of Contents
1. [Find the Maximum and Minimum Element in an Array](#1-find-the-maximum-and-minimum-element-in-an-array)
2. [Rearrange an Array - Negative Numbers Before Positive Numbers](#2-rearrange-an-array-so-that-all-negative-numbers-appear-before-all-positive-numbers)
3. [Find the Union and Intersection of Two Sorted Arrays](#3-find-the-union-and-intersection-of-two-sorted-arrays)
4. [Cyclically Rotate an Array by One](#4-write-a-program-to-cyclically-rotate-an-array-by-one)
5. [Find First and Last Positions of an Element in a Sorted Array](#5-find-first-and-last-positions-of-an-element-in-a-sorted-array)
6. [Searching in an Array where Adjacent Differ by at Most k](#6-searching-in-an-array-where-adjacent-differ-by-at-most-k)
7. [Search in a Rotated Sorted Array](#7-search-in-a-rotated-sorted-array)
8. [Find Duplicate in an Array of N+1 Integers](#8-find-duplicate-in-an-array-of-n1-integers)
9. [Sort an Array of 0s, 1s, and 2s](#9-given-an-array-which-consists-of-only-0-1-and-2-sort-the-array-without-using-any-sorting-algo)
10. [Minimum Number of Jumps to Reach End of an Array](#10-minimum-no-of-jumps-to-reach-end-of-an-array)
11. [Missing Number](#11-missing-number)
12. [Find Minimum in Rotated Sorted Array](#12-find-minimum-in-rotated-sorted-array)
13. [Range Sum Query](#13-range-sum-query)
14. [In-place Prefix Sum](#14-in-place-prefix-sum)
15. [Equilibrium Index of an Array](#15-equilibrium-index-of-an-array)
16. [Even Numbers in a Range](#16-even-numbers-in-a-range)
17. [Product Array Puzzle](#17-product-array-puzzle)

---


<details>
<summary><h2>1. Find the Maximum and Minimum Element in an Array</h2></summary>

**Problem Link:** [GeeksforGeeks - Maximum and Minimum in an Array](https://www.geeksforgeeks.org/maximum-and-minimum-in-an-array/)

</details>

<details>
<summary><h2>2. Rearrange an Array - Negative Numbers Before Positive Numbers</h2></summary>

### Problem Description

Given an array containing both positive and negative numbers in random order.
The task is to rearrange the array elements so that all negative numbers appear before all positive numbers.

**Note:** 
- The given array does not contain any zeroes. 
- The order of the resultant array does not matter.

### Example

**Input:**
```
-12, 11, -13, -5, 6, -7, 5, -3, -6
```

**Output:**
```
-12 -13 -5 -7 -3 -6 11 6 5
```

### Code Template

```python
# Python program to Move all negative numbers
# to the beginning and positive to the end

def move(arr):
    # WRITE YOUR CODE HERE
    pass

if __name__ == "__main__":
    arr = [-12, 11, -13, -5, 6, -7, 5, -3, -6]
    ans = move(arr)

    for num in ans:
        print(num, end=" ")
    print()
```

</details>

<details>
<summary><h2>3. Find the Union and Intersection of Two Sorted Arrays</h2></summary>

**Problem Link:** [GeeksforGeeks - Union of Two Arrays](https://www.geeksforgeeks.org/problems/union-of-two-arrays3538/1)

</details>

<details>
<summary><h2>4. Cyclically Rotate an Array by One</h2></summary>

**Problem Link:** [GeeksforGeeks - Cyclically Rotate an Array](https://www.geeksforgeeks.org/problems/cyclically-rotate-an-array-by-one2614/1)

</details>

<details>
<summary><h2>5. Find First and Last Positions of an Element in a Sorted Array</h2></summary>

**Problem Link:** [GeeksforGeeks - First and Last Occurrences of X](https://practice.geeksforgeeks.org/problems/first-and-last-occurrences-of-x/0)

</details>

<details>
<summary><h2>6. Searching in an Array where Adjacent Differ by at Most k</h2></summary>

**Problem Link:** [GeeksforGeeks - Searching in an Array with Adjacent Difference](https://www.geeksforgeeks.org/problems/searching-in-an-array-where-adjacent-differ-by-at-most-k0456/1?itm_source=geeksforgeeks&itm_medium=article&itm_campaign=practice_card)

</details>

<details>
<summary><h2>7. Search in a Rotated Sorted Array</h2></summary>

**Problem Link:** [LeetCode - Search in Rotated Sorted Array](https://leetcode.com/problems/search-in-rotated-sorted-array/description/)

</details>

<details>
<summary><h2>8. Find Duplicate in an Array of N+1 Integers</h2></summary>

**Problem Link:** [LeetCode - Find the Duplicate Number](https://leetcode.com/problems/find-the-duplicate-number/submissions/1591184118/)

</details>

<details>
<summary><h2>9. Sort an Array of 0s, 1s, and 2s</h2></summary>

**Problem Link:** [GeeksforGeeks - Sort an Array of 0s, 1s, and 2s](https://practice.geeksforgeeks.org/problems/sort-an-array-of-0s-1s-and-2s/0)

</details>

<details>
<summary><h2>10. Minimum Number of Jumps to Reach End of an Array</h2></summary>

**Problem Link:** [GeeksforGeeks - Minimum Number of Jumps](https://www.geeksforgeeks.org/problems/minimum-number-of-jumps-1587115620/1)

**Solution Article:** [O(n) Solution](https://www.geeksforgeeks.org/minimum-number-jumps-reach-endset-2on-solution/)

</details>

<details>
<summary><h2>11. Missing Number</h2></summary>

**Problem Link:** [LeetCode - Missing Number](https://leetcode.com/problems/missing-number/description/)

</details>

<details>
<summary><h2>12. Find Minimum in Rotated Sorted Array</h2></summary>

**Problem Link:** [LeetCode - Find Minimum in Rotated Sorted Array](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/description/)

</details>

<details>
<summary><h2>13. Range Sum Query</h2></summary>

### Problem Description

You are given an integer array `A` of length `N`.

You are also given a 2D integer array `B` with dimensions `M x 2`, where each row denotes a `[L, R]` query.

For each query, you have to find the sum of all elements from index `L` to `R` in `A` (0-indexed).

More formally, find `A[L] + A[L + 1] + ... + A[R]` for each query.

### Problem Constraints

- `1 <= N, M <= 10^5`
- `1 <= A[i] <= 10^9`
- `0 <= L <= R < N`

### Input Format

- The first argument is the integer array `A`.
- The second argument is the 2D integer array `B`.

### Output Format

Return an integer array of length `M` where the `i-th` element is the answer for the `i-th` query in `B`.

### Example

**Input:**
```
A = [1, 2, 3, 4, 5]
B = [[0, 3], [1, 2]]
```

**Output:**
```
[10, 5]
```
</details>

<details>
<summary><h2>14. In-place Prefix Sum</h2></summary>

### Problem Description

Given an array A of N integers. Construct prefix sum of the array in the given array itself.

### Problem Constraints

- 1 <= N <= 10^5
- 1 <= A[i] <= 10^3

### Input Format

Only argument A is an array of integers.

### Output Format

Return an array of integers denoting the prefix sum of the given array.

### Example

**Input 1:**
```
A = [1, 2, 3, 4, 5]
```

**Input 2:**
```
A = [4, 3, 2]
```

**Output 1:**
```
[1, 3, 6, 10, 15]
```

**Output 2:**
```
[4, 7, 9]
```

### Example Explanation

**Explanation 1:**
The prefix sum array of [1, 2, 3, 4, 5] is [1, 3, 6, 10, 15].

**Explanation 2:**
The prefix sum array of [4, 3, 2] is [4, 7, 9].

### Solution Approach

To construct the prefix sum in-place:
1. Start from the second element (index 1)
2. For each position i, add the value at position i-1 to the current value
3. Continue this process until the end of the array

This replaces each element with the sum of all elements up to and including its position.

### Code Solution

```python
def prefixSum(A):
    for i in range(1, len(A)):
        A[i] += A[i-1]
    return A
```

### Complexity Analysis

- **Time Complexity**: O(N) - We iterate through the array once
- **Space Complexity**: O(1) - We modify the array in-place without using additional space

</details>

<details>
<summary><h2>15. Equilibrium Index of an Array</h2></summary>

### Problem Description

You are given an array A of integers of size N.

Your task is to find the equilibrium index of the given array.

The equilibrium index of an array is an index such that the sum of elements at lower indexes is equal to the sum of elements at higher indexes.

If there are no elements that are at lower indexes or at higher indexes, then the corresponding sum of elements is considered as 0.

**Note:**
- Array indexing starts from 0.
- If there is no equilibrium index then return -1.
- If there are more than one equilibrium indexes then return the minimum index.

### Problem Constraints
- 1 <= N <= 10^5
- -10^5 <= A[i] <= 10^5

### Input Format
First argument is an array A.

### Output Format
Return the equilibrium index of the given array. If no such index is found then return -1.

### Example

**Input 1:**
```
A = [-7, 1, 5, 2, -4, 3, 0]
```

**Input 2:**
```
A = [1, 2, 3]
```

**Output 1:**
```
3
```

**Output 2:**
```
-1
```

### Example Explanation

**Explanation 1:**
```
i   Sum of elements at lower indexes    Sum of elements at higher indexes
0                   0                                   7
1                  -7                                   6
2                  -6                                   1
3                  -1                                  -1
4                   1                                   3
5                  -3                                   0
6                   0                                   0
```

3 is an equilibrium index, because: 
A[0] + A[1] + A[2] = A[4] + A[5] + A[6]

**Explanation 2:**
```
i   Sum of elements at lower indexes    Sum of elements at higher indexes
0                   0                                   5
1                   1                                   3
2                   3                                   0
```
Thus, there is no such index.

### Solution Approach

#### Intuition
To find the equilibrium index, we need to compare the sum of elements to the left of an index with the sum of elements to the right of it. A naive approach would require O(n^2) time complexity, but we can optimize this to O(n) by:

1. First calculating the total sum of the array
2. Then iterating through the array while maintaining a running sum of elements encountered so far
3. At each index, the sum of right elements = totalSum - leftSum - current element
4. An equilibrium index occurs when leftSum equals rightSum

#### Algorithm
1. Calculate the sum of all array elements
2. Initialize a variable leftSum = 0
3. Iterate through each index i of the array:
   - Calculate rightSum = totalSum - leftSum - A[i]
   - If leftSum equals rightSum, return the current index i
   - Update leftSum += A[i]
4. If no equilibrium index is found, return -1

#### Time Complexity
- O(n) - We make two passes through the array: one to calculate the total sum and one to find the equilibrium index

#### Space Complexity
- O(1) - We use only a constant amount of extra space

### Code Solution

```python
def equilibrium_index(A):
    n = len(A)
    
    # Calculate the total sum of the array
    total_sum = sum(A)
    
    # Initialize left_sum to track the running sum from left
    left_sum = 0
    
    # Iterate through the array
    for i in range(n):
        # Right sum = total sum - left sum - current element
        right_sum = total_sum - left_sum - A[i]
        
        # Check if this is an equilibrium index
        if left_sum == right_sum:
            return i
        
        # Update left sum for the next iteration
        left_sum += A[i]
    
    # If no equilibrium index is found
    return -1
```

### Alternative Solution in Java

```java
public class Solution {
    public int solve(int[] A) {
        int n = A.length;
        
        // Calculate total sum
        long totalSum = 0;
        for (int i = 0; i < n; i++) {
            totalSum += A[i];
        }
        
        // Traverse the array to find equilibrium index
        long leftSum = 0;
        for (int i = 0; i < n; i++) {
            // Right sum = total sum - left sum - current element
            long rightSum = totalSum - leftSum - A[i];
            
            if (leftSum == rightSum) {
                return i;
            }
            
            leftSum += A[i];
        }
        
        return -1;
    }
}
```

### Dry Run Example

Let's trace through the algorithm with the given example:
`A = [-7, 1, 5, 2, -4, 3, 0]`

1. Calculate total sum = -7 + 1 + 5 + 2 + (-4) + 3 + 0 = 0
2. Initialize left_sum = 0

3. Iteration 1: i = 0
   - right_sum = 0 - 0 - (-7) = 7
   - left_sum (0) != right_sum (7)
   - Update left_sum = 0 + (-7) = -7

4. Iteration 2: i = 1
   - right_sum = 0 - (-7) - 1 = 6
   - left_sum (-7) != right_sum (6)
   - Update left_sum = -7 + 1 = -6

5. Iteration 3: i = 2
   - right_sum = 0 - (-6) - 5 = 1
   - left_sum (-6) != right_sum (1)
   - Update left_sum = -6 + 5 = -1

6. Iteration 4: i = 3
   - right_sum = 0 - (-1) - 2 = -1
   - left_sum (-1) == right_sum (-1) ✓
   - Return i = 3

Therefore, the equilibrium index is 3.

</details>

<details>
<summary><h2>16. Even Numbers in a Range</h2></summary>

**Problem Description**

You are given an array **A** of length **N** and **Q** queries given by the 2D array **B** of size **Q×2**. Each query consists of two integers **B[i][0]** and **B[i][1]**. For every query, your task is to find the count of even numbers in the range from **A[B[i][0]]** to **A[B[i][1]]**.

**Problem Constraints**
- 1 <= N <= 10^5
- 1 <= Q <= 10^5
- 1 <= A[i] <= 10^9
- 0 <= B[i][0] <= B[i][1] < N

**Input Format**
- First argument A is an array of integers.
- Second argument B is a 2D array of integers.

**Output Format**
- Return an array of integers.

**Example Input**

Input 1:
```
A = [1, 2, 3, 4, 5]
B = [
   [0, 2]
   [2, 4]
   [1, 4]
]
```

Input 2:
```
A = [2, 1, 8, 3, 9, 6]
B = [
   [0, 3]
   [3, 5]
   [1, 3]
   [2, 4]
]
```

**Example Output**

Output 1:
```
[1, 1, 2]
```

Output 2:
```
[2, 1, 1, 1]
```

**Example Explanation**

For Input 1:
```
The subarray for the first query is [1, 2, 3] (index 0 to 2) which contains 1 even number.
The subarray for the second query is [3, 4, 5] (index 2 to 4) which contains 1 even number.
The subarray for the third query is [2, 3, 4, 5] (index 1 to 4) which contains 2 even numbers.
```

For Input 2:
```
The subarray for the first query is [2, 1, 8, 3] (index 0 to 3) which contains 2 even numbers.
The subarray for the second query is [3, 9, 6] (index 3 to 5) which contains 1 even number.
The subarray for the third query is [1, 8, 3] (index 1 to 3) which contains 1 even number.
The subarray for the fourth query is [8, 3, 9] (index 2 to 4) which contains 1 even number.
```

</details>

<details>
<summary><h2>17. Product Array Puzzle</h2></summary>

**Problem Description**

Given an array of integers **A**, find and return the product array of the same size where the ith element of the product array will be equal to the product of all the elements divided by the ith element of the array.

**Note:** 
- It is always possible to form the product array with integer (32 bit) values. 
- Solve it without using the division operator.

**Problem Constraints**
- 2 <= length of the array <= 1000
- 1 <= A[i] <= 10

**Input Format**
```
The only argument given is the integer array A.
```

**Output Format**
```
Return the product array.
```

**Example**

Input 1:
```
A = [1, 2, 3, 4, 5]
```

Output 1:
```
[120, 60, 40, 30, 24]
```

Input 2:
```
A = [5, 1, 10, 1]
```

Output 2:
```
[10, 50, 5, 50]
```

</details>
