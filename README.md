# Hangman
Hangman is a classic game in which a player thinks of a word and the other player tries to guess that word within a certain amount of attempts.

This is an implementation of the Hangman game, where the computer thinks of a word and the user tries to guess it. 

## Milestone 1

- The first step is setting up the GitHub repository for the Hangman Project.
- It involves creating the necessary files and documents that showcase professional documentation habits.

## Milestone 2

- Created a list containing the name of 5 fruits and assigned the list to the variable word_list.
- With the use of the module "random", a random word is selected from the list.
- The user is asked to input a single letter.
- Conditional checks are created that must be passed before the input is accepted. 

## Milestone 3

To define the functions "check_guess" and "ask_for_input" for the "Hangman" game, I followed these steps:

- First, I defined the check_guess function which takes a guessed letter as a parameter and checks if the letter is in the secret word. I passed the guess as a parameter to the function and converted it to lowercase to ensure that the game is case-insensitive.
- Next, I defined the ask_for_input function which is responsible for asking the user to guess a letter, checking if the input is valid, and checking if the guess is in the secret word. The function will continue to ask for input until a valid guess is made.
- I also called the check_guess function from within the ask_for_input function to check if the guess is in the secret word. The check_guess function takes the guess as a parameter.
- Finally, I called the ask_for_input function outside the function definition to test the code.
