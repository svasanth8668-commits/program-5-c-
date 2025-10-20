# program-5-c-
C module 5
EX NO:5-c) Sum of opposite diagonal of a matrix. 

Date:19/10/2025 

Name: VASANTH S 

Ref no: 25017538

AIM:
To write a C program to find the sum of opposite diagonal elements of a given matrix.

ALGORITHM:
1) Get a matrix as an input from the user.
2) Find the sum of diagonal elements using for loop anf if else statements.
3) print the result using printf() function.

PROGRAM:
```
#include <stdio.h>

int main()
{
    int n1,n2;
    scanf("%d %d",&n1,&n2);
    int mat[n1][n2];
    for(int i=0;i<n1;i++)
    {
        for(int j=0;j<n2;j++)
        {
            scanf("%d",&mat[i][j]);
        }
    }
    int sum=0;
    for(int i=0;i<n1;i++)
    {
        for(int j=0;j<=n2;j++)
        {
            if(i+j==2){
            printf("%d ",mat[i][j]);
            sum+=mat[i][j];}
        }printf("\n");
    }printf("The Sum of Opposite Diagonal Elements of a Matrix =  %d",sum);  
    return 0;
}

```

OUTPUT:

<img width="1096" height="280" alt="Screenshot 2025-10-20 201924" src="https://github.com/user-attachments/assets/04ecb789-b123-4ae4-b5b6-1efa6a5b8619" />

RESULT:

Thus the C program to find the sum of opposite diagonal elements of a given matrix is executed successfully.









