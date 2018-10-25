CONTENTS OF THIS FILE
--------------------------------
* Game Description
* Introduction
* Design Decisions
* Installation
* Configuration
* Authors

Game Description
--------------------------------
In a regular game of WAR, the deck is divided evenly, with each player receiving 26 cards, dealt one at a time, face down. Anyone may deal first. Each player places his stack of cards face down, in front of him. Each player turns up a card at the same time and the player with the higher card takes both cards and puts them, face down, on the bottom of his stack.

If the cards are the same rank, it is War. Each player turns up one card face down and one card face up. The player with the higher cards takes both piles (six cards). If the turned-up cards are again the same rank, each player places another card face down and turns another card face up. The player with the higher card takes all 10 cards, and so on.

The goal is to win all 52 cards.


Introduction
--------------------------------

The game is implemented following the rules above. However, at the moment you can only play against the computer. The main purpose of this project was to become comfortable using pointers in C++.


Design Decisions
--------------------------------
The project uses pointers for card objects that are used in the deck. Pointers are used to traverse the deck of cards, the pointers are also used in drawing a card, inserting the card in a deck and printing the deck if needed.


Installation
--------------------------------
Download or clone this repository to a folder of your choice.
You do not need anything special to run the application (which is titled War) in the folder, however if you would like to make changes you will need at least a code editor or a C++ IDE to edit, compile, and run the code.


Configuration
--------------------------------
There is not much to change in the project but if you wanted to ensure that the deck is printing the cards correctly you can remove the war.cpp file and add the test.cpp file's code to the project, compile and run it, and make sure the deck has the correct amount of each card.


Authors
--------------------------------
Framework designed by Prof. Jay Snellen.

Worked on and edited by Earl Moss.
