Java Quiz Application

A console-based Java Quiz Game built using core Object-Oriented Programming principles such as Encapsulation, Object Composition, and Collections (ArrayList).
This project demonstrates clean architecture, input validation, score tracking, and result summarization — designed specifically for mastering Java fundamentals and interview preparation.

🚀 Project Highlights

20 Multiple-choice Java questions
Instant feedback (Correct / Wrong)
Score tracking system
Final percentage calculation
Structured 3-class architecture

🏗 Project Architecture
The application is divided into three well-structured classes:

🔹 Question (Model)
Stores question text
Stores 4 answer options
Stores correct answer index
Displays question
Validates answer

🔹 Quiz (Controller)
Holds list of Question objects
Runs main game loop
Validates user input
Tracks score
Displays summary

🔹 QuizApp (Entry Point)
Contains main() method
Creates Quiz and Scanner objects
Adds questions
Starts quiz execution

🧠 Core Concepts Demonstrated

✔ Encapsulation
✔ Object Composition (HAS-A Relationship)
✔ Java Collections (ArrayList with Generics)
✔ Input Validation using while(true) loop
✔ Type Casting for accurate percentage calculation
✔ Clean Console Output formatting

📊 Score Calculation Logic
double percentage = ((double) score / totalQuestions) * 100;
Casting prevents integer division errors and ensures accurate decimal results.

💻 How to use
1️⃣ Compile= QuizApp.java
2️⃣ Run= QuizApp

🔮 Future Enhancements
Shuffle question order using Collections.shuffle()
Add timer functionality
Add difficulty levels
Store high scores










