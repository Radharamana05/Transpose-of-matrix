# Transpose-of-matrix
# python program to know the transpose of a matrix.

N = 4 
def transpose(A, B): 
    for i in range(N): 
        for j in range(N): 
            B[i][j] = A[j][i] 
            
            
if __name__ == '__main__': 
    A = [[1, 1, 1, 1], [2, 2, 2, 2], [3, 3, 3, 3], [4, 4, 4, 4]] 
    B = [[0 for x in range(N)] for y in range(N)] 
transpose(A, B) 


print("Result matrix is:") 

for i in range(N): 
    for j in range(N): 
        print(B[i][j], " ", end='') 
        
    print() 


# output:
Result matrix is:
1  2  3  4  
1  2  3  4  
1  2  3  4  
1  2  3  4  
