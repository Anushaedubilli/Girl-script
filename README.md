Dot and Boxes Game
Dot and Boxes is a classic pen-and-paper game where two players take turns connecting dots to form lines. When a player completes a box by forming the fourth side, they score a point and get another turn. The player with the most boxes at the end of the game wins.

🖥️ Game Overview

The game has been implemented using Python and Pygame. It supports both two-player mode and single-player mode against a basic AI.

✨ Features

Grid-based Gameplay: The game consists of a grid where players take turns to draw lines between dots.
Two Players: The game supports two players - either two human players taking turns or one human player against an AI.
Turn-based System: The game alternates turns between the players unless a player completes a box, in which case they get an extra turn.
Score Tracking: Keep track of each player's score throughout the game.
Single-player Mode: Play against a basic AI that makes random moves.

🎮 Instructions for Playing
Player 1 is represented by 'X' (Blue) and Player 2 (or AI) is represented by 'O' (Green).
Controls:
 Use the mouse to draw lines by clicking near the sides of the boxes.
Restart Game: Press the 'R' key to restart the game.
Quit Game: Press 'Q' or the 'Escape' key to quit the game.

Steps to Play
Drawing Lines:
Click near the top, right, bottom, or left side of a cell to draw the corresponding line.
Completing Boxes:
When you complete a box, it will be filled with your color (Blue for 'X', Green for 'O'), and you will get an additional turn.
AI Moves:
If playing in single-player mode, the AI will automatically make its move after your turn.
Winning the Game:
The game ends when all boxes are completed. The player with the most boxes wins.
💻 Installation
To play the game locally, follow these steps:

Clone the repository to your local machine:

git clone https://github.com/your_username/dot_and_boxes.git
Navigate to the project directory:

cd dot_and_boxes
Install dependencies/requirements:

pip install -r requirements.txt
Or, if there is no requirements.txt file:
pip install pygame
Run the Game:
python main.py
This will launch the game!

🤝 How to Contribute
If you think that you can add a new feature or want to fix a bug, we invite you to contribute to the Dot and Boxes project and make it better. To start contributing, follow the steps below:

Fork the repository.

Clone your forked repository:

git clone https://github.com/your_username/dot_and_boxes.git

Navigate to the project directory:

cd dot_and_boxes

Add a reference (remote) to the original repository:

git remote add upstream https://github.com/original_author/dot_and_boxes.git

Always take a pull from the upstream repository to keep your main branch updated:

git pull upstream main

Create a new branch for your feature or bugfix:

git checkout -b feature_or_bugfix_branch

Make your changes.

Stage your changes:
git add .

Commit your changes:

git commit -m "Description of the feature or bugfix"

Push your changes to your remote repository:

git push origin feature_or_bugfix_branch

Create a pull request by comparing changes across forks.

Congratulations! You've made a contribution to the Dot and Boxes project.

📜 Credits

This project is based on the classic Dot and Boxes game.

Developed using Python and Pygame.

📄 License

This project is licensed under the MIT License.

