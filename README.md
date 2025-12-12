# guessing-the-number
3-Digit Number Guessing Game in C

This program is a simple two-player guessing game written in C.
Each player selects a secret three-digit number, and both players take turns trying to guess the other's number. After every guess, the program gives helpful feedback that tells:

Correct-position matches: digits that are correct and in the correct place

Wrong-position matches: digits that exist in the secret number but are in the wrong place

The program uses two helper functions:

splitDigits() – breaks a 3-digit number into individual digits

countMatches() – compares the guess with the secret number and calculates correct-position and wrong-position matches without double-counting

The game continues until both players guess correctly, after which the program ends.

This project demonstrates basic concepts of C programming such as arrays, loops, modular functions, and input handling. It is a simple and effective example of applying logical comparison techniques in a game format.
