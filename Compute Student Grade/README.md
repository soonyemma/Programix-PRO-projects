Suppose you are a teaching assistant in a University, and you need to assign grades to students based on their average scores.
Your job is to first compute the average score first. And, based on the average score, you need to compute a student's grade.

The grading rule is like this:

Grade A if the average score is equal to or above 80
Grade B if the average score is equal to or above 60 and less than 80
Grade C if the average score is equal to or above 50 and less than 60
Grade F if the average score is less than 50

Thought Process
The project has two distinct tasks:

calculating average marks
calculating grade
To accomplish these tasks, we will create functions.

1. The getAverageScore() function

This function will take an array as the argument, compute the average score, and return it.

2. The computeGrade() function

This function will take the average score as an argument, compute the grade and return it.

* We used a for loop and scanf to get input scores and based on the input find the average score and grade.
