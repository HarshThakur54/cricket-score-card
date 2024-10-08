Cricket Score Card
Project Overview
This project is a Cricket Score Sheet application written in the C programming language as part of a mini-project for the course 21CSS101J - Programming for Problem-Solving. It utilizes file management to store and display cricket score details, such as runs, wickets, overs, and player statistics.

Features
Create a New Score Sheet: The program allows users to input match details such as player names, runs, wickets, and more, then saves this information to a file.
View Previous Score Sheets: Users can load existing score sheets from files to view past match results.
Match Summary: Displays the complete statistics of the game, including the total runs, wickets, strike rates, and economy rates.
Exit: Provides an option to exit the application.
Key Concepts
File Handling: Saves and retrieves match data from files.
Structures: Uses structures to manage batsman and bowler details.
User Interaction: Provides a simple menu-driven interface for easy navigation.
Files
cricket_scorecard.c: The source code for the Cricket Score Card application written in C.
README.md: This README file explaining the project.
sample_scorecard.txt: Example scorecard file generated by the program (if applicable).
How to Run
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/cricket-score-card.git
cd cricket-score-card
Compile the C program:

bash
Copy code
gcc cricket_scorecard.c -o cricket_scorecard
Run the executable:

bash
Copy code
./cricket_scorecard
Project Structure
bash
Copy code
├── cricket_scorecard.c   # Source code
├── README.md            # Project documentation
└── sample_scorecard.txt # Example scorecard file (optional)
Sample Input
mathematica
Copy code
Enter the number of batsmen: 4
Enter name of batsman1: Rohit
Enter the runs scored by Rohit: 45
Enter name of bowler1: Bumrah
Enter the wickets taken by Bumrah: 3
Future Enhancements
Graphical User Interface (GUI): To enhance user interaction.
Multiple Matches: Support for handling multiple matches in a single session.
Live Match Updates: Real-time score updates during a match.
References
Cricket Score Sheet in C - Javatpoint
Free C Programming Books
