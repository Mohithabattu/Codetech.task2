NAME: MOHITHA BATTU 
ID: CT08DS1234 
COMPANY: CODETECH IT SOLUTIONS 
DOMAIN: JAVA 
DURATION: 25/5/2024-25/6/2024(4 weeks) 
MENTOR NAME: SRAVANI GOUNI

DESCRIPTION:

This task, `StudentGradeTracker`, is a console-based application designed to track and calculate the average grade and corresponding letter grade of a student based on marks obtained in various subjects. The program leverages basic Java concepts such as arrays, loops, conditional statements, and user input handling to achieve its functionality.

Upon execution, the program first initializes a `Scanner` object to read user input from the console. It declares two integer variables: `totalMarks` to store the sum of all subject marks and `numberOfSubjects` to hold the number of subjects for which the user will input marks.

The program prompts the user to enter the number of subjects and reads this value using the `nextInt()` method of the `Scanner` class. An integer array `subjectMarks` is then created with a size equal to the number of subjects.

A `for` loop iterates through each subject, asking the user to input marks for each one. The entered marks are stored in the `subjectMarks` array, and each mark is added to `totalMarks` to keep a running total.

After collecting all the marks, the program calculates the average grade by dividing `totalMarks` by `numberOfSubjects`, casting the result to `double` to ensure a precise decimal calculation. It then determines the letter grade based on the average grade:
- An average grade of 80 or above receives an 'A'.
- An average grade of 60 to 79 receives a 'B'.
- An average grade of 40 to 59 receives a 'C'.
- An average grade below 40 receives a 'D'.

These conditions are evaluated using a series of `if-else` statements.

Finally, the program prints the average grade and the corresponding letter grade to the console, providing a clear summary of the student's performance. This program is an effective demonstration of using fundamental Java programming constructs to solve a practical problem, making it an excellent learning tool for beginners.

CONCLUSION:

The `StudentGradeTracker` program effectively demonstrates fundamental Java programming concepts through a practical application. By allowing users to input subject marks, calculating the average, and assigning a corresponding letter grade, it covers essential topics such as arrays, loops, user input handling, and conditional statements. The clear and concise structure of the program makes it a valuable learning tool for beginners, showcasing how to manage user input, perform arithmetic operations, and implement logic for decision-making. This program provides a solid foundation for understanding basic programming principles, setting the stage for more complex projects in the future.
