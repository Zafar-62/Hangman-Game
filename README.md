# 🎮 Hangman Game

## 📌 Project Overview

**Hangman Game** is an interactive Python-based word guessing application developed by **Zafa International**.

The project provides an engaging and user-friendly gaming experience where players attempt to identify a randomly selected six-letter fruit by guessing one letter at a time.

The application combines Python programming with an interactive dashboard-style interface using **Jupyter Notebook** and **ipywidgets**, providing a clean and visually appealing user experience.

---

## 🏢 Developed By

**Zafa International**

**Software Development & Technology Solutions**

Zafa International focuses on developing practical, reliable, and user-friendly software solutions using modern technologies and programming practices.

---

## 🎯 Project Objectives

The main objectives of this project are:

* Develop an interactive Hangman game using Python.
* Implement random word selection.
* Provide an intuitive letter-guessing mechanism.
* Manage player attempts and game states.
* Limit incorrect guesses to six attempts.
* Create an attractive dashboard-style interface.
* Provide simple and responsive game controls.
* Demonstrate practical Python programming implementation.

---

## ✨ Key Features

### 🎲 Random Fruit Selection

A fruit is randomly selected from the predefined list whenever a new game starts.

### 🔤 Letter Guessing

Players can enter letters to reveal the hidden fruit.

### ❤️ Six Incorrect Attempts

The player is allowed a maximum of **6 incorrect guesses**.

### ▶️ Start Game

Starts a new gaming session and selects a random fruit.

### 🆕 New Game

Allows the player to start another round with a new randomly selected fruit.

### 🛑 End Game

Allows the player to end the current game session.

### 📊 Interactive Dashboard

The dashboard displays important game information, including:

* Hidden word
* Guessed letters
* Incorrect guesses
* Remaining attempts
* Game status

### 🏆 Win Detection

The application automatically detects when the player successfully reveals the complete fruit.

### ❌ Game Over Detection

The game automatically ends when the maximum number of incorrect guesses is reached.

### 🎨 User-Friendly Interface

The application uses `ipywidgets` along with HTML/CSS styling to provide an interactive dashboard experience.

---

## 🍎 Fruit Categories

The current version includes five six-letter fruit names:

* Banana
* Cherry
* Orange
* Papaya
* Litchi

The fruit list can be easily expanded with additional words.

---

## 🛠️ Technologies Used

| Technology           | Purpose                               |
| -------------------- | ------------------------------------- |
| **Python**           | Core application development          |
| **Jupyter Notebook** | Development and execution environment |
| **ipywidgets**       | Interactive user interface            |
| **HTML**             | Interface structure                   |
| **CSS**              | Dashboard styling                     |
| **Random Module**    | Random fruit selection                |

---

## 🧠 Programming Concepts

The project demonstrates the practical use of:

* Variables
* Strings
* Lists
* Functions
* Conditional statements
* `if / elif / else`
* `for` loops
* `while` loops
* Random selection
* User input
* Event handling
* Game-state management

---

## 🎮 Game Workflow

```text
Start Game
     ↓
Random Fruit Selected
     ↓
Hidden Word Displayed
     ↓
Player Enters a Letter
     ↓
Letter Validation
     ↓
 ┌─────────────────┐
 │ Correct Guess   │
 └────────┬────────┘
          ↓
    Reveal Letter

          OR

 ┌─────────────────┐
 │ Incorrect Guess │
 └────────┬────────┘
          ↓
 Increase Wrong Attempts
          ↓
 Check Remaining Attempts
          ↓
   Win / Continue / Game Over
```

---

## 📋 Game Rules

1. A fruit is randomly selected when the game starts.
2. The selected fruit remains hidden.
3. The player guesses one letter at a time.
4. Correct letters are revealed.
5. Incorrect guesses increase the attempt counter.
6. A maximum of **6 incorrect guesses** is allowed.
7. The player wins by revealing all letters before the attempts run out.
8. The game ends after six incorrect guesses.

---

## 💻 Requirements

The following software is required to run the project:

* Python 3.x
* Jupyter Notebook or JupyterLab
* ipywidgets

Install `ipywidgets` if required:

```bash
pip install ipywidgets
```

---

## ▶️ How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/Hangman-Game.git
```

### 2. Open the Project Folder

```bash
cd Hangman-Game
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 4. Open the Notebook

Open:

```text
Hangman_Game.ipynb
```

### 5. Run the Notebook

Run all cells and use the interactive dashboard to play the game.

---

## 📁 Project Structure

```text
Hangman-Game/
│
├── Hangman_Game.ipynb
├── README.md
│
└── screenshots/
    ├── game_start.png
    ├── gameplay.png
    ├── winning_screen.png
    └── game_over.png
```

---

## 📸 Screenshots

Screenshots can be included to demonstrate the application's interface and gameplay.

Recommended screenshots:

* Game Dashboard
* Active Gameplay
* Correct Guess
* Wrong Guess
* Winning Screen
* Game Over Screen

---

## 🔮 Future Enhancements

Future versions may include:

* Multiple difficulty levels
* Expanded fruit and word categories
* Score tracking
* Timer-based gameplay
* Sound effects
* Animations
* Player statistics
* Leaderboard functionality
* Web-based version
* Mobile application version
* Database integration

---

## 🚀 Project Highlights

This project demonstrates the ability to transform fundamental programming concepts into a practical interactive application.

The dashboard-oriented interface also demonstrates attention to **user experience, application structure, and visual presentation**.

---

## 👩‍💻 Development Information
**Organization:** Zafa International
**Project:** Hangman Game
**Technology:** Python
**Development Environment:** Jupyter Notebook

---

## 📄 License

This project is developed for **portfolio, educational, and demonstration purposes**.

© 2026 **Zafa International**. All rights reserved.
