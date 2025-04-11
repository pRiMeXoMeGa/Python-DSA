# Array and String Problems

## Table of Contents
1. [Leaders in an Array](#1-leaders-in-an-array)
2. [Closest MinMax](#2-closest-minmax)
3. [Special Subsequences "AG"](#3-special-subsequences-ag)
4. [Best Time to Buy and Sell Stocks I](#4-best-time-to-buy-and-sell-stocks-i)
5. [Amazing Subarrays](#5-amazing-subarrays)
6. [Even Subarrays](#6-even-subarrays)
7. [Bulbs](#7-bulbs)
8. [Pick from both sides!](#8-pick-from-both-sides)

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

## 5. Amazing Subarrays

**Problem Description**
You are given a string **S**, and you have to find all the **amazing substrings** of **S**.
An amazing Substring is one that starts with a **vowel** (a, e, i, o, u, A, E, I, O, U).

**Problem Constraints**
1 <= length(S) <= 1e6
S can have special characters

**Input Format**
Only argument given is string S.

**Output Format**
Return a single integer X mod 10003, here X is the number of Amazing Substrings in given the string.

**Example Input**
Input:
```
ABEC
```

**Example Output**
Output:
```
6
```

**Example Explanation**
Explanation:
```
Amazing substrings of given string are :
1. A
2. AB
3. ABE
4. ABEC
5. E
6. EC
here number of substrings are 6 and 6 % 10003 = 6.
```

---

## 6. Even Subarrays

**Problem Description**
You are given an integer array **A**.
Decide whether it is possible to divide the array into one or more subarrays of **even length** such that the **first** and **last** element of all subarrays will be **even**.
Return "**YES**" if it is possible; otherwise, return "**NO**" (without quotes).

**Problem Constraints**
1 <= |A|, A[i] <= 106

**Input Format**
The first and the only input argument is an integer array, A.

**Output Format**
Return a string "YES" or "NO" denoting the answer.

**Example Input**
Input 1:
```
 A = [2, 4, 8, 6]
```

Input 2:
```
 A = [2, 4, 8, 7, 6]
```

**Example Output**
Output 1:
```
 "YES"
```

Output 2:
```
 "NO"
```

**Example Explanation**
Explanation 1:
```
 We can divide A into [2, 4] and [8, 6].
```

Explanation 2:
```
 There is no way to divide the array into even length subarrays.
```

---

## 7. Bulbs

**Problem Description**
A wire connects **N** light bulbs.

Each bulb has a switch associated with it; however, due to faulty wiring, a switch also changes the state of all the bulbs to the right of the current bulb.
Given an initial state of all bulbs, find the **minimum number** of switches you have to press to turn on all the bulbs.
You can press the same switch multiple times.
**Note:** **0** represents the bulb is off and **1** represents the bulb is on.

**Problem Constraints**
0 <= N <= 5×105
0 <= A[i] <= 1

**Input Format**
The first and the only argument contains an integer array A, of size N.

**Output Format**
Return an integer representing the minimum number of switches required.

**Example Input**
Input 1:
```
 A = [0, 1, 0, 1]
```

Input 2:
```
 A = [1, 1, 1, 1]
```

**Example Output**
Output 1:
```
 4
```

Output 2:
```
 0
```

**Example Explanation**
Explanation 1:
```
 press switch 0 : [1 0 1 0]
 press switch 1 : [1 1 0 1]
 press switch 2 : [1 1 1 0]
 press switch 3 : [1 1 1 1]
```

Explanation 2:
```
 There is no need to turn any switches as all the bulbs are already on.
```

---

## 8. Pick from both sides!

**Problem Description**
You are given an integer array **A** of size **N**.
You have to perform **B** operations. In one operation, you can remove either the leftmost or the rightmost element of the array **A**.
Find and return the **maximum possible sum** of the **B elements** that were removed after the **B** operations.

**NOTE:** Suppose **B = 3**, and array A contains 10 elements, then you can:
* Remove 3 elements from front and 0 elements from the back, OR
* Remove 2 elements from front and 1 element from the back, OR
* Remove 1 element from front and 2 elements from the back, OR
* Remove 0 elements from front and 3 elements from the back.

**Problem Constraints**
1 <= N <= 105
1 <= B <= N
-103 <= A[i] <= 103

**Input Format**
First argument is an integer array **A**.
Second argument is an integer **B**.

**Output Format**
Return an integer denoting the maximum possible sum of elements you removed.

**Example Input**
Input 1:
```
 A = [5, -2, 3 , 1, 2]
 B = 3
```

Input 2:
```
 A = [ 2, 3, -1, 4, 2, 1 ]
 B = 4
```

**Example Output**
Output 1:
```
 8
```

Output 2:
```
 9
```

**Example Explanation**
Explanation 1:
```
 Remove element 5 from front and element (1, 2) from back so we get 5 + 1 + 2 = 8
```

Explanation 2:
```
 Remove the first element and the last 3 elements. So we get 2 + 4 + 2 + 1 = 9
```

---
