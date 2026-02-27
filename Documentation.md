Java Quiz Application – Documentation
1️⃣ Project Overview

The Java Quiz Application is a console-based quiz system built using core Object-Oriented Programming principles.
It presents multiple-choice questions, validates user input, checks correctness, tracks score, and generates a final result summary with percentage.

The application is structured using three classes:
Question
Quiz
QuizApp

This separation ensures clean architecture and follows good software design practices.

2️⃣ Project Architecture
🔹 Question Class (Model Layer)

Responsible for:
Storing question text
Storing 4 answer options
Storing correct answer index
Displaying the question
Checking if the user’s answer is correct
Encapsulation is applied by keeping all fields private and exposing only public methods.

🔹 Quiz Class (Controller Layer)

Responsible for:
Storing all Question objects using ArrayList
Running the quiz loop
Handling input validation
Tracking score
Generating result summary
Uses Object Composition:
Quiz HAS-A List of Question objects

🔹 QuizApp Class (Entry Point)

Responsible for:
Creating Quiz object
Creating Scanner object
Creating and adding all Question objects
Starting the quiz using quiz.start(scanner)
Contains public static void main() method.

3️⃣ Core Concepts Used
✅ Encapsulation
All fields in Question class are private
Access controlled via public methods
Protects data integrity

✅ Object Composition
Quiz contains multiple Question objects
Demonstrates HAS-A relationship

✅ ArrayList & Generics
List<Question> questions = new ArrayList<>();
Used for dynamic storage of questions.

✅ Input Validation
Implemented using:
while(true)
Loop continues until user enters valid option (A, B, C, D).

✅ Type Casting
Used for accurate percentage calculation:
(double) score / totalQuestions * 100
Prevents integer division errors.

4️⃣ Program Flow

main() method runs
Quiz object created
Question objects added
Each question displayed
User enters answer
Answer validated
Score updated
Final summary displayed
Scanner closed

5️⃣ Result Summary Logic

Score stored as integer
Boolean array tracks correct/wrong answers
Percentage calculated using double casting
Performance rating can be displayed if implemented

6️⃣ Future Scope/Enhancement

Load questions from file (JSON / TXT)
Shuffle questions using Collections.shuffle()
Add timer per question
Add difficulty levels
Store high scores in file
