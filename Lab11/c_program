#include <stdio.h>

int main() {
    int num, sum = 0;
    char choice;

    printf("Welcome to the Sum Calculator!\n");

    do {
        // Prompt the user for input
        printf("Enter an integer: ");
        scanf("%d", &num);

        // Add the number to the sum
        sum += num;

        // Ask if the user wants to enter another number
        printf("Do you want to enter another number? (y/n): ");
        scanf(" %c", &choice);  // Space before %c to consume any leftover newline character

    } while (choice == 'y' || choice == 'Y');

    // Output the total sum
    printf("The total sum is: %d\n", sum);

    return 0;
}
