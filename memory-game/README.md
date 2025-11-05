# Memory Game

A simple Java console program that challenges players memory skills. The game features eight cards (four matching pairs) that are randomly shuffled and placed face down, represented by numbered slots from 0 to 7. Players take turns entering two different indices between 0 and 7 to flip the cards and reveal what is underneath. If the two flipped cards match, they stay face up; if not, they are turned back down. The game continues until all pairs are found, and a congratulatory message is displayed at the end.

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

- Clone the Repository:
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

