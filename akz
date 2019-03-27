/* Bubble sort code */
 
#include<stdio.h>
#include<stdlib.h>
 
int main() {
    int array[100], n, c, d, swap;
 
    printf("Enter number of elements\n");
    scanf("%d", &n);
 
    printf("Enter %d integers\n", n);
 
    for (c = 0; c < n; c++) //the numbers are supplied in any order
        scanf("%d", &array);
 
    for (c = 0; c < (n - 1); c++) { //outer loop starts
        for (d = 0; d < n - c - 1; d++) {
            if (array[d] > array[d + 1]) { // For decreasing order use <
                swap = array[d]; //swap using tempoprary variable
                array[d] = array[d + 1];
                array[d + 1] = swap;
            }
        }
    }
 
    printf("Sorted list in ascending order:\n");
 
    for (c = 0; c < n; c++)
        printf("%d\n", array); //printing the sorted array
 
    return 0;
}
