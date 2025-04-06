# Array Problems

## 1. Find the Maximum and Minimum Element in an Array

[GeeksforGeeks Link](https://www.geeksforgeeks.org/maximum-and-minimum-in-an-array/)

## 2. Rearrange an Array so that All Negative Numbers Appear Before All Positive Numbers

Given an array containing both positive and negative numbers in random order.
The task is to rearrange the array elements so that all negative numbers appear before all positive numbers.

**Note:** The given array does not contain any zeroes. The order of the resultant array does not matter.

### Example:

**Input:**
```
-12, 11, -13, -5, 6, -7, 5, -3, -6
```

**Output:**
```
-12 -13 -5 -7 -3 -6 11 6 5
```

### Code:

Just paste the below code in an editor and complete the `move` function.

```python
# Python program to Move all negative numbers
# to the beginning and positive to the end

def move(arr):
    # WRITE YOUR CODE HERE

if __name__ == "__main__":
    arr = [-12, 11, -13, -5, 6, -7, 5, -3, -6]
    ans = move(arr)

    for num in ans:
        print(num, end=" ")
    print()
```

## 3. Find the Union and Intersection of Two Sorted Arrays

[GeeksforGeeks Link](https://www.geeksforgeeks.org/problems/union-of-two-arrays3538/1)

## 4. Write a Program to Cyclically Rotate an Array by One

[GeeksforGeeks Link](https://www.geeksforgeeks.org/problems/cyclically-rotate-an-array-by-one2614/1)

## 5. Find first and last positions of an element in a sorted array
[GeeksforGeeks Link](https://practice.geeksforgeeks.org/problems/first-and-last-occurrences-of-x/0)

## 6. Searching in an array where adjacent differ by at most k
[GeeksforGeeks Link](https://www.geeksforgeeks.org/problems/searching-in-an-array-where-adjacent-differ-by-at-most-k0456/1?itm_source=geeksforgeeks&itm_medium=article&itm_campaign=practice_card)

## 7. Search in a rotated sorted array
[Leetcode Link](https://leetcode.com/problems/search-in-rotated-sorted-array/description/)

## 8. find duplicate in an array of N+1 Integers
[Leetcode_ link](https://leetcode.com/problems/find-the-duplicate-number/submissions/1591184118/)

## 9. Given an array which consists of only 0, 1 and 2. Sort the array without using any sorting algo
[GeeksforGeeks Link](https://practice.geeksforgeeks.org/problems/sort-an-array-of-0s-1s-and-2s/0)

## 10. Minimum no. of Jumps to reach end of an array
[GeeksforGeeks Link](https://www.geeksforgeeks.org/problems/minimum-number-of-jumps-1587115620/1)

[Solution](https://www.geeksforgeeks.org/minimum-number-jumps-reach-endset-2on-solution/)

## 11. Missing Number
[Leetcode Link](https://leetcode.com/problems/missing-number/description/)

## 12. Find Minimum in Rotated Sorted Array
[Leetcode Link](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/description/)

## 13. Range Sum Query

---

### Problem Description

You are given an integer array `A` of length `N`.

You are also given a 2D integer array `B` with dimensions `M x 2`, where each row denotes a `[L, R]` query.

For each query, you have to find the sum of all elements from index `L` to `R` in `A` (0-indexed).

More formally, find `A[L] + A[L + 1] + ... + A[R]` for each query.

---

### Problem Constraints

- `1 <= N, M <= 10^5`
- `1 <= A[i] <= 10^9`
- `0 <= L <= R < N`

---

### Input Format

- The first argument is the integer array `A`.
- The second argument is the 2D integer array `B`.

---

### Output Format

Return an integer array of length `M` where the `i-th` element is the answer for the `i-th` query in `B`.

---

### Example Input 1

```text
A = [1, 2, 3, 4, 5]
B = [[0, 3], [1, 2]]

Output 1
Output = [10, 5]
```

## 14. In-place Prefix Sum

## Problem Description
Given an array A of N integers. Construct prefix sum of the array in the given array itself.

## Problem Constraints
- 1 <= N <= 10^5
- 1 <= A[i] <= 10^3

## Input Format
Only argument A is an array of integers.

## Output Format
Return an array of integers denoting the prefix sum of the given array.

## Example Input
**Input 1:**
```
A = [1, 2, 3, 4, 5]
```

**Input 2:**
```
A = [4, 3, 2]
```

## Example Output
**Output 1:**
```
[1, 3, 6, 10, 15]
```

**Output 2:**
```
[4, 7, 9]
```

## Example Explanation
**Explanation 1:**
The prefix sum array of [1, 2, 3, 4, 5] is [1, 3, 6, 10, 15].

**Explanation 2:**
The prefix sum array of [4, 3, 2] is [4, 7, 9].

## Solution Approach
To construct the prefix sum in-place:
1. Start from the second element (index 1)
2. For each position i, add the value at position i-1 to the current value
3. Continue this process until the end of the array

This replaces each element with the sum of all elements up to and including its position.

## Code Solution
```python
def prefixSum(A):
    for i in range(1, len(A)):
        A[i] += A[i-1]
    return A
```

## Time and Space Complexity
- **Time Complexity**: O(N) - We iterate through the array once
- **Space Complexity**: O(1) - We modify the array in-place without using additional space

