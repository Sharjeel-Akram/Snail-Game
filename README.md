# Snail-Game
This is an artificial 2D game in which you play with AI Agent.

This is developed in python using its arcade libary for 2D games.

# Minimax and Heuistic search algorithms are used.

# Following are certain rules to play the game:

1. 2D Snail game has total hundred number of grids.
2. Initial position of 1st player will be at the bottom left but inside the
specified grid.
3. Initial position of 2nd player will be at the top right but inside the
specifies grid.Namal University Mianwali
4. A player can move one step in single turn and step can be towards left,
right, up or down.
5. A player can’t move diagonally.
6. A player can’t jump from one position to other. Instead of jumping, it
has to cover all the position to reach that specific position.
7. A player can’t move to position or splash of opponent.
8. A player can move on its own splashes but it will slip to last splash
towards moving side.
9. A player can use mouse to click to move its sprite.
10. A player can lose its turn by clicking on opponent’s position.
11. Both players have to cover maximum position to win the game.
12. When there is be no position or box of grid, the game will be ended.
13. Each legal turn and filling of empty position will add a point to total
points of that player.
14. A player with maximum number of covered position will win the game.
