# mathematics-lab-programs
'''find the dimension of subspace spanned by the vectors(1,2,3),(2,3,1) and (3,1,2)
import numpy as np 
v=np.array([[1,2,3],[2,3,1],[3,1,2]])
basis=np.linalg.matrix_rank(v)
dimension=v.shape[0]
print("Basis of the matrix is:",basis)
print("Dimension of the matrix is:",dimension)
