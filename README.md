# -Stone-Paper-Scissors-Game-JavaScript
The "Rock Paper Scissors" game is a simple web-based project that allows users to play the classic game against the computer. This project involves creating a user interface using HTML and CSS and implementing game logic using JavaScript. Here’s a detailed description of each component of the project:

Project Description
Objective:
The objective of this project is to create a web application that allows users to play the Rock Paper Scissors game against a computer opponent. The game keeps track of scores and displays the result of each round.

Components:

HTML (index.html):

Structure: The HTML file provides the structure of the game interface. It includes headings, divs for choices (rock, paper, scissors), and elements to display scores and messages.
Elements:
div elements for each choice (rock, paper, scissors), each containing an image.
div elements for the score-board, showing the user and computer scores.
A message container to display the result of each round.
CSS (style.css):

Styling: The CSS file is used to style the game interface. This includes positioning the choices, styling the score-board, and making the game visually appealing.
Responsive Design: The CSS ensures that the game interface is responsive and looks good on different screen sizes.
JavaScript (app.js):

Game Logic: The JavaScript file contains the logic for the game. It handles user interactions, determines the computer’s choice, compares the choices to determine the winner, updates the scores, and displays the result.
Event Handling: The JavaScript code adds event listeners to the choice elements, so that when a user clicks on a choice, the game logic is executed.
Random Choice: The computer's choice is generated randomly from the available choices (rock, paper, scissors).
Result Calculation: The JavaScript code compares the user's choice with the computer's choice to determine the result (win, lose, draw) and updates the scores accordingly.
How It Works:
User Interface:

The user is presented with three clickable images representing rock, paper, and scissors.
Scores for both the user and the computer are displayed on the screen.
A message area displays the result of each round.
Game Play:

The user clicks on one of the three choices.
The JavaScript code captures the user’s choice and generates a random choice for the computer.
The choices are compared to determine the result based on the rules of Rock Paper Scissors:
Rock beats Scissors
Scissors beats Paper
Paper beats Rock
The scores are updated based on the result, and a message is displayed indicating whether the user won, lost, or if it was a draw.
