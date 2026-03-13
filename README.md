# Import NumPy
import numpy as np

# -------------------------
# Vector Example
# -------------------------
vector = np.array([1, 2, 3, 4])

print("Vector:")
print(vector)

# Vector operations
print("Vector Sum:", np.sum(vector))
print("Vector Mean:", np.mean(vector))
print("Vector Square:", np.square(vector))

# -------------------------
# Matrix Example
# -------------------------
matrix1 = np.array([[1, 2],
                    [3, 4]])

matrix2 = np.array([[5, 6],
                    [7, 8]])

print("\nMatrix 1:")
print(matrix1)

print("\nMatrix 2:")
print(matrix2)

# Matrix addition
addition = matrix1 + matrix2
print("\nMatrix Addition:")
print(addition)

# Matrix subtraction
subtraction = matrix1 - matrix2
print("\nMatrix Subtraction:")
print(subtraction)

# Matrix multiplication
multiplication = np.dot(matrix1, matrix2)
print("\nMatrix Multiplication:")
print(multiplication)

# Transpose of matrix
transpose = matrix1.T
print("\nTranspose of Matrix 1:")
print(transpose)

# Determinant
det = np.linalg.det(matrix1)
print("\nDeterminant of Matrix 1:", det)
