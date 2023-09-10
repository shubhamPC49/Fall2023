## Lab 1 – Basic NumPy Operations

**Due Date**: September 24 11:59 PM EST.


The purpose of this lab is to practice how to use NumPy to create 2-D arrays and easily compute mathematical operations.
NumPy (Numerical Python) is an open-source package. 
In this lab you will practice how to create arrays and use NumPy array operations.
Use indexing and slicing for 2-D arrays.
Find the shape of an array, reshape it and stack it horizontally and vertically, 
Use the NumPy Linear Algebra package to solve system of Linear Equations.

## Part A- Create a Notebook to demonstrate NumPy Operations.

 1. Create an array that starts from the integer 1, ends at 20, incremented by 3.
 2. Create a new array of shape 3 with random numbers between 0 and 1.
 3. Create a 2 D array `[[10,20,45], [30,12,16], [42,17,56]]` and perform the following operations: 
	 - Slice the 2D array to get the first two rows, slice the 2D array to get the last two rows.
 4. Create two 2x2 arrays and demonstrate how you can stack the elements vertically, horizontally, and split the arrays into smaller arrays.
 5. Create two matrices `X= ([[5, 7, 2], [4, 5, 6], [7, 4 ,2]]) Y= ([[4, 2], [6, 2], [4, 2]]),` 
	 - Is it possible to multiply these matrices? 
	 - Demonstrate the case when it is not possible to.
 6. Create two arrays, `x = ([2, -1, -8]) y = ([3, 1, -2]),`
	 - Find the Shape, Number of dimensions of vector x.
	 - Reshape the vector x to a matrix of size (3,1) and determine the number of dimensions after reshaping y to a matrix of (3,1).
 7. How does broadcasting work? Demonstrate the subtraction, multiplication by considering a 3 x 3 matrix.

**Instructions**

 1. *Feel free to add additional Markdown elements (description/additional comments)*
 2. *Push the notebook to your lab-submission fork, and create a PR*

       

## Part B- Linear Equations
Determine the singularity of the system of equations, comment on the expected solution of the system. Solve the system of equations if possible. Justify the reason why you believe the system can or cannot be solved using numpy functions.
### Part B.1

1. 4x + y - 2z = 10
2. 2x - 3y + 2z = -4
3. x + 2y + 3z = 6

### Part B.2    		
1. 2x - y + 3z + 4w = 10
2. 4x - 2y + 6z + 8w = 20
3. 3x + y - 2z + 2w = 3
4. x + 3y - 4z + w = -1


**Instructions**

 1. *Publish the notebook as an HTML using GitHub Pages* 
 2. *In the PR description (created in Part A) - add the direct link to the HTML.*


## Late Submission Policy
1. 10% of the grade will be deducted for each day that your submission is late.