# Demonstrate-Explicit-Type-Casting
#include <stdio.h>

int main() {
    float num = 9.75;
    int intNum = (int)num;  // explicit type casting
    printf("Original Number: %.2f\n", num);
    printf("After Casting to Integer: %d\n", intNum);
    return 0;
}
