# Memory Game
The Memory Game is a fun and simple two-player game that tests your memory. In this game, a set of cards is laid face down. Players take turns flipping two cards to find matching pairs. If the two cards match, they remain face up. If not, they are flipped back down. The game continues until all pairs are found.

## How to Play the Game

- The game board has 4 pairs of cards (8 total), which are randomly shuffled.
- The board is shown as a row of numbered slots from 0 to 7.
- On each turn:
    - A player selects two different indices to flip.
    - If the values match, the pair remains visible.
    - If the value does not match, then they are hidden again.
- The game will end when all the pairs are found.

## Sample Input & Output

```
Welcome to the Memory Game!
|   |   |   |   |   |   |   |   |
Enter index of first card to flip:
0
| B |   |   |   |   |   |   |   |
Enter index of second card to flip:
1
| B | A |   |   |   |   |   |   |
Sorry, those cards don't match.
|   |   |   |   |   |   |   |   |
Enter index of first card to flip:
0
| B |   |   |   |   |   |   |   |
Enter index of second card to flip:
3
| B |   |   | C |   |   |   |   |
Sorry, those cards don't match.
|   |   |   |   |   |   |   |   |
Enter index of first card to flip:
3
|   |   |   | C |   |   |   |   |
Enter index of second card to flip:
5
|   |   |   | C |   | D |   |   |
Sorry, those cards don't match.
|   |   |   |   |   |   |   |   |
Enter index of first card to flip:
6
|   |   |   |   |   |   | D |   |
Enter index of second card to flip:
5
|   |   |   |   |   | D | D |   |
You found a pair!
|   |   |   |   |   | D | D |   |
Enter index of first card to flip:
7
|   |   |   |   |   | D | D | A |
Enter index of second card to flip:
1
|   | A |   |   |   | D | D | A |
You found a pair!
|   | A |   |   |   | D | D | A |
Enter index of first card to flip:
2
|   | A | C |   |   | D | D | A |
Enter index of second card to flip:
3
|   | A | C | C |   | D | D | A |
You found a pair!
|   | A | C | C |   | D | D | A |
Enter index of first card to flip:
0
| B | A | C | C |   | D | D | A |
Enter index of second card to flip:
4
| B | A | C | C | B | D | D | A |
You found a pair!
Congratulations, you won!
```

## Run

- Clone the repo:
  ```bash
  git clone https://github.com/itsjomon/java-mini-projects.git
  ```
  
- Navigate to the project directory:
  ```bash
  cd java-mini-projects/memory-game
  ```
  
- Compile and Run:
  ```bash
  javac src/App.java
  
  java -cp src App
  ```

