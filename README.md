# project-7
Simple Quiz Game
#include <stdio.h>

int main() {
    int score = 0, ans;

    printf("1) Capital of India?\n1.Delhi 2.Mumbai\nYour answer: ");
    scanf("%d", &ans);
    if (ans == 1) score++;

    printf("2) 5 + 3 = ?\n1.7 2.8\nYour answer: ");
    scanf("%d", &ans);
    if (ans == 2) score++;

    printf("\nFinal Score: %d/2\n", score);
    return 0;
}
