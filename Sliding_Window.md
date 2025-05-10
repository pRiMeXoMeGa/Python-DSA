# Coding Questions Collection

## Table of Contents
- [Q1. Subarray with given sum and length](#q1-subarray-with-given-sum-and-length)
- [Q2. Minimum Swaps](#q2-minimum-swaps)
- [Q3. Spiral Order Matrix II](#q3-spiral-order-matrix-ii)
- [Q4. Subarray with least average](#q4-subarray-with-least-average)

---

<details>
<summary><h2 id="q1-subarray-with-given-sum-and-length">Q1. Subarray with given sum and length</h2></summary>

### Problem Description
Given an array **A** of length **N**. Also given are integers **B** and **C**.
Return 1 if there exists a subarray with length **B** having sum **C** and 0 otherwise

### Problem Constraints
- 1 <= N <= 10^5
- 1 <= A[i] <= 10^4
- 1 <= B <= N
- 1 <= C <= 10^9

### Input Format
First argument A is an array of integers.
The remaining arguments B and C are integers

### Output Format
Return 1 if such a subarray exist and 0 otherwise

### Example Input
**Input 1:**
```
A = [4, 3, 2, 6, 1]
B = 3
C = 11
```

**Input 2:**
```
A = [4, 2, 2, 5, 1]
B = 4
C = 6
```

### Example Output
**Output 1:**
```
1
```

**Output 2:**
```
0
```

### Example Explanation
**Explanation 1:**
```
The subarray [3, 2, 6] is of length 3 and sum 11.
```

**Explanation 2:**
```
There are no such subarray.
```
</details>

---

<details>
<summary><h2 id="q2-minimum-swaps">Q2. Minimum Swaps</h2></summary>

### Problem Description
Given an array of integers **A** and an integer **B**, find and return the minimum number of swaps required to bring all the numbers less than or equal to **B** together.

**Note:** It is possible to swap any two elements, not necessarily consecutive.

### Problem Constraints
- 1 <= length of the array <= 100000
- -10^9 <= A[i], B <= 10^9

### Input Format
The first argument given is the integer array A.
The second argument given is the integer B.

### Output Format
Return the minimum number of swaps.

### Example Input
**Input 1:**
```
 A = [1, 12, 10, 3, 14, 10, 5]
 B = 8
```

**Input 2:**
```
 A = [5, 17, 100, 11]
 B = 20
```

### Example Output
**Output 1:**
```
 2
```

**Output 2:**
```
 1
```

### Example Explanation
**Explanation 1:**
```
 A = [1, 12, 10, 3, 14, 10, 5]
 After swapping  12 and 3, A => [1, 3, 10, 12, 14, 10, 5].
 After swapping  the first occurence of 10 and 5, A => [1, 3, 5, 12, 14, 10, 10].
 Now, all elements less than or equal to 8 are together.
```

**Explanation 2:**
```
 A = [5, 17, 100, 11]
 After swapping 100 and 11, A => [5, 17, 11, 100].
 Now, all elements less than or equal to 20 are together.
```
</details>

---

<details>
<summary><h2 id="q3-spiral-order-matrix-ii">Q3. Spiral Order Matrix II</h2></summary>

### Problem Description
Given an integer **A**, generate a square matrix filled with elements from 1 to A^2 in spiral order and return the generated square matrix.

### Problem Constraints
1 <= **A** <= 1000

### Input Format
First and only argument is integer A

### Output Format
Return a 2-D matrix which consists of the elements added in spiral order.

### Example Input
**Input 1:**
```
1
```

**Input 2:**
```
2
```

**Input 3:**
```
5
```

### Example Output
**Output 1:**
```
[ [1] ]
```

**Output 2:**
```
[ [1, 2], 
  [4, 3] ]
```

**Output 3:**
```
[ [1,   2,  3,  4, 5], 
  [16, 17, 18, 19, 6], 
  [15, 24, 25, 20, 7], 
  [14, 23, 22, 21, 8], 
  [13, 12, 11, 10, 9] ]
```

### Example Explanation
**Explanation 1:**
```
Only 1 is to be arranged.
```

**Explanation 2:**
```
1 --> 2
      |
      |
4<--- 3
```
</details>

---

<details>
<summary><h2 id="q4-subarray-with-least-average">Q4. Subarray with least average</h2></summary>

### Problem Description
Given an array **A** of size **N**, find the subarray of size **B** with the least average.

### Problem Constraints
```
1 <= B <= N <= 10^5
-10^5 <= A[i] <= 10^5
```

### Input Format
First argument contains an array A of integers of size N.
Second argument contains integer B.

### Output Format
Return the index of the first element of the subarray of size B that has least average.
Array indexing starts from 0.

### Example Input
**Input 1:**
```
A = [3, 7, 90, 20, 10, 50, 40]
B = 3
```

**Input 2:**
```
A = [3, 7, 5, 20, -10, 0, 12]
B = 2
```

### Example Output
**Output 1:**
```
3
```

**Output 2:**
```
4
```

### Example Explanation
**Explanation 1:**
```
Subarray between indexes 3 and 5
The subarray {20, 10, 50} has the least average 
among all subarrays of size 3.
```

**Explanation 2:**
```
Subarray between [4, 5] has minimum average
```
</details>
