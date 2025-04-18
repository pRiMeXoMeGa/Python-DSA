# Array and String Problems (Additional)

## Table of Contents
1. [Subarray in given range](#1-subarray-in-given-range)
2. [Maximum Subarray Easy](#2-maximum-subarray-easy)
3. [Sum of All Subarrays](#3-sum-of-all-subarrays)
4. [Generate all subarrays](#4-generate-all-subarrays)
5. [Good Subarrays Easy](#5-good-subarrays-easy)
6. [Counting Subarrays Easy](#6-counting-subarrays-easy)

---

<details>
<summary><h2>1. Subarray in given range</h2></summary>

**Problem Description**  
Given an array **A** of length **N**, return the subarray from **B** to **C**.

**Problem Constraints**  
1 <= N <= 10^5  
1 <= A[i] <= 10^9  
0 <= B <= C < N

**Input Format**  
The first argument A is an array of integers  
The remaining argument B and C are integers.

**Output Format**  
Return a subarray

**Example Input**  
Input 1:
```
A = [4, 3, 2, 6]
B = 1
C = 3
```

Input 2:
```
A = [4, 2, 2]
B = 0
C = 1
```

**Example Output**  
Output 1:
```
[3, 2, 6]
```

Output 2:
```
[4, 2]
```

**Example Explanation**  
Explanation 1:
```
The subarray of A from 1 to 3 is [3, 2, 6].
```

Explanation 2:
```
The subarray of A from 0 to 1 is [4, 2].
```
</details>

---

<details>
<summary><h2>2. Maximum Subarray Easy</h2></summary>

**Problem Description**  
You are given an integer array **C** of size **A**. Now you need to find a subarray (contiguous elements) so that the sum of contiguous elements is maximum. But the sum must not exceed **B**.

**Problem Constraints**  
1 <= A <= 10^3  
1 <= B <= 10^9  
1 <= C[i] <= 10^6

**Input Format**  
The first argument is the integer A.  
The second argument is the integer B.  
The third argument is the integer array C.

**Output Format**  
Return a single integer which denotes the maximum sum.

**Example Input**  
Input 1:
```
A = 5
B = 12
C = [2, 1, 3, 4, 5]
```

Input 2:
```
A = 3
B = 1
C = [2, 2, 2]
```

**Example Output**  
Output 1:
```
12
```

Output 2:
```
0
```

**Example Explanation**  
Explanation 1:
```
We can select {3,4,5} which sums up to 12 which is the maximum possible sum.
```

Explanation 2:
```
All elements are greater than B, which means we cannot select any subarray.
Hence, the answer is 0.
```
</details>

---

<details>
<summary><h2>3. Sum of All Subarrays</h2></summary>

**Problem Description**  
You are given an integer array **A** of length **N.** You have to find the sum of all subarray sums of A. More formally, a subarray is defined as a contiguous part of an array which we can obtain by deleting zero or more elements from either end of the array. A subarray sum denotes the sum of all the elements of that subarray.

**Note:** Be careful of integer overflow issues while calculations. Use appropriate datatypes.

**Problem Constraints**  
1 <= N <= 10^5  
1 <= Ai <= 10^4

**Input Format**  
The first argument is the integer array A.

**Output Format**  
Return a single integer denoting the sum of all subarray sums of the given array.

**Example Input**  
Input 1:
```
A = [1, 2, 3]
```

Input 2:
```
A = [2, 1, 3]
```

**Example Output**  
Output 1:
```
20
```

Output 2:
```
19
```

**Example Explanation**  
Explanation 1:
```
The different subarrays for the given array are: [1], [2], [3], [1, 2], [2, 3], [1, 2, 3].
Their sums are: 1 + 2 + 3 + 3 + 5 + 6 = 20
```

Explanation 2:
```
The different subarrays for the given array are: [2], [1], [3], [2, 1], [1, 3], [2, 1, 3].
Their sums are: 2 + 1 + 3 + 3 + 4 + 6 = 19
```
</details>

---

<details>
<summary><h2>4. Generate all subarrays</h2></summary>

**Problem Description**  
You are given an array **A** of **N** integers. Return a 2D array consisting of all the subarrays of the array  
**Note:** The **order** of the subarrays in the resulting 2D array **does not matter**.

**Problem Constraints**  
1 <= N <= 100  
1 <= A[i] <= 10^5

**Input Format**  
First argument A is an array of integers.

**Output Format**  
Return a 2D array of integers in any order.

**Example Input**  
Input 1:
```
A = [1, 2, 3]
```

Input 2:
```
A = [5, 2, 1, 4]
```

**Example Output**  
Output 1:
```
[[1], [1, 2], [1, 2, 3], [2], [2, 3], [3]]
```

Output 2:
```
[[1], [1, 4], [2], [2, 1], [2, 1, 4], [4], [5], [5, 2], [5, 2, 1], [5, 2, 1, 4]]
```

**Example Explanation**  
For Input 1:
```
All the subarrays of the array are returned. There are a total of 6 subarrays.
```

For Input 2:
```
All the subarrays of the array are returned. There are a total of 10 subarrays.
```
</details>

---

<details>
<summary><h2>5. Good Subarrays Easy</h2></summary>

**Problem Description**  
Given an array of integers **A**, a subarray of an array is said to be good if it fulfills any one of the criteria:  
1. Length of the subarray is be even, and the sum of all the elements of the subarray must be less than **B**.  
2. Length of the subarray is be odd, and the sum of all the elements of the subarray must be greater than **B**.  
Your task is to find the count of good subarrays in A.

**Problem Constraints**  
1 <= **len(A)** <= 5 x 10^3  
1 <= **A[i]** <= 10^3  
1 <= **B** <= 10^7

**Input Format**  
The first argument given is the integer array A.  
The second argument given is an integer B.

**Output Format**  
Return the count of good subarrays in A.

**Example Input**  
Input 1:
```
A = [1, 2, 3, 4, 5]
B = 4
```

Input 2:
```
A = [13, 16, 16, 15, 9, 16, 2, 7, 6, 17, 3, 9]
B = 65
```

**Example Output**  
Output 1:
```
6
```

Output 2:
```
36
```

**Example Explanation**  
Explanation 1:
```
Even length good subarrays = {1, 2}
Odd length good subarrays = {1, 2, 3}, {1, 2, 3, 4, 5}, {2, 3, 4}, {3, 4, 5}, {5}
```

Explanation 2:
```
There are 36 good subarrays
```
</details>

---

<details>
<summary><h2>6. Counting Subarrays Easy</h2></summary>

**Problem Description**  
Given an array **A** of **N** non-negative numbers and a non-negative number **B,** you need to find the **number of subarrays in A with a sum less than B.** We may assume that there is no overflow.

**Problem Constraints**  
1 <= N <= 5 x 10^3  
1 <= A[i] <= 1000  
1 <= B <= 10^7

**Input Format**  
First argument is an integer array **A**.  
Second argument is an integer **B**.

**Output Format**  
Return an integer denoting the **number of subarrays in A having sum less than B**.

**Example Input**  
Input 1:
```
A = [2, 5, 6]
B = 10
```

Input 2:
```
A = [1, 11, 2, 3, 15]
B = 10
```

**Example Output**  
Output 1:
```
4
```

Output 2:
```
4
```

**Example Explanation**  
Explanation 1:
```
The subarrays with sum less than B are {2}, {5}, {6} and {2, 5},
```

Explanation 2:
```
The subarrays with sum less than B are {1}, {2}, {3} and {2, 3}
```
</details>

---
