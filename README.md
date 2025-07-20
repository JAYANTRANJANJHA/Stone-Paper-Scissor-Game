# Rock Paper Scissors Game ✂️📜🗿

A classic Rock, Paper, Scissors game built with fundamental web technologies: HTML, CSS, and vanilla JavaScript. This project is a simple, interactive web-based game where a user can play against the computer.

*(Feel free to replace this placeholder image with a screenshot or GIF of your game)*

-----

## ✨ Features

  * **Player vs. Computer**: Test your luck and strategy against a computer opponent.
  * **Interactive UI**: A clean, simple, and responsive user interface with hover effects on choices.
  * **Score Tracking**: The game keeps track of both the user's and the computer's score.
  * **Instant Feedback**: The display message immediately updates to show the result of each round (win, lose, or draw) with distinct colors.

-----

## 💻 Technologies Used

  * **HTML5**: For the structure and content of the game.
  * **CSS3**: For styling the game, including layout, colors, and responsive design.
  * **JavaScript**: For the core game logic, handling user events, generating the computer's choice, and updating the DOM.

-----

## 🚀 How to Run Locally

To get a local copy up and running, follow these simple steps.

1.  **Clone the repository:**
    ```sh
    git clone https://github.com/JAYANTRANJANJHA/Rock-Paper-Scissor-Game.git
    ```
2.  **Navigate to the project directory:**
    ```sh
    cd Rock-Paper-Scissor-Game
    ```
3.  **Open the `index.html` file in your web browser.**

That's it\! You can now play the game.

-----

## 🎮 How to Play

1.  Open the `index.html` file in your browser.
2.  Click on one of the three choices: **Rock**, **Paper**, or **Scissors**.
3.  The computer will make its choice randomly.
4.  The message at the bottom will declare the winner of the round, and the scores will be updated accordingly.
5.  Play as many rounds as you like\!

-----

## 📂 File Structure

The repository is structured as follows:

```
├── images/
│   ├── rock.png
│   ├── paper.png
│   └── scissor.png
├── index.html      # The main HTML file with the game structure
├── style.css       # CSS file for all the styling
└── app.js          # JavaScript file with all the game logic
```

### Code Overview

  * **`app.js`**: This file contains all the client-side logic for the game.
      * It selects DOM elements to manipulate the score and messages.
      * `genCompChoice()`: Randomly returns "rock", "paper", or "scissors" for the computer's turn.
      * `playGame(userChoice)`: This is the main function that compares the user's choice with the computer's choice to determine the winner.
      * `showWinner()` and `drawGame()`: These functions handle the UI updates, changing messages, scores, and background colors based on the outcome.
      * An event listener is added to each choice `div` to trigger the `playGame` function on click.
