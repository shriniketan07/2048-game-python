# Python 2048 Game 

2048 is a simple mathematics puzzle game.
It is a really addictive game and the main operation performed in this game is addition which makes it easy for all of us.

![sample](Sample_2048_Game.png)
 
## How to Play
The game starts with a 4x4 grid, where two tiles (2 or 4) are randomly placed on the board.

**Use the following keys to move the tiles:**
- w to move up
- a to move left
- s to move down
- d to move right
Tiles with the same number will merge when they collide, doubling their value. A new tile (either a 2 or 4) will be placed on the board after each move.

Your goal is to merge the tiles to reach the 2048 tile. When you do, you win the game

## Game Logic
- The game board is a 4x4 grid.
- At the start, two random tiles (2 or 4) are placed at random positions.
- Tiles can be moved in four directions: up, down, left, and right.
- When two tiles of the same value collide while moving, they merge into a tile with double the value.
- After each move, a new random tile (either a 2 or 4) is added to the grid at an empty position.
- The game continues until there are no more moves available or you reach the 2048 tile and win.


## Move Logic
- Slide: Tiles without a number (zeros) move to the edge in the direction of movement.
- Merge: If two adjacent tiles have the same value, they merge into a new tile with double the value.



## The game ends when one of the following happens:

-  You win: You reach the 2048 tile.
-  Game Over: There are no empty spaces on the board, and no adjacent tiles can be merged.
