# calculator-
#include <stdio.h>

int main()
{
    int num1, num2, sum, mul;
    
    printf("Enter first number: ");
    scanf("%d", &num1);
    
    printf("Enter second number: ");
    scanf("%d", &num2);
    
    sum = num1 + num2;
    mul = num1 * num2;
    printf("Sum of entered numbers is %d\n", sum);
    printf("Multiply of entered numbers is %d\n", mul);
    
    return 0;
}
