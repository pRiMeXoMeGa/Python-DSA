# Array and String Problems

## Table of Contents
1. [Leaders in an Array](#1-leaders-in-an-array)
2. [Closest MinMax](#2-closest-minmax)
3. [Special Subsequences "AG"](#3-special-subsequences-ag)
4. [Best Time to Buy and Sell Stocks I](#4-best-time-to-buy-and-sell-stocks-i)

## 1. Leaders in an Array

**Problem Description**
Given an integer array **A** containing **N** distinct integers, you have to find **all the leaders** in array **A**. An element is a leader if it is **strictly greater than** all the elements to its **right side.** **NOTE**: The rightmost element is always a leader.

**Problem Constraints**
1 <= N <= 10^5
1 <= A[i] <= 10^8

**Input Format**
There is a single input argument which a integer array **A**

**Output Format**
Return an integer array denoting all the **leader elements** of the array.

**Example Input**
Input 1:
```
 A = [16, 17, 4, 3, 5, 2]
```

Input 2:
```
 A = [5, 4]
```

**Example Output**
Output 1:
```
[17, 2, 5]
```

Output 2:
```
[5, 4]
```

**Example Explanation**
Explanation 1:
```
 Element 17 is strictly greater than all the elements on the right side to it.
 Element 2 is strictly greater than all the elements on the right side to it.
 Element 5 is strictly greater than all the elements on the right side to it.
 So we will return these three elements i.e [17, 2, 5], we can also return [2, 5, 17] or [5, 2, 17] or any other ordering.
```

Explanation 2:
```
 Element 5 is strictly greater than all the elements on the right side to it.
 Element 4 is strictly greater than all the elements on the right side to it.
 So we will return these two elements i.e [5, 4], we can also any other ordering.
```

---

## 2. Closest MinMax

**Problem Description**
Given an array **A**, find the size of the smallest subarray such that it contains at least one occurrence of the maximum value of the array
and at least one occurrence of the minimum value of the array.

**Problem Constraints**
1 <= **|A|** <= 2000

**Input Format**
First and only argument is vector **A**

**Output Format**
Return the length of the smallest subarray which has at least one occurrence of minimum and maximum element of the array

**Example Input**
Input 1:
```
A = [1, 3, 2]
```

Input 2:
```
A = [2, 6, 1, 6, 9]
```

**Example Output**
Output 1:
```
 2
```

Output 2:
```
 3
```

**Example Explanation**
Explanation 1:
```
 Take the 1st and 2nd elements as they are the minimum and maximum elements respectievly.
```

Explanation 2:
```
 Take the last 3 elements of the array.
```

---

## 3. Special Subsequences "AG"

**Problem Description**
You have given a string **A** having **Uppercase English letters**.
You have to find the number of pairs **(i, j)** such that **A[i] = 'A'**, **A[j] = 'G'** and **i < j**.

**Problem Constraints**
1 <= length(A) <= 10^5

**Input Format**
First and only argument is a string A.

**Output Format**
Return an long integer denoting the answer.

**Example Input**
Input 1:
```
 A = "ABCGAG"
```

Input 2:
```
 A = "GAB"
```

**Example Output**
Output 1:
```
 3
```

Output 2:
```
 0
```

**Example Explanation**
Explanation 1:
```
 Subsequence "AG" is 3 times in given string, the pairs are (0, 3), (0, 5) and (4, 5). 
```

Explanation 2:
```
 There is no subsequence "AG" in the given string.
```

---

## 4. Best Time to Buy and Sell Stocks I

**Problem Description**
Say you have an array, **A**, for which the **i**th element is the price of a given stock on day **i**.

If you were only permitted to complete at most one transaction (ie, buy one and sell one share of the stock), design an algorithm to find the maximum profit.
Return the **maximum** possible profit.

**Problem Constraints**
0 <= **A.size()** <= 700000

1 <= **A[i]** <= 10^7

**Input Format**
The first and the only argument is an array of integers, A.

**Output Format**
Return an integer, representing the maximum possible profit.

**Example Input**
Input 1:
```
A = [1, 2]
```

Input 2:
```
A = [1, 4, 5, 2, 4]
```

**Example Output**
Output 1:
```
1
```

Output 2:
```
4
```

**Example Explanation**
Explanation 1:
```
Buy the stock on day 0, and sell it on day 1.
```

Explanation 2:
```
Buy the stock on day 0, and sell it on day 2.
```

---
