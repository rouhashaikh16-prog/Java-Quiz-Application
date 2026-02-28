Java Quiz Application

A console-based Java Quiz Game built using core Object-Oriented Programming principles such as Encapsulation, Object Composition, and Collections (ArrayList).
This project demonstrates clean architecture, input validation, score tracking, and result summarization — designed specifically for mastering Java fundamentals and interview preparation.

-  Project Highlights

This project is a console-based Java Quiz Application that allows users to attempt 20 multiple-choice questions in a simple and interactive way. It shows one question at a time, takes the user’s answer as input, and checks whether the answer is correct or not. At the end of the quiz, it automatically calculates the total score and displays a result summary along with the percentage. The project is built using basic Java and OOP concepts, and it is simple, easy to understand, and beginner friendly.

-  Project Architecture

The Java Quiz Application is designed as a simple console-based program where the user answers multiple-choice questions one by one. When the program starts, it loads all the questions and displays them to the user in sequence. The user selects an option, and the system checks whether the answer is correct and updates the score accordingly. In this project, I have used core Java and OOP concepts like Encapsulation to organize question data properly and Object Composition to manage quiz and question details together. I have also used ArrayList to store multiple questions dynamically. Loops are used to display questions one by one, and conditional statements are used to check correct and wrong answers. Scanner is used to take input from the user. After all questions are completed, the system calculates the total score and percentage and then displays a final result summary. The overall structure of the program is simple, organized, and easy to understand.

-  Core Concepts Demonstrated

In this project, I have demonstrated important core Java and Object-Oriented Programming concepts in a practical way. Encapsulation is used to organize question data properly and keep it structured. Object composition is applied to manage quiz details and questions together in a clean manner. I have used ArrayList from the Collection Framework to store multiple questions dynamically, which makes the system flexible and easy to manage. Loops are used to display each question one by one, and conditional statements are used to check whether the selected answer is correct or not. Scanner is used to take input from the user through the console. Overall, this project shows how basic programming concepts can be combined to build a complete and working application in a simple and understandable way.

-  Score Calculation Logic

In this project, the score is calculated based on the number of correct answers given by the user. Every time the user selects the correct option for a question, the score increases by one. If the answer is wrong, the score does not increase. After all the questions are completed, the system calculates the total score and then finds the percentage based on the total number of questions.
                                            double percentage = ((double) score / totalQuestions) * 100;

-  How to use
1️.  Compile= QuizApp.java
2️.  Run= QuizApp

-  Future Enhancements
Shuffle question order using Collections.shuffle()
Add timer functionality
Add difficulty levels
Store high scores










