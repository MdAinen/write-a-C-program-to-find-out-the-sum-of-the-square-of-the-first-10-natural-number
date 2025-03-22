#include <stdio.h>
#include <math.h>
 
int main() { 
    int sum = 0; 
    int n = 10; 
    for (int i = 1; i <= n; i++) { 
        sum += i * i; // Add the square of each number to sum 
    } 
    printf("The sum of squares of the first %d natural numbers is: %d\n", n, sum); 
    return 0; 
} 
