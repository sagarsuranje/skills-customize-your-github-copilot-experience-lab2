
# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Build the classic Hangman word‑guessing game using Python. You will practice string manipulation, loops, conditionals, and handling user input while creating an interactive console program.

## 📝 Tasks

### 🛠️ Word Selection and Progress Tracking

#### Description
Implement the logic that selects a random word from a predefined list and tracks the player's progress as they guess letters.

#### Requirements
Completed program should:

- Include a list of possible words hard‑coded or loaded from a file
- Randomly choose one word at the start of each game
- Maintain and display the current progress using underscores for unknown letters (e.g. `_ a _ g _ a _`)
- Keep a record of letters that have already been guessed


### 🛠️ Game Loop and Win/Lose Conditions

#### Description
Create the main game loop that accepts user input, updates the game state, and ends the game when appropriate.

#### Requirements
Completed program should:

- Prompt the player to guess a letter each turn
- Validate input (single alphabetic character, not guessed before)
- Decrement remaining attempts on incorrect guesses and inform the player
- Detect and display a winning message when the word is completely guessed
- Display a losing message when the player runs out of attempts, revealing the word


---

Feel free to extend the game with additional features once the core requirements are met, such as allowing multiple rounds, showing a simple ASCII hangman, or letting the user add words to the list.
