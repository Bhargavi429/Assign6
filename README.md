# Assign6 
A <- matrix(c(2, 0, 1, 3), ncol = 2)

B <- matrix(c(5, 2, 4, -1), ncol = 2)

#Find (A + B)

sum <-(A + B)
print("Sum of A and B:")
print(sum)

#Find (A - B)

difference <-(A - B)
print("Difference of A and B:")
print(difference)

#Using the diag() function to build a matrix of size 4 with the diagonal values 4, 1, 2, 3.

diag_matrix <-diag(c(4, 1, 2, 3))
print("Diagonal matrix of given values:")
print(diag_matrix)

#Generate the specified matrix

specified_matrix <-diag(3,5,5)
R <- matrix(c(3,2,2,2,2,1,3,0,0,0,1,0,3,0,0,1,0,0,3,0,1,0,0,0,3),5,5)
print(R)
