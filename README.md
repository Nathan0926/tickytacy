# Infinite Tic Tac Toe Game

## Overview

Infinite Tic Tac Toe is a dynamic twist on the classic Tic Tac Toe game where players can expand the board and use special "block" moves. This README will guide you through the rules, setup, and gameplay mechanics.

## Table of Contents

1. [Game Rules](#game-rules)
2. [Gameplay](#gameplay)
   - [Basic Moves](#basic-moves)
   - [Block Moves](#block-moves)
   - [Winning the Game](#winning-the-game)

## Game Rules

### Basic Rules

- The game is played by two players who take turns.
- Players can place their symbol (X or O) on any empty cell of the board.
- The board is initially 3x3 but can be expanded by the players.
- To win, a player must align a specified number of their symbols (e.g., 3 in a row for classic, or a larger number for bigger boards).

### Board Expansion
- When hitting the exapnd button, it exponentially increases the board both by rows and column.
- The expansion does count as a turn, And YES both players can use the expand move as a turn.
- If a player uses expansion as a turn, the other player wont be allowed to place an X or O to win the game, why? its funny

### Block Moves

- A block move allows a player to block an opponent's potential winning move.
- Using a block move grants the player an additional turn.
- Block moves cannot be used to directly create a winning line for the blocking player.
- Both players can use this function.


### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/katanpink/inf-ticky-tacy.git
   cd inf-ticky-tacy
   
