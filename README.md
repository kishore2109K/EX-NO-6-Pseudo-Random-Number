# EX-NO-6-Pseudo-Random-Number

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
Start the program and import the required libraries.
Seed the random number generator using the current time(i.e) rand(time(0));
Get the number of randon number to generate.
Pass the value for number of iterations and print the numbers.
End the program.

# PROGRAM:
```
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main() {
    srand(time(NULL));

    for (int i = 0; i < 10; i++) {
        int randomNumber = rand();
        printf("Random Number %d: %d\n", i + 1, randomNumber);
    }

    printf("\nRandom Numbers between 1 and 100:\n");
    for (int i = 0; i < 10; i++) {
        int numberInRange = (rand() % 100) + 1;
        printf("Random Number %d: %d\n", i + 1, numberInRange);
    }

    return 0;
}
```
# OUTPUT:
![image](https://github.com/user-attachments/assets/96d343a6-4ffd-4824-b38f-cd6729ba3b84)

# RESULT:
Thus the implementation of Pseudorandom Number Generation Using Standard library is successfully executed.

