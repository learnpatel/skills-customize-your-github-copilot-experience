
# 📘 Assignment: Hangman Game

## 🎯 Objective

Build a playable Hangman game that uses strings, loops, and user input to guess a hidden word. Practice managing game state and input validation in Python.

## 📝 Tasks

### 🛠️	Word Selection Setup

#### Description
Create a predefined list of words and randomly select one word to be the secret word for the round.

#### Requirements
Completed program should:

- Define a list of at least 5 words
- Randomly choose one word at the start of the game
- Store the chosen word for use during gameplay


### 🛠️	Gameplay Loop and Win/Lose Logic

#### Description
Implement the main game loop so the player can guess letters, see progress, and either win or lose based on remaining attempts.

#### Requirements
Completed program should:

- Display the current progress using underscores for unknown letters (for example, `_ _ _ _`)
- Accept one-letter guesses and update progress when correct
- Track and decrement remaining attempts for incorrect guesses
- End the game when the word is guessed or attempts reach zero
- Print a clear win or lose message at the end
