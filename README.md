# Array-of-Marks-of-subjects-
Array of 5 subjects marks, Sum of marks obtained and average marks of all 5 subjects.
#include <stdio.h>

int main() {
    
    int sub[5] = { 70, 46,82,67,82};
    printf("The array form is: ");
    printf(" %d", sub[0]);
    printf(" %d", sub[1]);
    printf(" %d", sub[2]);
    printf(" %d", sub[3]);
    printf(" %d", sub[4]);
    
    float sum = sub[0] + sub[1] + sub[2] + sub[3] + sub[4] ;
    printf("\nSum of the marks of all 5 subjects: %0.2f", sum);
  
    float pop = (sum / 5);
    printf("\nAverage marks of all 5 subjects: %0.2f", pop);
   

    return 0;
}
