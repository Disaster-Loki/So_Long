# 🕹️ So_Long: A 2D Game Adventure 🏃‍♂️💨

Welcome to **So_Long**, a game inspired by Pac-Man, built using the **MiniLibX** library! 🎮 The player’s goal is simple: collect all the collectibles, find the exit, and escape as quickly as possible! ⏱️

---

## 🏅 42 Luanda Project
This project is part of the 42 Luanda curriculum, where students learn how to develop software from the ground up, including the use of graphical libraries like MiniLibX.

## 🚀 Game Overview

In **So_Long**, you control a character navigating through a maze. Your task is to collect all the collectibles 🟡 and find the shortest route to escape 🚪. But beware—walls will block your way, and if you are playing the bonus version, enemies 👾 might patrol the area!

### 🎯 Objectives:
- Collect all the collectibles (🟡) scattered across the map.
- Escape through the exit (🚪) after collecting everything.
- Use **W, A, S, D** to move up, left, down, and right (or arrow keys if you prefer).
- Avoid walls (⬛) and enemies (👾 in the bonus version).

---

## 🕹️ Game Features

### Mandatory Features:
1. **Character Movement**: Control your character using `W`, `A`, `S`, `D` keys or arrow keys ⬆️⬇️⬅️➡️.
2. **Movement Counter**: Track the number of movements in the shell 🧮.
3. **2D View**: The game is displayed in a simple 2D view (top-down or profile).
4. **Window Management**: 
   - Pressing **ESC** exits the game gracefully.
   - Clicking the window's close button exits the game cleanly.
   - The window management is smooth when switching, minimizing, etc.
5. **Map Parsing**: The game accepts a map with walls (⬛), collectibles (🟡), empty spaces (0), exits (🚪), and a player starting position (P).
6. **Map Validation**: Ensures that:
   - The map is rectangular.
   - There is at least 1 exit, 1 collectible, and 1 starting position.
   - The map is fully surrounded by walls (⬛).

### Bonus Features:
1. **Enemies Patrol**: If you touch an enemy 👾, you lose the game.
2. **Animated Sprites**: Character and collectible animations to enhance the visual experience ✨.
3. **On-Screen Movement Counter**: Displays the number of moves directly on the game screen instead of the shell 🧮.

---

## 🛠️ How to Run the Game

### 1. Clone the repository:
```bash
git clone git@github.com:Disaster-Loki/So_Long.git
cd So_Long
```
### 2. Compile the project:

1 - Mandatory Version: To compile the mandatory version of the game, run:
```bash
make
```
2 - Bonus Version: To compile the bonus version, run: 
```bash
make bonus
```

### 3. ▶️ How to Play

Run the game using the following commands:

1 - Mandatory Version:
```bash
./so_long maps/map.ber

2 - Bonus Version:
```bash
./so_long_bonus maps/map4.ber
```

Make sure your map follows the required format (⬛ walls, 🟡 collectibles, 🚪 exit, P player start position).

