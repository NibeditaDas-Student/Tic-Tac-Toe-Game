# 🎮 Tic Tac Toe Game (Java Swing)

A desktop-based **Tic Tac Toe Game** developed using **Java Swing**.
This application provides a graphical user interface where two players can play the classic Tic Tac Toe game with a clean and interactive design.

---

## 📌 Project Overview

This project is a GUI-based implementation of the classic **Tic Tac Toe** game. It allows two players to compete in a turn-based format and determines the winner dynamically.

The game includes:

* Interactive game board
* Player turn switching
* Winner detection
* Series result display
* User interface panels

---

## 🏗️ Project Structure

```
TicTacToeGame/
│
├── TicTacToeGame.java     # Main class to launch the application
├── GamePanel.java         # Handles game board logic and UI
├── UserPanel.java         # Manages user information display
├── WhoWinSeries.java      # Determines and displays winner of series
└── README.md              # Project documentation
```

---

## 🚀 Features

* 🎨 GUI built using Java Swing
* 👥 Two-player gameplay
* 🔄 Automatic turn switching
* 🏆 Winner detection logic
* 📊 Series winner tracking
* 🖥️ Clean and user-friendly interface

---

## 🛠️ Technologies Used

* **Java**
* **Java Swing (GUI Framework)**
* **AWT Event Handling**

---

## ▶️ How to Run the Project

### 1️⃣ Prerequisites

* Java JDK 8 or above installed
* Any Java IDE (IntelliJ IDEA, Eclipse, NetBeans)
  OR
* Command Prompt / Terminal

---

### 2️⃣ Compile the Project

Using Command Prompt:

```bash
javac TicTacToeGame.java
javac GamePanel.java
javac UserPanel.java
javac WhoWinSeries.java
```

---

### 3️⃣ Run the Application

```bash
java TicTacToeGame
```

The game window will open and you can start playing.

---

## 🎯 Game Rules

1. The game is played on a 3×3 grid.
2. Player 1 uses **X**.
3. Player 2 uses **O**.
4. Players take turns placing their marks.
5. The first player to get 3 marks in a row (horizontal, vertical, or diagonal) wins.
6. If all cells are filled without a winner, the game ends in a draw.

---

## 📷 Sample Gameplay Flow

1. Application starts
2. User panel loads
3. Game board appears
4. Players alternate turns
5. Winner is displayed
6. Series winner is tracked

---

## 👩‍💻 Author

**Nibedita Das**

---

## 📄 License

This project is developed for educational purposes.
You are free to modify and use it for learning.
