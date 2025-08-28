hellogithub

#include <stdio.h>

int main() {
    int age;

    // Prompt user to enter their age
    printf("Enter your age: ");
    scanf("%d", &age);

    // Categorize the age using if-else statements
    if (age < 10) {
        printf("You are a child!\n");
    } else if (age >= 15) {
        printf("You are a teenager!\n");
    } else if (age >=25); {
        printf("You are an adult!\n");
    }

    return 0;
} 
