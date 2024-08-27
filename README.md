# EXPERIMENT 8:
# Multidimensional-Array
This repository contains C++ programs for various matrix operations, including user input for a 2D matrix, summing two matrices, multiplying two matrices, adding the diagonal elements of a matrix, and finding the transpose of a square matrix. Below, you'll find detailed explanations of the logic behind each program, along with instructions on how to compile and run them.    

## Introduction:
Working with matrices is a fundamental skill in programming, especially in areas such as data science, machine learning, and computer graphics. In this repository, we provide several essential matrix operations: capturing user input for a 2D matrix, summing matrices, multiplying matrices, adding diagonal elements, and finding the transpose of a matrix.  

## Program 1: User Input for a 2D Matrix
## Logic Explanation:  
This program takes user input for a 2D matrix of a specified size (rows and columns). The logic involves:  

1.Matrix Size Input: The user is prompted to enter the number of rows and columns for the matrix.    
2.Matrix Initialization: A 2D array (or vector) is initialized based on the input dimensions.   
3.Element Input: The user inputs the elements of the matrix. Nested loops are used to iterate through each element in the matrix and store the input in the corresponding position.  

## ALGORITHM
1. Start.
2. Initialize a matrix A of size rows x cols.
3. For each element (i, j):
   - Input the value from the user into A[i][j].
4. End.



## Program 2: Summing Two Matrices  
## Logic Explanation  
This program sums two matrices of the same dimensions. The steps are:    

1.Matrix Size Validation: Ensure both matrices have the same dimensions.    
2.Matrix Input: The user inputs the elements for two matrices.    
3.Matrix Summation: A new matrix is initialized to store the sum of the two matrices. Corresponding elements are added and stored in the new matrix.    
Output the Result: The resulting matrix is displayed to the user.   

## ALGORITHM
1. Start.
2. Initialize two matrices A and B of size rows x cols.
3. Initialize a result matrix C of the same size.
4. For each element at position (i, j):
   - Set C[i][j] = A[i][j] + B[i][j].
5. Output the result matrix C.
6. End.



## Program 3: Multiplying Two Matrices  
## Logic  explaination:
This program multiplies two matrices. The logic is as follows:    

1.Matrix Size Validation: Ensure that the number of columns in the first matrix equals the number of rows in the second matrix.    
2.Matrix Input: The user inputs the elements for both matrices.    
3.Matrix Multiplication: A new matrix is initialized to store the product of the two matrices. The multiplication is done by taking the dot product of the rows of the first matrix with the columns of the second matrix.  
Output the Result: The resulting matrix is displayed to the user.    

## ALGORITHM
1. Start.
2. Initialize two matrices A of size r1 x c1 and B of size r2 x c2.
3. Initialize a result matrix C of size r1 x c2.
4. If c1 != r2, multiplication is not possible, output an error.
5. For each element at position (i, j) in C:
   - Initialize C[i][j] = 0.
   - For each k from 0 to c1:
     - Add A[i][k] * B[k][j] to C[i][j].
6. Output the result matrix C.
7. End.




## Program 4: Diagonal Addition of a Matrix  
## Logic Explanation
This program adds the diagonal elements of a square matrix. The steps are:  

1.Matrix Size Input: The user is prompted to enter the size of the square matrix (i.e., the number of rows and columns, which must be equal).  
2.Matrix Input: The user inputs the elements of the square matrix.  
3.Diagonal Addition: The diagonal elements (elements where the row index equals the column index) are summed up.  
Output the Result: The sum of the diagonal elements is displayed.    


## Program 5: Finding Transpose of a Square Matrix
## Logic Explanation
This program finds the transpose of a square matrix. The logic involves:  

1.Matrix Size Input: The user inputs the size of the square matrix.  
2.Matrix Input: The user inputs the elements of the square matrix.  
3.Transpose Calculation: The transpose is calculated by swapping rows with columns.  
Output the Result: The transposed matrix is displayed to the user.  

## ALGORITHM

1. Start.
2. Initialize a matrix A of size rows x cols.
3. Initialize a transpose matrix T of size cols x rows.
4. For each element at position (i, j):
   - Set T[j][i] = A[i][j].
5. Output the transpose matrix T.
6. End.


## Conclusion
In this experiment we performed different programs on matrix
