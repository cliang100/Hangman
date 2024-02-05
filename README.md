# Hangman Game

Welcome to the Hangman game! Test your word-guessing skills by playing this classic game of Hangman. Can you guess the word before the hangman is fully drawn?

## Instructions

1. **File Placement:**
   - Ensure that both `hangman.py` and `words.py` files are in the same folder.

2. **Run the Game:**
   - Open a terminal or command prompt.
   - Navigate to the folder where `hangman.py` and `words.py` are located.
   - Run the game by executing the command:
     ```
     python hangman.py
     ```
     If you're using Python 3, use:
     ```
     python3 hangman.py
     ```

3. **Gameplay:**
   - Follow the on-screen instructions to guess letters and uncover the hidden word.
   - When prompted, enter a letter to guess. The game will let you know if the letter is correct or incorrect.

4. **Objective:**
   - Guess the complete word before the hangman figure is drawn completely. You have a limited number of incorrect guesses, so choose your letters wisely.

5. **Enjoy the Game!**
   - Have fun playing Hangman! Try to guess the word and avoid the hangman's fate.

## Files

- **`hangman.py`**: This file contains the main logic for the Hangman game, including the game loop, word selection, and user input handling.

- **`words.py`**: This file stores a list of words used in the game. The `get_valid_word` function in `hangman.py` randomly selects a word from this list.

## Notes

- The hangman figure will be drawn incrementally for each incorrect guess. Make your guesses carefully to avoid completing the hangman.

- The game provides feedback on the guessed letters, the current state of the word, and the hangman figure.

- If you encounter any issues or have suggestions, feel free to reach out.

Enjoy playing Hangman! Can you save the stick figure from hanging?
