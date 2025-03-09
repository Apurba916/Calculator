#include <stdio.h>

float calculation(float, float);

float calculation(float a, float b){
    int operation;
    printf("Enter the operation you want to perform:\n(Note: 1 is for '+', 2 is for '-', 3 is for '*' and 4 is for '/')");
    scanf("%d", &operation);

    if (operation == 1)
    {
        return a + b;
    }
    else if (operation == 2)
    {
        return a - b;
    }
    else if (operation == 3)
    {
        return a *b;
    }
    else if (operation == 4)
    {
        if (b == 0)
        {
            printf("Invalid number input.");
            return 0;
        }
        else
        {
            return a/b;
        }
    }
    else
    {
        printf("Invalid!");
        return 0;
    }
}

int main(){
    float a;
    float b;
    printf("Enter the first number:\n");
    scanf("%f", &a);
    printf("Enter the second number:\n");
    scanf("%f", &b);

    float c = calculation(a,b);
    printf("The answer is %.2f\n", c);

    return 0;
}
