# 2048 Game

## A brief description of the project

This project is an implementation of the popular 2048 puzzle game. The objective of the game is to slide numbered tiles on a grid to combine them and create a tile with the number 2048. This game is built using JavaScript and provides an interactive and engaging user experience.

Link to the preview:  [DEMO LINK](https://alenalenk.github.io/game-2048/)

## How to play 
The game field is 4 x 4.
Each cell can be empty or contain one of the numbers: 2, 4, 8 ... 2^n.
The player can move cells with keyboard arrows.
All the numbers should be moved in the selected direction until all empty cells are filled in
2 equal cells can merged into a doubled number.
The move is possible if at least one cell is changed after the move.
After move 2 or 4 appears in a random empty cell. 4 probability is 10%.
When 2048 value is displayed in any cell, win message will be shown.
The game over message will be shown if there are no more available moves.
When game starts start message will be hide and  the Start button will change to Restart. Restart button can reset the game to the initial state.
The score will be increased by the sum of all merged cells with each move .

## Technologies that were used

- **JavaScript**: The core logic and functionality of the game are implemented in JavaScript.

## Any additional launch instructions

To launch the project locally, follow these steps:

1. **Clone the repository**:<br>
   git clone https://github.com/Alenalenk/game-2048.git<br>
   cd game-2048<br>
   
2. **Install the dependencies**:<br>
  If you are using NPM: npm install<br>
  If you are using Yarn: yarn install<br>

4. **Start the development server**: <br>
  If you are using NPM: npm start<br>
  If you are using Yarn: yarn start<br>

Open your browser.
You should now see the 2048 game running in your browser.
