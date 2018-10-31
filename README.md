# Example "Hello World!" in C

This is an example of how to write C code to print out "Hello World! and how use scanf, printf, declaration variable ".
#include <stdio.h>
int main()
{
    int number;
    int p = 3 ;
    printf("Hello World!");
    printf("Enter an integer: "); 
    scanf("%d", &number);  
    printf("You entered: %d", number);
    printf("%d", p);
    return 0;
}
