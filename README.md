# TICTACTOE
# A424Project
This document will describe how to open and run the developed code;

installing and running: 
simply download the cpp file and run on any compiler software. development was done in VS and is tailored for that, but any software capable of running C++ code will work.
Starting a game:
starting a game is very simple. upon launching the code you will be asked to select single player or 2 player game modes
  single player: in single player mode, moves are made against the computer. currently, the computer randomly chooses a spot on the board to play after you select a spot.
  two player: two players are initialized and each player gets to choose their spots until the board is full or one player wins (3 in a row). 
Winning a game: to win a game, a player needs to place 3 marks in a row in any orientation.

Board expansion: 
if the player wishes to play again, the board will expand by 1 row and 1 column. the play area expands as does the requirement for winning. the player must now match an additional mark in a row for ever dimension added to the board. for example if the board is now 5x5, the player must match 5 marks in a row to win. 
