# Rock Paper Scissors Game

This is a simple Rock Paper Scissors game built using HTML, CSS, and JavaScript. The game allows the user to select Rock, Paper, or Scissors, and plays against the computer, displaying the results and keeping track of the score.

## Key Features

- User can choose between Rock, Paper, or Scissors.
- The computer randomly selects its choice.
- The game determines if the player wins, loses, or draws based on the selected choices.
- The player's score is updated after each round.
- There is an "End Game" button to reset the game.

## How It Works

1. The user clicks one of the Rock, Paper, or Scissors buttons.
2. The computer randomly picks a choice.
3. The result (win, lose, draw) is displayed on the screen along with both the player's and computer's choices.
4. The score is updated after each round.
5. The user can click the "End Game" button to reset the game and scores.

## Game Logic

- **getComputerChoice()**: Randomly selects one of `Rock`, `Paper`, or `Scissors` for the computer.
- **getResult(playerChoice, computerChoice)**: Compares the player's choice with the computer's choice to determine the winner and returns the score:
  - `1` if the player wins.
  - `0` if it's a tie.
  - `-1` if the player loses.
- **showResult(score, playerChoice, computerChoice)**: Updates the DOM with the result of the round, showing whether the player wins, loses, or draws.
- **onClickRPS(playerChoice)**: Handles the player's selection, determines the result, and updates the score.
- **endGame()**: Resets the game and score.

## Project Structure

src/ │ ├── index.html ├── style.css └── script.js


### index.html

This is the main HTML file that contains the structure of the game, including the buttons for Rock, Paper, and Scissors, as well as the result display area and the end game button.

### style.css

This file contains the CSS to style the buttons, layout, and overall appearance of the game.

### script.js

This file contains the JavaScript code that handles the game logic and interactions, such as determining the winner, updating the score, and resetting the game.

## Running the Game

1. Clone or download the repository.
2. Open `index.html` in a web browser to start playing the game.
3. Choose between Rock, Paper, or Scissors to play against the computer.
4. Click the "End Game" button to reset the scores.

## Conclusion

This project demonstrates how to use basic JavaScript concepts like functions, conditionals, and DOM manipulation to build an interactive game. It also covers how to handle user input and update the UI accordingly.
