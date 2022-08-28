# C-program-1
# Program to initialize a matrix of order m x n, with value equal to sum of their indices.


#include <stdio.h>
    int main ()
    {
 
        static int array[10][10];
        int i, j, m, n, sum = 0;
 
        printf("Enter the order of the matrix\n");
        scanf("%d %d", &m, &n);
        printf("The matrix is:\n");
        for (i = 0; i < m; ++i)
        {
            for (j = 0; j < n; ++j) 
            {    array[i][j]=i+j;
                printf("%d ",array[i][j]);
                if(j==n-1)
                {printf("\n");
                }
                
            }
        }
        return 0;
    }

