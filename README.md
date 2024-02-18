# Jumbled Word Guessing Game Documentation


## Overview
This is a simple word guessing game where two players take turns guessing words that are randomly chosen from a predefined list. The players earn points for correctly guessing words and the game continues until they decide to quit.

## Functionality
* choose(): This function selects a random word from a predefined list of words.

* jumble(word): This function shuffles the letters of a given word to create a jumbled version of it.

* thank(p1name, p2name, p1s, p2s): This function prints a thank you message along with the scores of both players at the end of the game.

play(): This function implements the main gameplay logic. It takes input from two players, compares their guesses with the selected word, updates scores accordingly, and continues the game until players decide to quit.

## Usage
To play the game:

## Run the script.
Enter the names of both players when prompted.
Guess the word based on the jumbled letters provided.
Continue playing until you decide to quit by entering '0' when prompted.
Example
python
Copy code
play()

## Note
The game assumes that players will input correct spellings of the guessed words.
This documentation provides an overview of the code functionality and how to use it to play the word guessing game.
