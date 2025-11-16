

# Scrabble Game in C++ (OOP)

![Scrabble](https://upload.wikimedia.org/wikipedia/commons/thumb/f/f7/Scrabble_Game.jpg/320px-Scrabble_Game.jpg)

[![C++](https://img.shields.io/badge/Language-C++-blue)](https://isocpp.org/) [![OOP](https://img.shields.io/badge/Concept-OOP-green)](#) [![License](https://img.shields.io/badge/License-MIT-yellow)](#)

---

## Overview

A **console-based Scrabble game** implemented in **C++** using **OOP principles**.
Supports **2-4 players**, turn-based gameplay, word validation, scoring, and clean modular code.

**Author:** Mostafa Hossam – Experienced in OOP projects like this Scrabble game, CCNA certified.

---

## Features

* Player management (names, scores, letters)
* Correct tile distribution and points
* Horizontal and vertical word placement
* Word validation via `wordlist.txt`
* 15x15 board display
* Winner or tie detection

---

## Tile Points

| Letter | Quantity | Points |
| ------ | -------- | ------ |
| A      | 9        | 1      |
| B      | 2        | 3      |
| C      | 2        | 3      |
| D      | 4        | 2      |
| E      | 12       | 1      |
| F      | 2        | 4      |
| G      | 3        | 2      |
| H      | 2        | 4      |
| I      | 9        | 1      |
| J      | 1        | 8      |
| K      | 1        | 5      |
| L      | 4        | 1      |
| M      | 2        | 3      |
| N      | 6        | 1      |
| O      | 8        | 1      |
| P      | 2        | 3      |
| Q      | 1        | 10     |
| R      | 6        | 1      |
| S      | 4        | 1      |
| T      | 6        | 1      |
| U      | 4        | 1      |
| V      | 2        | 4      |
| W      | 2        | 4      |
| X      | 1        | 8      |
| Y      | 2        | 4      |
| Z      | 1        | 10     |

---

## Sample Board Layout

```
   A B C D E F G H I J K L M N O
1  . . . . . . . . . . . . . . .
2  . . . . . . . . . . . . . . .
3  . . . . . . . . . . . . . . .
4  . . . . . . . . . . . . . . .
5  . . . . . . . . . . . . . . .
6  . . . . . . . . . . . . . . .
7  . . . . . . . . . . . . . . .
8  . . . . . . . . . . . . . . .
9  . . . . . . . . . . . . . . .
10 . . . . . . . . . . . . . . .
11 . . . . . . . . . . . . . . .
12 . . . . . . . . . . . . . . .
13 . . . . . . . . . . . . . . .
14 . . . . . . . . . . . . . . .
15 . . . . . . . . . . . . . . .
```

* Empty cells are represented by `.`
* Letters are displayed in **capital** once placed

---

## How to Play

1. Compile the project:

```bash
g++ main.cpp -o Scrabble
```

2. Run the game:

```bash
./Scrabble
```

3. Enter the number of players (2-4) and their names.
4. On each turn:

   * Refill letters (up to 7)
   * Enter a word and starting position (horizontal or vertical)
   * Word is validated and score updated
5. Continue until players decide to end the game.
6. Winner(s) displayed based on total score.

---

## Future Improvements

* Add **blank tiles** as wildcards
* Implement **bonus squares** (double/triple letters/words)
* Add **AI players** for single-player mode
* Develop a **graphical interface** for better experience

---

## License

This project is licensed under the **MIT License** – see the LICENSE file for details.

---
