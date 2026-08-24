# Snake and Ladder Game in C

A simple console-based Snake and Ladder game written in C. The game supports up to four players and uses random dice rolls to move players across a 100-cell board.


## How to Play

1. Start the program.
2. Enter the number of players. The game supports up to 4 players.
3. The game board will be displayed.
4. Press **Enter** to roll the dice.
5. The player moves according to the dice result.
6. If the player lands on a snake, the player moves down to the snake's tail.
7. If the player lands on a ladder, the player moves up to the ladder's top.
8. If the dice result causes the player's position to exceed 100, the player does not move.
9. Players take turns until one player reaches position 100.
10. The first player to reach exactly position 100 wins the game.


### Snakes

| Snake Head | Snake Tail |
|------------|------------|
| 99         | 4          |
| 95         | 55         |
| 89         | 51         |
| 59         | 37         |
| 47         | 32         |
| 39         | 3          |


### Ladders

| Ladder Start | Ladder End |
|--------------|------------|
| 8            | 30         |
| 17           | 44         |
| 31           | 67         |
| 42           | 80         |
| 57           | 85         |
| 73           | 93         |
