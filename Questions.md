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

## 5. Searching in an array where adjacent differ by at most k
[GeeksforGeeks Link](https://www.geeksforgeeks.org/problems/searching-in-an-array-where-adjacent-differ-by-at-most-k0456/1?itm_source=geeksforgeeks&itm_medium=article&itm_campaign=practice_card)

## 6. Search in a rotated sorted array
[Leetcode Link](https://leetcode.com/problems/search-in-rotated-sorted-array/description/)
