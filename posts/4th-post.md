---
layout: layouts/post.njk
title: Python Games
date: 2020-05-05T11:30:00.000Z
description: Games built using Python
tags:
  - PROJECT
  - PYTHON
---
A few simple games I have built that can be played directly in the terminal. The idea here was to revisit some Python fundamentals and to solidify some of the basics, whilst also learning a bit more intermeidate-level Python.

* Sudoku - Both a solver and a generator, making use of several functions to made decisions based on user input. A backtracking algorithm is used to Solve the Sudoku - more difficult Sudoku's can take longer to solve. View on [Github](https://github.com/samabarker/terminal_games/blob/master/sudokusolver.py) and [Repl](https://repl.it/@sambarkercom/sudoku).
* Hangman - A simple hangman game. A list of words is passed into a Game class, where one of the words is randomly chosen. Looping is used to obtain user input until either the man is hung, or the correct word is guessed. My first dabble with OOP and classes. View on [Github](https://github.com/samabarker/terminal_games/blob/master/hangman.py) and [Repl](https://repl.it/@sambarkercom/hangman).
* Tic Tac Toe - Or Noughts and Crosses if you are British! A user inputs the reference of the square in which they would like to play (1-9), and then the computer plays in a random empty square. This continues until the computer wins, the player wins or noone wins. Incredibly simple. Some optimisation on where the computer plays is yet to be done (i.e. always block the play where possible, chose corners first, etc.). View on [Github](https://github.com/samabarker/terminal_games/blob/master/tictactoe.py) and [Repl](https://repl.it/@sambarkercom/tictactoe).
* Big Text - A very simple little application that takes a word and makes it big. Makes use of list comprehension and dictionaries to print a word in symbols in the terminal screen. View on [Github](https://github.com/samabarker/terminal_games/blob/master/bigtext.py) and [Repl](https://repl.it/@sambarkercom/bigtext).



After building a few games that can be played directly in the terminal, I wanted to have a play around with the PyGame package to build a more user friendly game.

* Dodge - A really simple first game where a 'player ship' has to avoid incoming 'enemy ships'. The enemy ships are randomly generated and have random speeds. There are 5 levels, getting incrementally more difficult in terms of number of enemies, enemy speeds and enemy sizes. The game keeps track of level, level score and overall score, all of which are displayed on the game screen. View on [Github](https://github.com/samabarker/pygames/blob/master/dodge.py) and [Repl](https://repl.it/@sambarkercom/dodge).