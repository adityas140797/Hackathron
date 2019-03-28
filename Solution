#include <stdio.h>

int main()
{
    int i, j, k=0, l, n, a[0][0], seq[0], b, sum=0, p1, p2, q1, q2, r1, r2;

    printf("Enter the no. of rows or columns for square matrix\n");
    scanf("%d", &n);

    printf("Enter the value for matrix - row wise\n");

    for (i=0; i<n; i++) {
        for (j=0; j<n; j++) {
            scanf("%d", &a[i][j]);
        }
    }
	
    printf("Enter the limit for the sequence\n");
    scanf("%d", &n);

    printf("Enter the values for the sequence\n");
    for (i=0; i<n; i++) {
        scanf("%d", &seq[i]);
    }

    for (l=0; l<sizeof(seq); l++) {
        for (i=0; i<n; i++) {
            for (j=0; j<n; j++) {
                if (seq[k] == a[i][j]) {
	    	    p1 = i, p2 = j, k++;
		    for (i=0; i<n; i++) {
		        for (j=0; j<n; j++) {
              	            if (seq[k] == a[i][j]) {
		           	q1 =i, q2 =j;

				//Finding maximum between rows and columns and adding that into sum
				if (p1 >= q1) { r1 = p1-q1; }
				else { r1 = q1-p1; }

				if (p2 >= q2) { r2 = p2-q2; }
				else { r2 = q2-p2; }
				
				if (r1 > r2) { sum = sum + r1; }
				else { sum = sum + r2; }

                            }
		        }            	
		    }
	        }
            }
         }
    }
	
    // Print the matrix
    printf("Matrix given was\n");
    for (i=0; i<n; i++) {
        for (j=0; j<n; j++) {
            printf("%d", a[i][j]);
        }
	printf("\n");
    }
 
    // Print the sequence
    printf("Sequence given was\n");
    for (i=0; i<n; i++) {
        printf("%d", seq[i]);
	printf(", ");
    }
 
    // Print sum
    printf("Thus sum for the shortest path for the given matrix with sequence is\n");
    printf("%d", sum);	
}
