# Quiz-Game.c

#include <stdio.h>

int main() {
    int choice;
    int ans1, ans2, ans3, ans4, ans5;
    int points = 0;

    printf("Welcome to the Game\n\n");
    printf("> Press 7 to start the game\n");
    printf("> Press 0 to quit the game\n");
    scanf("%d", &choice);

    if (choice == 7) {
        printf("The game has started\n\n");

        // Question 1
        printf("1) Which one is the first search engine in internet?\n\n");
        printf("1) Google\n");
        printf("2) Archie\n");
        printf("3) Wais\n");
        printf("4) Altavista\n");
        printf("Enter your Answer : ");
        scanf("%d", &ans1);
        if (ans1 == 2) {
            printf("Correct Answer\n");
            points += 5;
        } else {
            printf("Wrong Answer\n");
        }
        printf("You have scored %d points\n", points);

        // Question 2
        printf("2) Which one is the first web browser invented in 1990?\n\n");
        printf("1) Internet Explorer\n");
        printf("2) Mosaic\n");
        printf("3) Mozilla\n");
        printf("4) WorldWideWeb\n");
        printf("Enter your Answer: ");
        scanf("%d", &ans2);
        if (ans2 == 4) {
            printf("Correct Answer\n");
            points += 5;
        } else {
            printf("Wrong Answer\n");
        }
        printf("You have scored %d points\n", points);

        // Question 3
        printf("3) First computer virus is known as?\n\n");
        printf("1) Rabbit\n");
        printf("2) Creeper\n");
        printf("3) Elk Cloner\n");
        printf("4) SCA Virus\n");
        printf("Enter your Answer: \n");
        scanf("%d", &ans3);
        if (ans3 == 2) {
            printf("Correct Answer\n");
            points += 5;
        } else {
            printf("Wrong Answer\n");
        }
        printf("You have scored %d points\n", points);

        // Question 4
        printf("4) Firewall in computer is used for?\n\n");
        printf("1) Security\n");
        printf("2) Data transmission\n");
        printf("3) Monitoring\n");
        printf("4) Authentication\n");
        printf("Enter your Answer: \n");
        scanf("%d", &ans4);
        if (ans4 == 1) {
            printf("Correct Answer\n");
            points += 5;
        } else {
            printf("Wrong Answer\n");
        }
        printf("You have scored %d points\n", points);

        // Question 5
        printf("5) Which of the following is not a database management software?\n\n");
        printf("1) Mysql\n");
        printf("2) Oracle\n");
        printf("3) Cobol\n");
        printf("4) Sybase\n");
        printf("Enter your Answer: \n");
        scanf("%d", &ans5);
        if (ans5 == 3) {
            printf("Correct Answer\n");
            points += 5;
        } else {
            printf("Wrong Answer\n");
        }
        printf("You have scored %d points\n", points);

        printf("Game over! Your final score is %d points\n", points);
    } else if (choice == 0) {
        printf("The game has ended\n\n");
    } else {
        printf("Invalid choice\n\n");
    }

    return 0;
}

