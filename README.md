# Project Title - Hangman: A Classic Word guessing Game in Python
![Alt text](hangman.png)

Hangman is a classic word guessing game where the computer randomly choices a word and the player tries to guess that word within a certain amount of attempts.

This is an implementation of the Hangman game, where the computer thinks of a word and the user tries to guess it.

## Table of Contents
1. [Introduction](#project-title)
2. [Project Description](##project-description)
3. [Installation Instructions](##installation-instructions)
4. [Usage Instructions](##usage-instructions)
5. [Future Upgrades](##future-enhancements)
6. [License Information](##license-information)

## Project Description
In the classic children's game of Hangman, a player's objective is to identify a secret word of which only the number of letters is originally revealed. In each round, the player guesses a letter of the alphabet: if it is present in the secret word, all instances are revealed; otherwise one of the hangman's body parts is drawn in on a gallows. The game ends in a win if the word is entirely revealed by correct guesses, and ends in a loss if the hangman's body is completely revealed instead. To assist the player, a visible record of all guessed letters is typically maintained.

## Installation instructions
To clone this repository or download the zip file. To clone the repository, run the following command:

``` bash
git clone https://github.com/MTabrett/hangman_game_project.git
```
Then move into the hangman_directory and run
```
python milestone_5.py
``` 

## Usage instructions
To play the game, navigate to the project directory and run the milestone_5.py file:

## File structure of the project
Built in sections -
Part 1 - Milestone_2.py
        - Defined the list of possible words
        - Choose a random word from the list
        - Asked the Player for an input
        - Check that the input is a single character
        - Documented to this point
        - Updated GitHub with commits and git push
        - Refactored and optimised current code
    
Part 2 - Milestone_3.py
        - Iterately checked the player input to make sure a valid guess
        - Checked whether the player_guess was in the random_selected_word
        - Created functions to help run the checks - check if valid & is in the random_selected_word

Part 3 - Milestone_4.py - converting to OOP paradigm.
        - Create the Game class
        - Create Hangman class
        - Create __init__ method passing word_list and num_lives=5 parameters
        - Initialise following attributes -  randon_word, word_guessed, num_letters, num_lives, word_list and list_of_guesses
        - Create methods for running the checks of input valid and guess is or not in word
        - Define what happens if the letter is in the word using for-loop and if statements
        - Define what happens if the letter is NOT in the word

Part 4 - Mileston_5.py - Putting it all together
        - Created a function (play_game) that will run all the code to play the game
        - Finished code - play game 

## Future Enhancements
1. Add the gallows to be drawn as the guesses come in.
2. Connect the secret word to a database of different words.
3. Tidy up some of the instructions.

## License information
MIT license