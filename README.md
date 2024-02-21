# Command-Line Wordle in C

## What is Wordle?
Wordle is a popular word game created by software engineer Josh Wardle and can be played [online](https://www.nytimes.com/games/wordle/index.html). Players are given six attempts to guess a five-letter word, in which each guess is provided a color code for each letter to indicate if the letter is correct. Red indicates that the letter is not found in the word, yellow indicates that the letter is found in the word but in the incorrect position, and green indicates that that the letter is correct and correctly positioned. 

![](https://github.com/xgigglypuff/wordle-in-c/blob/main/Wordle-in-C.GIF)

## Why "Wordle in C?"
This project is a command-line game developed that I developed in C for a course assignment while studying at Harvard. In this version, users can play a game that functions like Wordle--except for unlimited times, with variations on the word's letter count, and for free--all from their command line! 

## Usage
In order to run the program, users will need to download the [CS50 library](https://github.com/cs50/libcs50/releases) and follow these [instructions](https://github.com/xgigglypuff/libcs50). The code must then be compiled.

To play, users must type "./wordle *n*" into the command-line, with *n* being an integer 5, 6, 7, or 8 that indicates how many letters the word should contain. From there, users will be prompted to enter "guess" words until they have solved the puzzle or run out of guesses. Note that this version does not test to see if the user input is a dictionary-verified word.

## Specifications
- *wordle.c* contains the source code that runs the game.
- *5.txt* is a file of 1,000 five-letter words to be used for the game. 
- *6.txt* is a file of 1,000 six-letter words to be used for the game. 
- *7.txt* is a file of 1,000 seven-letter words to be used for the game. 
- *8.txt* is a file of 1,000 eight-letter words to be used for the game. 
- Any of these .txt files can be updated with additional words of your choice.
