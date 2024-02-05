Game Description: Rock, Paper, Scissors

Objective:
The objective of the Rock, Paper, Scissors game is to defeat your opponent by choosing a weapon that defeats their chosen weapon.

Rules:

Rock crushes Scissors.
Scissors cuts Paper.
Paper covers Rock.
Implementation:
The game is implemented in C# using a console application. It consists of the following components:

Player Class:

Represents a player in the game.
Has a property to store the player's chosen weapon.
Game Logic:

The game logic handles the comparison between the weapons chosen by the two players to determine the winner based on the rules.
It includes methods to check for a tie, player victories, and overall game results.
User Input:

Accepts user input to choose a weapon (Rock, Paper, or Scissors).
Validates user input to ensure a valid choice is made.
Computer Player:

Generates a random choice for the computer player.
Main Game Loop:

The main loop of the game where players make their choices, and the winner is determined.
The loop continues until the player decides to exit.
Display Results:

Displays the choices made by both players and the result of the round (win, lose, or tie).
Keeps track of overall game statistics, such as the number of wins, losses, and ties.
