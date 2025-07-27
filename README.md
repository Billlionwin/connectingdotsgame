# 🔵🔴 Connecting Dots Game

A simple game built with Python and Tkinter. Your task is to connect all matching pairs of colored dots on a grid without crossing paths. Play through built-in levels or design your own using the custom level editor!

---

## 🎮 Features

### 🧩 Built-in Levels
* Comes with 10 pre-made levels of increasing difficulty.

### ✏️ Custom Level Editor
* Choose a grid size and place dots to create your own puzzles.
* Save and load your own levels.
* Make sure your own level is solvable by using Auto Solver

### 🧠 Auto Solver
* Use the Solve button to automatically solve custom levels.
* Algorithm uses BFS(Breadth-First Search) with backtracking to find valid paths.

### 💾 Saved levels
Saved levels are saved in:
```bash
~/ConnectingDotsLevels/
```

---

## 🚀 Getting Started

### 1. Install Dependencies
Make sure Python 3.10+ is installed. Then install:

```bash
pip install pygame
```
### 2. Run the Game
```bash
python connectingdotsgame.py
```
### Alternatively, download the MacOS app and run directly

#### 🛡️ MacOS Security Notice (Gatekeeper)

Since this app is not notarized by Apple or signed with a developer ID, macOS may block it from launching. Allow the game to run by open System Settings → Privacy & Security.
