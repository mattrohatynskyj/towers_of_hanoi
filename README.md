
# Towers of Hanoi

Welcome to the Towers of Hanoi project! This repository contains a Python implementation of the classic Towers of Hanoi puzzle, a mathematical game that challenges players to move a stack of disks from one peg to another.

## Table of Contents

- [Introduction](#introduction)
- [How to Play](#how-to-play)
- [Installation](#installation)
- [Usage](#usage)
- [Game Rules](#game-rules)
- [Optimal Moves](#optimal-moves)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The Towers of Hanoi is a puzzle that involves moving a set of disks from one rod to another while following specific rules. This implementation is a command-line version where you can interactively play the game by moving disks between rods.

## How to Play

The game consists of three rods (referred to as "Left," "Middle," and "Right") and a number of disks of different sizes. The goal is to move all the disks from the "Left" rod to the "Right" rod while obeying the following rules:

1. Only one disk can be moved at a time.
2. Each move consists of taking the top disk from one rod and placing it on top of another rod or on an empty rod.
3. No larger disk may be placed on top of a smaller disk.

## Installation

To run the Towers of Hanoi game on your local machine, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/mattrohatynskyj/towers_of_hanoi.git
   cd towers_of_hanoi
   ```

2. **Ensure you have Python installed.** This game requires Python 3.

3. **Run the game:**

   ```bash
   python main.py
   ```

## Usage

After running the game, you will be prompted to enter the number of disks you'd like to play with. The game requires at least 3 disks. Once the game is set up, you'll need to move the disks from the "Left" rod to the "Right" rod using a series of inputs.

### Example:

1. **Input the number of disks**:
   ```text
   How many disks do you want to play with?
   3
   ```

2. **Make moves by selecting the source and destination rods**:
   ```text
   Enter L for Left.
   Enter M for Middle.
   Enter R for Right.
   ```
   For example, to move a disk from "Left" to "Right", you would enter:
   ```text
   L
   R
   ```

3. **Continue playing until all disks are moved to the "Right" rod**.

### Optimal Moves

The game calculates and displays the minimum number of moves required to solve the puzzle optimally, which is `2^n - 1`, where `n` is the number of disks.

## Game Rules

- You must move all disks from the "Left" rod to the "Right" rod.
- You can only move one disk at a time.
- A larger disk cannot be placed on top of a smaller disk.
- You can use the "Middle" rod as an auxiliary storage to help with the moves.

## Contributing

Contributions to this project are welcome! You can contribute by:

1. Forking the repository.
2. Creating a new branch for your feature: `git checkout -b feature-name`.
3. Committing your changes: `git commit -m 'Add some feature'`.
4. Pushing to the branch: `git push origin feature-name`.
5. Submitting a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
