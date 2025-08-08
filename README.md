# 🔵🔴 Connecting Dots Game

A simple game built with Python and Tkinter. Your task is to connect all matching pairs of colored dots on a grid without crossing paths. Play through built-in levels or design your own using the custom level editor!

---

## 🎮 Features

### 🧩 10 different levels
* The higher the level, the higher the difficulty.
<img width="712" height="790" alt="Screenshot 2025-07-27 at 23 48 29" src="https://github.com/user-attachments/assets/7d024061-3236-45c8-9dc2-8094635b1000" />

### ✏️ Custom level editor

* Choose a grid size and place dots to create your own puzzles.
* Save and load your own levels.
* Make sure your own level is solvable by clicking Solve button

### 🧠 Auto solver
* Use the Solve button to automatically solve custom levels.
* Algorithm uses BFS(Breadth-First Search) with backtracking to find valid paths.
<img width="712" height="790" alt="Screenshot 2025-07-27 at 21 13 35" src="https://github.com/user-attachments/assets/f8db280a-f3e7-4cbb-9664-6c4ffa7abe93" />
<img width="712" height="790" alt="Screenshot 2025-07-27 at 21 13 27" src="https://github.com/user-attachments/assets/d3339570-2af6-497a-b055-4e5962c37067" />

### 💾 Saved levels
Saved levels are saved in:

```bash
/Users/username/ConnectingDotsLevels/
```

---

## 🚀 Getting started

### 1. Install dependencies
Make sure Python 3.10+ is installed. Then install:

```bash
pip install pygame
```
### 2. Run the game
```bash
python connectingdotsgame.py
```
### Alternatively, download the MacOS app and run directly

#### 🛡️ MacOS security notice (Gatekeeper)

Since this app is not notarized by Apple or signed with a developer ID, MacOS may block it from launching. Allow the game to run by open System Settings → Privacy & Security.
