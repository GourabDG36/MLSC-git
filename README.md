🧠 IQ Test Quiz Game (C Program)

📌 Overview

This is a console-based General Knowledge Quiz Game written in C. It asks the player multiple-choice questions, calculates their score based on correct answers and time taken, and keeps track of the highest score.

✅ Features

✔ Interactive Menu Options
✔ Random Question Selection (from a set of 23 questions)
✔ Scoring Based on Accuracy and Speed
✔ High Score Tracking using score.txt
✔ Replay Option after finishing the quiz

🖥️ How It Works

Displays the main menu with options:

S → Start the Game

V → View High Score

H → Help

Q → Quit

When the game starts:

Player enters their name.

The game selects 5 random questions (no repeats).

Each question has 4 options (A, B, C, D).

After answering all questions:

Score is calculated using:

score = (correct_answers / total_questions) * 100 - (time_taken / 3)


Negative scores reset to 0.

If you beat the previous high score, your name and score are saved in score.txt.

📂 Files in the Project

quiz.c → Main source code.

score.txt → Stores the highest score and player name.

📸 Example Output
WELCOME TO I.Q. TEST PROGRAM

Enter 'S' to start game
Enter 'V' to view high score
Enter 'H' for help
Enter 'Q' to quit

Your Score: 80.67
VERY GOOD!!
NEXT PLAY?(Y/N)

⚙️ How to Run

Compile the program using GCC or any C compiler:

gcc quiz.c -o quiz


Run the program:

./quiz


Ensure score.txt exists in the same directory:

echo "PlayerName 0" > score.txt

✅ Requirements

OS: Windows (uses <windows.h> and <conio.h>).

Compiler: GCC or any standard C compiler.

📖 How Scoring Works

Total questions per game: 5

Faster answers → Higher score

Highest score is stored in score.txt

🚀 Future Enhancements

Add more questions dynamically.

Make it cross-platform (replace Windows-specific functions).

Add colorful UI for better experience.

Add per-question timer.

👨‍💻 Author

Gourabdipta Ghosh
📌 Feel free to contribute or fork this repository!
