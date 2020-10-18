# INST126-Fall2020

## Project 2: Hangman

### Overview
This project involves creating the well-known, classic hangman game where a user must guess the secret word before they run out of turns. This specific game, however, is a modified version where the secret word(s) are encoded. The secret word is only decoded in the end if the user wins.

### How It Works
The program will randomly select the word that the user has to guess (secret word) from an established list. Unknown to the user, all of the words are decoded, including the one that the program will randomly pick.

Once the secret word is chosen, the program will display dashes to represent how long the secret word is.
The user then will be prompted to enter a letter. If their guess is correct, the dash corresponding to the correct letter will be replaced by the user's guess. 

The user has 10 guesses to try to win the game. They will win if they correctly spell out the decoded secret word which then will be decoded and displayed after the user wins. The user will lose if they use all 10 guesses without guessing the entire decoded word. Additionally, the word will not be decoded if the user loses.

### Assumptions
The Hangman program will assume that the user:
- enters a valid input, which in this case, is a letter, lowercase or uppercase (the program will change the input to uppercase)
