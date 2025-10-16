🧩 2048 Game (HTML, CSS, JavaScript)
🎯 Objective

This project is a browser-based implementation of the popular 2048 puzzle game.
Your goal is to combine numbered tiles by sliding them in four directions (Up, Down, Left, Right) until you reach the 2048 tile — or even higher!

🖥️ Features

🟩 4x4 game board

🎮 Keyboard controls (arrow keys)

💥 Smooth tile movement and merging

🧠 Automatic game-over and win detection

🔢 Random tile generation (2 or 4)

💯 Real-time score tracking

🧩 Responsive GUI using HTML and CSS

🛠️ Technologies Used

HTML5 – Structure and layout

CSS3 – Styling and responsive design

JavaScript (ES6) – Game logic and DOM manipulation

📦 Installation & Setup
Step 1: Clone or Download the Repository
git clone https://github.com/<shubhamlalge>/2048-game.git
cd 2048-game

Step 2: Open the Game

Simply open the index.html file in your web browser.
No additional setup or dependencies required!

🎮 How to Play

Use your keyboard arrow keys:

⬆️ Move Up

⬇️ Move Down

⬅️ Move Left

➡️ Move Right

When two tiles with the same number collide, they merge into one tile with their sum.

Your goal is to create a tile with the number 2048.

The game ends when no empty spaces or valid moves remain.

-> Implementation Details
🪟 Board Initialization

The game initializes a 4x4 grid using HTML div elements.

Two tiles (either 2 or 4) are randomly generated at the start.

🎲 Random Tile Generation

After every valid move, a new tile (2 or 4) appears in a random empty cell.

⬆️⬇️⬅️➡️ Move Logic

Each direction is handled by a function that:

Shifts non-empty tiles toward the direction.

Merges tiles if they have the same value.

Adds the merged value to the score.

-> Game Over Detection

The game checks after every move:

If no empty cells remain, and

No adjacent tiles can merge → Game Over.

-> Win Detection

When a tile reaches 2048, a “You Win” message appears.

Folder Structure
2048-game/
│
├── index.html        # Main HTML file
├── style.css         # Game styling
├── script.js         # Game logic
└── README.md         # Documentation


-> Future Enhancements

Add sound effects on merge

Add restart and undo buttons

Store high scores in localStorage


-> License

This project is open-source and free to use for educational and personal projects.
Feel free to fork, modify, and share!