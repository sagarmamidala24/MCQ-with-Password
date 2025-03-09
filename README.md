# MCQ-with-Password

This Python program is an interactive exam simulator with the following structure and logic:

### Prompt for Username and Password:

The program begins by asking the user to input their username and password.

### Password Verification:

If the entered password is "p4n@in," the user is allowed to start the exam.

If the password is incorrect, the user is given two more attempts to enter the correct password. After three failed attempts, the user is informed that they have lost their chances and must try later.

### Exam Questions:

If the correct password is entered, the user is presented with the first exam question: "Who invented Java Programming?" with four multiple-choice answers.

The user inputs their answer.

If the answer is "James Gosling," the user proceeds to the second question: "Which component is used to compile, debug, and execute Java programs?" with four multiple-choice answers.

If the answer is incorrect, the user is prompted to try again next year.

### Second Question:

For the second question, if the user answers "JIT," they are congratulated for passing the exam.

If the answer is incorrect, the user is prompted to try again next year.

### Incorrect Password Handling:

If the initial password entered is incorrect, the user is given two more chances to enter the correct password.

Each time the password is entered incorrectly, the user is informed of the number of attempts remaining.

If the correct password is entered within the allowed attempts, the user is presented with the same set of exam questions.

If the password remains incorrect after three attempts, the user is informed that they have lost their chances and must try later.

### Additional Details:
The program uses input() to take input from the user for the username, password, and answers to the exam questions.

The print() function is used to display messages and questions to the user.

Conditional execution is managed using if-elif-else statements to check the password and validate the answers provided by the user.

The flow of the program ensures that only users with the correct password can attempt the exam, and they must answer both questions correctly to pass.
