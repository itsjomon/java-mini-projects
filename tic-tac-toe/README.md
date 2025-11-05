# Tic-Tac-Toe Game

A simple Java console program demonstrating the classic Tic Tac Toe game. Two players take turns placing **X** and **O** on a 3 by 3 grid by entering the slot number where they want to place their mark. The game checks after each move if a player has won or if the game ends in a draw.

## Sample Input & Output

```
Welcome to 3x3 Tic Tac Toe.
|---|---|---|
| 1 | 2 | 3 |
|-----------|
| 4 | 5 | 6 |
|-----------|
| 7 | 8 | 9 |
|---|---|---|
X will play first. Enter a slot number to place X in:
1
|---|---|---|
| X | 2 | 3 |
|-----------|
| 4 | 5 | 6 |
|-----------|
| 7 | 8 | 9 |
|---|---|---|
O's turn; enter a slot number to place O in:
3
|---|---|---|
| X | 2 | O |
|-----------|
| 4 | 5 | 6 |
|-----------|
| 7 | 8 | 9 |
|---|---|---|
X's turn; enter a slot number to place X in:
5
|---|---|---|
| X | 2 | O |
|-----------|
| 4 | X | 6 |
|-----------|
| 7 | 8 | 9 |
|---|---|---|
O's turn; enter a slot number to place O in:
6
|---|---|---|
| X | 2 | O |
|-----------|
| 4 | X | O |
|-----------|
| 7 | 8 | 9 |
|---|---|---|
X's turn; enter a slot number to place X in:
9
|---|---|---|
| X | 2 | O |
|-----------|
| 4 | X | O |
|-----------|
| 7 | 8 | X |
|---|---|---|
Congratulations! X's have won! Thanks for playing.
```

## Run

- Clone the Repository:
   ```bash
   git clone https://github.com/itsjomon/java-mini-projects.git
   ```

- Navigate to the project directory:
  ```bash
  cd java-mini-projects/tic-tac-toe
  ```

- Compile and Run:
  ```bash
  javac src/App.java

  java -cp src App
  ```