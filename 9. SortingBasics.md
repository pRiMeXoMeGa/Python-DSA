# Coding Problems Collection

## Table of Contents

1. [Q1. Sort by Color](#q1-sort-by-color)
2. [Q2. Arithmetic Progression?](#q2-arithmetic-progression)
3. [Q3. Tens Digit Sorting](#q3-tens-digit-sorting)
4. [Q4. Elements Removal](#q4-elements-removal)
5. [Q5. Noble Integer](#q5-noble-integer)
6. [Q6. Factors Sort](#q6-factors-sort)
7. [Q7. Largest Number](#q7-largest-number)

---

## Q1. Sort by Color

<details>
<summary><strong>Problem Description</strong></summary>

Given an array with **N** objects colored **red, white, or blue**, sort them so that objects of the same color are adjacent, with the colors in the **order red, white, and blue.**

We will represent the colors as:
- `red -> 0`
- `white -> 1` 
- `blue -> 2`

**Note:** Using the library sort function is not allowed.

**Problem Constraints**
- 1 <= N <= 1000000
- 0 <= A[i] <= 2

**Input Format**
First and only argument of input contains an integer array A.

**Output Format**
Return an integer array in asked order

**Example Input**

Input 1:
```
A = [0, 1, 2, 0, 1, 2]
```

Input 2:
```
A = [0]
```

**Example Output**

Output 1:
```
[0, 0, 1, 1, 2, 2]
```

Output 2:
```
[0]
```

</details>

---

## Q2. Arithmetic Progression?

<details>
<summary><strong>Problem Description</strong></summary>

Given an integer array **A** of size **N**. Return **1** if the array can be arranged to form an **arithmetic progression**, otherwise return **0**.

A sequence of numbers is called an arithmetic progression if the difference between any two consecutive elements is the same.

**Problem Constraints**
- 2 <= N <= 10⁵
- -10⁹ <= A[i] <= 10⁹

**Input Format**
The first and only argument is an integer array A of size N.

**Output Format**
Return **1** if the array can be rearranged to form an arithmetic progression, otherwise return **0.**

**Example Input**

Input 1:
```
A = [3, 5, 1]
```

Input 2:
```
A = [2, 4, 1]
```

**Example Output**

Output 1:
```
1
```

Output 2:
```
0
```

</details>

---

## Q3. Tens Digit Sorting

<details>
<summary><strong>Problem Description</strong></summary>

Given an array **A** of **N** integers. Sort the array in increasing order of the value at the tens place digit of every number.

- If a number has no tens digit, we can assume value to be 0.
- If 2 numbers have same tens digit, in that case number with max value will come first
- Solution should be based on comparator.

**Problem Constraints**
- 1 <= N <= 10⁵
- 1 <= A[i] <= 10⁹

**Input Format**
First argument A is an array of integers.

**Output Format**
Return the array after sorting

**Example Input**

Input 1:
```
A = [15, 11, 7, 19]
```

Input 2:
```
A = [2, 24, 22, 19]
```

**Example Output**

Output 1:
```
[7, 19, 15, 11]
```

Output 2:
```
[2, 19, 24, 22]
```

</details>

---

## Q4. Elements Removal

<details>
<summary><strong>Problem Description</strong></summary>

Given an integer array **A** of size **N**. You can **remove** any element from the array in one operation. The cost of this operation is the **sum of all elements** in the array present **before this operation**.

Find the **minimum cost** to remove all elements from the array.

**Problem Constraints**
- 0 <= N <= 1000
- 1 <= A[i] <= 10³

**Input Format**
First and only argument is an integer array A.

**Output Format**
Return an integer denoting the total cost of removing all elements from the array.

**Example Input**

Input 1:
```
A = [2, 1]
```

Input 2:
```
A = [5]
```

**Example Output**

Output 1:
```
4
```

Output 2:
```
5
```

</details>

---

## Q5. Noble Integer

<details>
<summary><strong>Problem Description</strong></summary>

Given an integer array **A**, find if an integer **p** exists in the array such that the number of integers greater than **p** in the array equals **p**.

**Problem Constraints**
- 1 <= |A| <= 2*10⁵
- -10⁸ <= A[i] <= 10⁸

**Input Format**
First and only argument is an integer array A.

**Output Format**
Return 1 if any such integer p is present else, return -1.

**Example Input**

Input 1:
```
A = [3, 2, 1, 3]
```

Input 2:
```
A = [1, 1, 3, 3]
```

**Example Output**

Output 1:
```
1
```

Output 2:
```
-1
```

</details>

---

## Q6. Factors Sort

<details>
<summary><strong>Problem Description</strong></summary>

You are given an array **A** of **N** elements. Sort the given array in increasing order of number of distinct factors of each element, i.e., element having the least number of factors should be the first to be displayed and the number having highest number of factors should be the last one. If 2 elements have same number of factors, then number with less value should come first. 

**Note:** You cannot use any extra space

**Problem Constraints**
- 1 <= N <= 10⁴
- 1 <= A[i] <= 10⁴

**Input Format**
First argument A is an array of integers.

**Output Format**
Return an array of integers.

**Example Input**

Input 1:
```
A = [6, 8, 9]
```

Input 2:
```
A = [2, 4, 7]
```

**Example Output**

Output 1:
```
[9, 6, 8]
```

Output 2:
```
[2, 7, 4]
```

</details>

---

## Q7. Largest Number

<details>
<summary><strong>Problem Description</strong></summary>

Given an array **A** of non-negative integers, arrange them such that they form the largest number.

**Note:** The result may be very large, so you need to return a string instead of an integer.

**Problem Constraints**
- 1 <= len(A) <= 100000
- 0 <= A[i] <= 2*10⁹

**Input Format**
The first argument is an array of integers.

**Output Format**
Return a string representing the largest number.

**Example Input**

Input 1:
```
A = [3, 30, 34, 5, 9]
```

Input 2:
```
A = [2, 3, 9, 0]
```

**Example Output**

Input 1:
```
9534330
```

Input 2:
```
9320
```

</details>

---
