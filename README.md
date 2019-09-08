# convert_matrix_to_echelon_form

-->Identifying special matrices


--->Instructions
In this assignment, we shall write a function that will test if a 4×4 matrix is singular, i.e. to determine if an inverse exists, before calculating it.
we shall use the method of converting a matrix to echelon form, and testing if this fails by leaving zeros that can’t be removed on the leading diagonal.

In the numpy package in Python, matrices are indexed using zero for the top-most column and left-most row. I.e., the matrix structure looks like this:
A[0, 0]  A[0, 1]  A[0, 2]  A[0, 3]
A[1, 0]  A[1, 1]  A[1, 2]  A[1, 3]
A[2, 0]  A[2, 1]  A[2, 2]  A[2, 3]
A[3, 0]  A[3, 1]  A[3, 2]  A[3, 3]

We can access the value of each element individually using,
A[n, m]

which will give the n'th row and m'th column (starting with zero). We can also access a whole row at a time using,
A[n]

Which we will see will be useful when calculating linear combinations of rows.
