[**LeetCode Submissions**](src/LeetCode)

**[1. Matrix Spiral Traversal:]((Miscellaneous/P1_MatrixSpiralTraversal.java)** Given a positive integer n, generate a square matrix filled with elements from 1 to n^2 in spiral order.
EXAMPLE:\
Input: 3\
Output:\
[\
 [1, 2, 3],\
 [8, 9, 4],\
 [7, 6. 5]\
]\
\
**[2. MoveZeroes :](src/Miscellaneous/P1_MatrixSpiralTraversal.java)** Move all zeroes to end of array
. Given an array of random numbers, Push all the zero’s of a given array to the end of the array. For example, if the given arrays is {1, 9, 8, 4, 0, 0, 2, 7, 0, 6, 0}, it should be changed to {1, 9, 8, 4, 2, 7, 6, 0, 0, 0, 0}. The order of all other elements should be same. Expected time complexity is O(n) and extra space is O(1).\
\
**[3. ClosestMultiple :](src/Miscellaneous/P3_ClosestMultiple.java)** Find the number closest to n and divisible by m.\
Given two integers n and m. The problem is to find the number closest to n and divisible by m. If there are more than one such number, then output the one having maximum absolute value. If n is completely divisible by m, then output n only. Time complexity of O(1) is required.\
\
**[4. NonDecreasing :](src/Miscellaneous/P4_NonDecreasing.java)** Given an array with n integers, your task is to check if it could become non-decreasing by modifying at most 1 element.\
We define an array is non-decreasing if array\[i] <= array\[i + 1] holds for every i (1 <= i < n).\
Example 1:\
Input: \[4,2,3]\
Output: True\
Explanation: You could modify the first 4 to 1 to get a non-decreasing array.\
Example 2:\
Input: \[4,2,1]\
Output: False\
Explanation: You can't get a non-decreasing array by modify at most one element.

**[5. Look&SaySequence :](src/Miscellaneous/P5_LookAndSaySequence.java)** Given n, the no. of rows, print the following pattern :\
1\
11\
21\
1211\
111221\
312211\
13112221    

**[6. Repeated Product Numbers :](src/Miscellaneous/P6_RepeatedProductNumbers.java)** 
The number 1827 is an interesting number, because 1827 = 21*87, and all of the same digits appear on both sides of the =. The number 136948 has the same property: 136948=146 * 938.
                                                                                      
Such numbers are called Repeated Product Numbers. More precisely, a number 'p' is a Repeated Product Number if it has a pair of factors, 'a' and 'b', where a*b=p, and together, a and b have exactly the same digits, in exactly the same quantities, as 'p'. None of the numbers p, a or b can have leading zeros and allow a and b to have differing number of digits, and p to have any number of digits. Here are some more examples:\
126 = 6 * 21\
10251 = 51 * 201\
702189 = 9 * 78021\
29632 = 32 * 926                                                                                      

Given a number X, find the smallest Repeated Product Number which is greater than or equal to X.
                                        