# Matrices_Ending
#include<stdio.h>
/*
int main(){
	
	//For printing matrices
//	int a[100][100],i,j,rs,cs;
//	printf("Enter the rows: ");
//	scanf("%d",&rs);
//	printf("Enter the columns : ");
//	scanf("%d",&cs);
//	printf("Enter the elements: ");
//	for(i=0;i<rs;i++){
//		for(j=0;j<cs;j++){
//			scanf("%d \n",&a[i][j]);
//		}
//	}
//	printf("The Matrix is: ");
//	for(i=0;i<rs;i++){
//		for(j=0;j<cs;j++){
//			printf("%d ",a[i][j]);
//		}
//		printf("\n");
//	}
//	return 0;
	
----------------------------------------------------------------------------------------------------------------------------------------------------------------------
*/	
// The second code for printing matrices
/*
	float a[3][3], b[3][3], c[3][3];
	int i, j;
	printf("Enter elements of 1st matrix\n");
	for(i=0; i<3; i++)
	{
	for(j=0; j<3 ;j++)
	{
	printf("Enter a%d%d: ", i, j);
	scanf("%f", &a[i][j]);
	}
	}
	// Taking input using nested for loop
	printf("Enter elements of 2nd matrix\n");
	for(i=0; i<3; i++)
	{
	for(j=0; j<3; j++)
	{
	printf("Enter b%d%d: ", i, j);
	scanf("%f", &b[i][j]);
	}
	}
	// adding corresponding elements of two arrays
	for(i=0; i<3; i++)
	{
	for(j=0; j<3; j++)
	{
	c[i][j] = a[i][j] + b[i][j];
	}
	}
	// Displaying the sum
	printf("\nSum Of Matrix:\n");
	
	for(i=0; i<3; i++)
	{
	for(j=0; j<3; j++)
	{
	printf("%.1f\t", c[i][j]);
	}
	printf("\n");
	}
	return 0;
}
*/

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------

/*
//Code for multiplying of two matrices
int main(){
	int a[10][10], b[10][10], result[10][10], r1, c1, r2, c2, i, j, k;

	printf("Enter rows and column for first matrix: ");
	scanf("%d %d", &r1, &c1);
	
	printf("Enter rows and column for second matrix: ");
	scanf("%d %d",&r2, &c2);
	
	// Column of first matrix should be equal to column of second matrix and
	while (c1 != r2)
	{
	printf("Error! No. of columns of first matrix not equal to no.of row of second.\n\n");
	printf("Enter rows and column for first matrix: ");
	scanf("%d %d", &r1, &c1);
	printf("Enter rows and column for second matrix: ");
	scanf("%d %d",&r2, &c2);
	}
	
	// Storing elements of first matrix.
	printf("\nEnter elements of matrix 1:\n");
	for(i=0; i<r1; i++)
	{
	for(j=0; j<c1; j++)
	{
	printf("Enter elements a%d%d: ",i,j);
	scanf("%d", &a[i][j]);
	}
	}
	
	// Storing elements of second matrix.
	printf("\nEnter elements of matrix 2:\n");
	for(i=0; i<r2; i++)
	{
	for(j=0; j<c2; j++)
	{
	printf("Enter elements b%d%d: ",i, j);
	scanf("%d",&b[i][j]);
	}
	}
	
	// Initializing all elements of result matrix to 0
	for(i=0; i<r1; i++)
	{
	for(j=0; j<c2; j++)
	{
	result[i][j] = 0;
	}
	}
	// Multiplying matrices a and b and
	// storing result in result matrix
	
	
	for(i=0; i<r1; i++)
	{
	for(j=0; j<c2; j++)
	{
	for(k=0; k<c1; k++)
	{
	result[i][j]+=a[i][k]*b[k][j];
	}
	}
	}
	// Displaying the result
	printf("\nOutput Matrix:\n");
	for(i=0; i<r1; i++)
	{
	for(j=0; j<c2; j++)
	{
	printf("%d ", result[i][j]);
	}
	printf("\n\n");
	}
	return 0;
}
*/

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------

/*
// Write a code for printing the transpose of a matrix
int main(){
	int a[10][10], transpose[10][10], r, c, i, j;
	printf("Enter rows and columns of matrix: ");
	scanf("%d %d", &r, &c);
	
	// Storing elements of the matrix
	printf("\nEnter elements of matrix:\n");
	for(i=0; i<r; i++)
	{
	for(j=0; j<c; j++)
	{
	printf("Enter element a%d%d: ",i, j);
	scanf("%d", &a[i][j]);
	}
	}
	// Displaying the matrix a[][] 
	printf("\nEntered Matrix: \n");
	for(i=0; i<r; i++)
	{
	for(j=0; j<c; j++)
	{
	printf("%d ", a[i][j]);
	}
	printf("\n\n");
	}
	
	// Finding the transpose of matrix a
	for(i=0; i<r; i++)
	{
	for(j=0; j<c; j++)
	{
	transpose[i][j] = a[j][i];
	}
	}
	// Displaying the transpose of matrix a
	printf("\nTranspose of Matrix:\n");
	for(i=0; i<r; i++)
	{
	for(j=0; j<c; j++)
	{
	printf("%d ",transpose[i][j]);
	}
	
	printf("\n\n");
	}
	return 0;
}
*/

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------




