# Matrix Operations Problems

## Table of Contents
- [Q1. Column Sum](#q1-column-sum)
- [Q2. Row Sum](#q2-row-sum)
- [Q3. Main Diagonal Sum](#q3-main-diagonal-sum)
- [Q4. Minor Diagonal Sum](#q4-minor-diagonal-sum)
- [Q5. Anti Diagonals](#q5-anti-diagonals)
- [Q6. Matrix Transpose](#q6-matrix-transpose)
- [Q7. Rotate Matrix](#q7-rotate-matrix)
- [Q8. Row to Column Zero](#q8-row-to-column-zero)

---

<details>
<summary>Q1. Column Sum</summary>

**Problem Description**  
You are given a 2D integer matrix A, return a 1D integer array containing column-wise sums of original matrix.

**Problem Constraints**  
- 1 <= A.size() <= 10³  
- 1 <= A[i].size() <= 10³  
- 1 <= A[i][j] <= 10³  

**Input Format**  
First argument is a 2D array of integers (2D matrix).

**Output Format**  
Return an array containing column-wise sums of original matrix.

**Example Input**  
Input 1:  
```
[1,2,3,4]
[5,6,7,8]
[9,2,3,4]
```

**Example Output**  
Output 1:  
```
{15,10,13,16}
```

**Example Explanation**  
Explanation 1:  
```
Column 1 = 1+5+9 = 15
Column 2 = 2+6+2 = 10
Column 3 = 3+7+3 = 13
Column 4 = 4+8+4 = 16
```

</details>

---

<details>
<summary>Q2. Row Sum</summary>

**Problem Description**  
You are given a 2D matrix **A** of integers. Your task is to compute the sum of elements in each row and return a 1D array where each element represents the sum of a corresponding row in the matrix.

**Problem Constraints**  
- 1 <= A.size() <= 10³  
- 1 <= A[i].size() <= 10³  
- 1 <= A[i][j] <= 10³  

**Input Format**  
First argument A is a 2D array of integers (2D matrix).

**Output Format**  
Return an array containing row-wise sums of original matrix.

**Example Input**  
Input 1:  
```
[1,2,3,4]
[5,6,7,8]
[9,2,3,4]
```

**Example Output**  
Output 1:  
```
[10,26,18]
```

**Example Explanation**  
Explanation 1:  
```
Row 1 = 1+2+3+4 = 10
Row 2 = 5+6+7+8 = 26
Row 3 = 9+2+3+4 = 18
```

</details>

---

<details>
<summary>Q3. Main Diagonal Sum</summary>

**Problem Description**  
You are given a **N X N** integer matrix. You have to find the sum of all the main diagonal elements of **A**.  
Main diagonal of a matrix **A** is a collection of elements **A[i, j]** such that `i = j`.

**Problem Constraints**  
- 1 <= **N** <= 10³  
- -1000 <= **A[i][j]** <= 1000  

**Input Format**  
There are 1 lines in the input. First 2 integers R, C are the number of rows and columns. Then R * C integers follow corresponding to the rowwise numbers in the 2D array **A**.

**Output Format**  
Return an integer denoting the sum of main diagonal elements.

**Example Input**  
Input 1:  
```
3 3 1 -2 -3 -4 5 -6 -7 -8 9
```

Input 2:  
```
2 2 3 2 2 3
```

**Example Output**  
Output 1:  
```
15
```

Output 2:  
```
6
```

**Example Explanation**  
Explanation 1:  
```
The size of matrix is 3.
So, considering the indexing from 0.
Main diagonal elements will be A[0][0], A[1][1] and A[2][2]
A[0][0] + A[1][1] + A[2][2] = 1 + 5 + 9 = 15
```

Explanation 2:  
```
The size of matrix is 2.
So, considering the indexing from 0.
Main diagonal elements will be A[0][0] and A[1][1].
A[0][0] + A[1][1] = 3 + 3 = 6
```

</details>

---

<details>
<summary>Q4. Minor Diagonal Sum</summary>

**Problem Description**  
You are given a **N X N** integer matrix. You have to find the sum of all the minor diagonal elements of **A**.  
Minor diagonal of a **M X M** matrix **A** is a collection of elements **A[i, j]** such that `i + j = M + 1` (where **i, j** are 1-based).

**Problem Constraints**  
- 1 <= **N** <= 10³  
- -1000 <= **A[i][j]** <= 1000  

**Input Format**  
First and only argument is a 2D integer matrix **A**.

**Output Format**  
Return an integer denoting the sum of minor diagonal elements.

**Example Input**  
Input 1:  
```
 A = [[1, -2, -3],
      [-4, 5, -6],
      [-7, -8, 9]]
```

Input 2:  
```
 A = [[3, 2],
      [2, 3]]
```

**Example Output**  
Output 1:  
```
-5
```

Output 2:  
```
4
```

**Example Explanation**  
Explanation 1:  
```
 A[1][3] + A[2][2] + A[3][1] = (-3) + 5 + (-7) = -5
```

Explanation 2:  
```
 A[1][2] + A[2][1] = 2 + 2 = 4
```

</details>

---

<details>
<summary>Q5. Anti Diagonals</summary>

**Problem Description**  
Give a **N * N** square matrix **A**, return an array of its anti-diagonals. Look at the example for more details.

**Problem Constraints**  
- 1 <= **N** <= 1000  
- 1 <= **A[i][j]** <= 1e9  

**Input Format**  
Only argument is a 2D array **A** of size **N** * **N**.

**Output Format**  
Return a 2D integer array of size (2 * **N** - 1) * **N**, representing the anti-diagonals of input array **A**. The vacant spaces in the grid should be assigned to 0.

**Example Input**  
Input 1:  
```
1 2 3
4 5 6
7 8 9
```

Input 2:  
```
1 2
3 4
```

**Example Output**  
Output 1:  
```
1 0 0
2 4 0
3 5 7
6 8 0
9 0 0
```

Output 2:  
```
1 0
2 3
4 0
```

**Example Explanation**  
For input 1:  
```
The first anti diagonal of the matrix is [1 ], the rest spaces shoud be filled with 0 making the row as [1, 0, 0].
The second anti diagonal of the matrix is [2, 4 ], the rest spaces shoud be filled with 0 making the row as [2, 4, 0].
The third anti diagonal of the matrix is [3, 5, 7 ], the rest spaces shoud be filled with 0 making the row as [3, 5, 7].
The fourth anti diagonal of the matrix is [6, 8 ], the rest spaces shoud be filled with 0 making the row as [6, 8, 0].
The fifth anti diagonal of the matrix is [9 ], the rest spaces shoud be filled with 0 making the row as [9, 0, 0].
```

For input 2:  
```
The first anti diagonal of the matrix is [1 ], the rest spaces shoud be filled with 0 making the row as [1, 0].
The second anti diagonal of the matrix is [2, 3 ], the rest spaces shoud be filled with 0 making the row as [2, 3].
The third anti diagonal of the matrix is [4 ], the rest spaces shoud be filled with 0 making the row as [4, 0].
```

</details>

---

<details>
<summary>Q6. Matrix Transpose</summary>

**Problem Description**  
Given a 2D integer array **A**, return the transpose of **A**. The transpose of a matrix is the matrix flipped over its main diagonal, switching the matrix's row and column indices.

**Problem Constraints**  
- 1 <= A.size() <= 1000  
- 1 <= A[i].size() <= 1000  
- 1 <= A[i][j] <= 1000  

**Input Format**  
First argument is a 2D matrix of integers.

**Output Format**  
You have to return the Transpose of this 2D matrix.

**Example Input**  
Input 1:  
```
A = [[1, 2, 3],[4, 5, 6],[7, 8, 9]]
```

Input 2:  
```
A = [[1, 2],[1, 2],[1, 2]]
```

**Example Output**  
Output 1:  
```
[[1, 4, 7], [2, 5, 8], [3, 6, 9]]
```

Output 2:  
```
[[1, 1, 1], [2, 2, 2]]
```

**Example Explanation**  
Explanation 1:  
```
Clearly after converting rows to column and columns to rows of [[1, 2, 3],[4, 5, 6],[7, 8, 9]]
 we will get [[1, 4, 7], [2, 5, 8], [3, 6, 9]].
```

Explanation 2:  
```
After transposing the matrix, A becomes [[1, 1, 1], [2, 2, 2]]
```

</details>

---

<details>
<summary>Q7. Rotate Matrix</summary>

**Problem Description**  
You are given a n x n 2D matrix **A** representing an image. Rotate the image by 90 degrees (clockwise). You need to do this in place.  
**Note:** If you end up using an additional array, you will only receive partial score.

**Problem Constraints**  
- 1 <= n <= 1000  

**Input Format**  
First argument is a 2D matrix A of integers.

**Output Format**  
Return the 2D rotated matrix.

**Example Input**  
Input 1:  
```
 [
    [1, 2],
    [3, 4]
 ]
```

Input 2:  
```
 [
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9]
 ]
```

**Example Output**  
Output 1:  
```
 [
    [3, 1],
    [4, 2]
 ]
```

Output 2:  
```
 [
    [7, 4, 1],
    [8, 5, 2],
    [9, 6, 3]
 ]
```

**Example Explanation**  
Explanation 1:  
```
 After rotating the matrix by 90 degree:
 1 goes to 2, 2 goes to 4
 4 goes to 3, 3 goes to 1
```

Explanation 2:  
```
 After rotating the matrix by 90 degree:
 1 goes to 3, 3 goes to 9
 2 goes to 6, 6 goes to 8
 9 goes to 7, 7 goes to 1
 8 goes to 4, 4 goes to 2
```

</details>

---

<details>
<summary>Q8. Row to Column Zero</summary>

**Problem Description**  
You are given a 2D integer matrix A, make all the elements in a row or column zero if the A[i][j] = 0. Specifically, make entire ith row and jth column zero.

**Problem Constraints**  
- 1 <= A.size() <= 10³  
- 1 <= A[i].size() <= 10³  
- 0 <= A[i][j] <= 10³  

**Input Format**  
First argument is a 2D integer matrix A.

**Output Format**  
Return a 2D matrix after doing required operations.

**Example Input**  
Input 1:  
```
[1,2,3,4]
[5,6,7,0]
[9,2,0,4]
```

**Example Output**  
Output 1:  
```
[1,2,0,0]
[0,0,0,0]
[0,0,0,0]
```

**Example Explanation**  
Explanation 1:  
```
A[2][4] = A[3][3] = 0, so make 2nd row, 3rd row, 3rd column and 4th column zero.
```

</details>
