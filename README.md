#define _CRT_SECURE_NO_WARNINGS
#include <stdio.h>

int main() {
    int total = 0;
    int gradecounter = 1;
    int grade;
    float average;  // Corrected spelling from 'avarage' to 'average'

    while (gradecounter <= 10) {
        printf("Enter grade %d: ", gradecounter);  // Added gradecounter in prompt
        scanf("%d", &grade);  // Fixed scanf syntax (removed comma, fixed variable name)
        total = total + grade;  // Added missing semicolon
        gradecounter = gradecounter + 1;
    }

    average = total / 10.0; // Division by 10 (10.0 for floating-point result)
    printf("Class average is %.2f\n", average); // Print average

    return 0;
}
⬇
