# Flashcard-Quizzer
# Overview
This project is an interactive, command-line Flashcard Quiz System developed in Python. Its primary function is to facilitate effective self-testing by using a customizable set of flashcards. The system is designed to track user progress across multiple sessions, randomly select questions to ensure comprehensive review, and generate performance reports.
The project was created to enhance skills in data persistence, randomized logic, and structured programming within the Python environment.
# Features
Randomized Quizzing:
- What it Does: Selects flashcards in a completely random order during each session.
- Why it's Useful: Prevents memorization based on order and ensures you genuinely know the material across the entire deck.
Progress Persistence:
- What it Does: Saves the accuracy data for every single flashcard across all study sessions.
- Why it's Useful: Allows for accurate, long-term performance tracking, enabling targeted study sessions on weaker topics.
Performance Reports:
- What it Does: Generates a comprehensive summary of scores and highlights the most difficult cards immediately after a session.
- Why it's Useful: Instantly shows you which topics require the most urgent review time, optimizing your study plan.
Easy Deck Customization:
- What it Does: Flashcard questions and answers are loaded from a simple, external data file (e.g., JSON or TXT).
- Why it's Useful: Allows for quick and effortless modification, expansion, or removal of the deck contents without ever needing to touch the core Python code.
# How to Run
To get the Flashcard Quizzer running on your local machine:
1. Set Up Environment: Ensure that Python 3.x is installed on your system.
2. Clone the Repository: Open your terminal and download the project files from GitHub:
   git clone https://github.com/fenetdiriba/Flashcard-Quizzer.git
cd Flashcard-Quizzer
3. Execute the Program: Run the main Python script from your terminal. (Use the actual filename of your main script if it's different from the example below):
   python flashcard_quizzer.py
# Example Usage Flow
The program provides a simple, interactive workflow designed for continuous learning:
1. Load Session: The system loads your flashcard deck and retrieves your previously saved performance data.
2. Quiz Loop: A random question is presented. You type your answer into the command line.
3. Feedback & Update: The system provides immediate feedback (correct or incorrect) and saves the updated score for that specific card to the data file.
4. End Session & Report: Once the quiz is complete, the program generates a summary report showing your overall accuracy for the session and highlighting the cards that need further review.
# Conclusion
The Flashcard Quizzer System is an efficient, practical tool for self-directed learning. Its core value lies in its ability to enforce randomized recall and provide data-driven feedback through progress persistence. This project demonstrates proficiency in using Python for command-line application development and file handling for data management.
