KERNEL PCA:
----------------
----------------

1. Find the K Matrix using the kernel :   Kij = K(xi,xj)
2. Center the data: <MANDATORY>  Kc = K - InK - KIn + InKIn  
3. Apply Standard PCA
4. Find: lamda1= eigen value and alpha1= eigen vector <find all>
5. Normalize all eigen vectors
6. find proxy : SUM(i)-to-(n)[ K[xi,xj] * alpha(i) ]
