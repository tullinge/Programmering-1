# Create-a-Quiz

## Requirements
This is the list of features your quiz needs to have:

1. Create your own quiz with five or more questions. You can ask questions that require:
   * a number as an answer (e.g., What is 1+1?)
   * text (e.g. What is Harry Potter's last name?)
   * a selection (Which of these choices are correct? A, B, or C)

2. If you have the user enter non-numeric answers, think and cover the different ways a user could enter a correct answer. For example, if the answer is “a”, would “A” also be acceptable? See Section 3.6 for a reminder on how to do this.

3. Let the user know if he or she gets the question correct. Print a message depending on the user's answer.

4. You need to keep track of how many questions they get correct.

5. At the end of the program print the percentage of questions the user gets right.

## Keep in mind
Keep the following in mind when creating the program:

* Variable names should start with a lower case letter. Upper case letters work, but it is not considered proper

* To create a running total of the number correct, create a variable to store this score. Set it to zero. With an if statement, add one to the variable each time the user gets a correct answer

* Calculate the percentage by using a formula at the end of the game

* To print a blank line so that all the questions don't run into each other, use the following code: `print()`
  
* Remember the program can print multiple items on one line. This can be useful when printing the user's score at the end.
`print("The value in x is", x)`

* Separate out your code by using blank lines to group sections together. For example, put a blank line between the code for each question.

* Sometimes it makes sense to re-use variables. Rather than having a different variable to hold the user's answer for each question, you could reuse the same one.

* Use descriptive variable names. x is a terrible variable name. Instead use something like number_correct.
