# alx-interview

In order to implement the function pascal_triangle(n), we follow these steps:

1. Define the function pascal_triangle(n). 
2. Inside it, define a variable result initialized to an empty list.
3. Implement a loop that iterates n times and in each iteration, create a new row of the triangle as a list of integers, starting with the number 1.
4. For rows 1 and 2, append the number 1 to the end of the row.
5. For rows greater than 2, compute the values of the remaining elements in the row using the formula result[i][j] = result[i-1][j-1] + result[i-1][j]. Append this value to the end of the row.
6. After the loop, return result.