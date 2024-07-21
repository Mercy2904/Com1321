# Com1321
Assignment

```
import java.util.Scanner;

public class StudentAchievement {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.print("Enter student marks (0-100): ");
        int marks = scanner.nextInt();

        if (marks >= 90) {
            System.out.println("Level 8 - Exceptional Achievement");
        } else if (marks >= 80) {
            System.out.println("Level 7 - Outstanding Achievement");
        } else if (marks >= 70) {
            System.out.println("Level 6 - Meritorious Achievement");
        } else if (marks >= 60) {
            System.out.println("Level 5 - Commendable Achievement");
        } else if (marks >= 50) {
            System.out.println("Level 4 - Satisfactory Achievement");
        } else if (marks >= 40) {
            System.out.println("Level 3 - Needs Improvement");
        } else {
            System.out.println("Level 2 - Unsatisfactory Achievement");
        }

        scanner.close();
    }
}
```

This program prompts the teacher to enter the student's marks, then uses nested if-else statements to determine the level of achievement based on the marks. The levels of achievement are:

- 80-100: Level 7 - Outstanding Achievement
- 70-79: Level 6 - Meritorious Achievement
- 60-69: Level 5 - Substantial archivement 
- 50-59: Level 4 - Adequate Achievement
- 40-49: Level 3 - moderate Improvement
- 30-39: Level 2 - elementary Achievement
- 1-30:  Level 1- not archived 
