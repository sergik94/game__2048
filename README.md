# 2048 game
It is own implementation of the popular game “2048”  using HTML/SASS(with BEM), Native JavaScript

[DEMO LINK](https://sergik94.github.io/game__2048/)

Game description:
  1) The player moves cells with keyboard arrows
  2) All the numbers move in the selected direction until all empty cells are filled in
    - 2 equal cells should be merged into a doubled number
    - The merged cell doesn't merged twice during one move
  3) The move is possible if at least one cell is changed after the move
  4) After move 2 or 4 appears in a random empty cell. 4 probability is 10%
  5) When 2048 value is displayed in any cell, win message is shown.
  6) The `game over` message is shown if there are no more available moves.
  7) Message hides when game starts.
  8) Increasing score with each move. The score is increased by the sum of all merged cells.
