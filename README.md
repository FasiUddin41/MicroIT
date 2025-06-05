# MicroIT - Internship Projects

Welcome to the MicroIT repository! This repository hosts my projects developed during the internship. Currently, it includes two classic command-line games: **Rock, Paper, Scissors** and **Tic-Tac-Toe**.

---

## Projects Overview

### 1. Rock, Paper, Scissors

A classic hand game played between two people. In this version, you play against the computer. The game is implemented in Python and features colored output for a more engaging experience.

#### How to Play:
1. Run the `Rock_Paper_Scissor.py` script.
2. When prompted, enter your choice: 'Rock' (r), 'Paper' (p), or 'Scissors' (s).
3. The computer will make its choice, and the winner will be declared.
4. You'll have an option to play again or exit the game.

#### Features:
* **Interactive Gameplay:** Simple command-line interface.
* **Colored Output:** Uses `colorama` for enhanced readability and visual feedback.
* **Player vs. Computer:** Play against an AI opponent.

---

### 2. Tic-Tac-Toe

A classic paper-and-pencil game for two players, X and O, who take turns marking the spaces in a 3x3 grid. The player who succeeds in placing three of their marks in a horizontal, vertical, or diagonal row wins the game. This Python implementation offers both single-player (against the computer) and two-player modes.

#### How to Play:
1.  Run the `Tic-Tac-Toe.py` script.
2.  Choose between **Single Player Mode** (you vs. computer) or **Two Player Mode**.
3.  **For Single Player:** You play as 'X', and the computer plays as 'O'. Enter the number corresponding to the position (0-8) where you want to place your mark.
4.  **For Two Player:** Player 1 plays as 'X', and Player 2 plays as 'O'. Players take turns entering the number corresponding to their desired position.
5.  The game will announce the winner or declare a draw.
6.  You'll have an option to play again or exit the game.

#### Features:
* **Single Player Mode:** Test your skills against the computer.
* **Two Player Mode:** Play with a friend on the same console.
* **Interactive Board:** The game board is displayed after each move.
* **Colored Output:** Utilizes `colorama` for clear visualization of 'X' and 'O' marks and game messages.
* **Input Validation:** Handles invalid position inputs gracefully.

---

## Getting Started

To run these projects, you'll need Python installed on your system. These scripts also use the `colorama` library for colored console output.

### Prerequisites

* **Python 3.x**
* **`colorama` library**: If you don't have it installed, you can install it using pip:
    ```bash
    pip install colorama
    ```

### Running the Projects

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/FasiUddin41/MicroIT.git](https://github.com/FasiUddin41/MicroIT.git)
    ```

2.  **Navigate to the repository directory:**
    ```bash
    cd MicroIT
    ```

3.  **Run a project:**
    * For Rock, Paper, Scissors:
        ```bash
        python Rock_Paper_Scissor.py
        ```
    * For Tic-Tac-Toe:
        ```bash
        python Tic-Tac-Toe.py
        ```

---

## Future Enhancements

* Add more interactive games or utility scripts.
* Implement more sophisticated AI for the single-player modes.
* Consider a graphical user interface (GUI) for the games.

---

## Contribution

This repository is primarily for my internship project submissions. However, if you have suggestions for improvements or find any issues, feel free to open an issue or submit a pull request.
