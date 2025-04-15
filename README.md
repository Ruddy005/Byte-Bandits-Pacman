<h1 align="center">
  🎮 Byte-Bandits: Pac-Man Clone
</h1>

<p align="center">
  A retro-style <b>Pac-Man game</b> built with <b>C++</b>, <b>OpenGL</b>, and <b>GLUT</b>.<br>
  Dodge ghosts, eat all the dots, and survive the maze! 🧠💥
</p>

<p align="center">
  <img src="https://img.shields.io/badge/C++-Game-blue.svg?style=flat-square" />
  <img src="https://img.shields.io/badge/OpenGL-Graphics-green.svg?style=flat-square" />
  <img src="https://img.shields.io/badge/GLUT-Support-orange.svg?style=flat-square" />
  <img src="https://img.shields.io/badge/Status-Playable-brightgreen.svg?style=flat-square" />
</p>

---

## 🕹️ Game Overview

> **Byte-Bandits** is a minimalist Pac-Man-style arcade game where:
> - You guide Pac-Man 🟡
> - Through a dangerous maze 🧱
> - Eating food dots 🍬
> - While avoiding four colorful monsters 👻

It's built with **OpenGL** and **GLUT**, and coded in **C++** for a fun low-level gaming experience.

---

## 🔥 Features at a Glance

> - ✨ **Clean 2D Graphics** with OpenGL  
> - 🧠 **Monster AI** with random movement and obstacle awareness  
> - 🎯 **Collision Detection** using a bitmap grid  
> - 🕹️ **Intuitive Controls** with WASD + Spacebar  
> - 🍭 **Dot Eating Mechanism** + Score Tracking  
> - 🔁 **Replay System** to restart after losing  

---

## Controls
| Key | Action |
|-----|--------|
| W   | Move Up |
| A   | Move Left |
| S   | Move Down |
| D   | Move Right |
| Space | Start/Restart Game |

## Game Rules
- Collect all food dots to win (106 total)
- Avoid contact with monsters
- Game ends when:
  - All food is collected (win)
  - Pacman touches a monster (lose)

## 🎮 How to Play

### 🍽 *Objective*
- 🥄 Collect all the *white dots* (food) scattered across the maze.
- 👻 *Avoid monsters* that roam unpredictably around the maze.
- ⭐ Every food pellet increases your *score*!

---

### 👻 *Monsters*
- There are *4 colorful monsters* with different behaviors.
- They move *automatically* and can randomly change direction.
- ❌ *Touching a monster = Game Over*

---

### 🧱 *Maze & Obstacles*
- The maze is built with *walls and obstacles*.
- 🚫 *You cannot pass through walls* or barriers.
- Movement is *restricted to open paths* in the game’s bitmap.

---

### 🟡 *Pac-Man Appearance*
- Pac-Man is a *yellow circle* (🟡) with an animated mouth, drawn using *arcs*.
- He *rotates* to face the direction he's moving — left, right, up, or down.

---

### 🏆 *Winning the Game*
- ✅ Eat *all the food dots*.
- 🚫 Don’t get caught by *any monster*.
- ⏳ There’s *no time limit* – plan wisely and take your time!

---

### 🔁 *Restarting the Game*
- If you get caught, the game will *prompt you to restart*.
- This uses a *replay flag* handled in the game code.

---

### 💡 *Tips & Tricks*
- 🧠 *Think ahead*: Don’t get cornered by monsters!
- ⚡ *Clear food zones quickly*, but stay alert.
- 🧱 *Use walls smartly* to *dodge or block* monsters.
- 🌀 Don’t rush — patience is key to survival!

---


## 🖥️ Requirements

> - ✅ C++ Compiler (e.g., Visual Studio, g++)
> - ✅ OpenGL Libraries
> - ✅ GLUT (OpenGL Utility Toolkit)
> - ✅ Windows.h *(For Windows users only)*

---

## ⚙️ Setup & Run Instructions

```bash
# Step 1: Clone the repository
git clone https://github.com/yourusername/byte-bandits-pacman.git

# Step 2: Navigate to project folder
cd byte-bandits-pacman

# Step 3: Compile the code
g++ Main.cpp -o pacman -lGL -lGLU -lglut

# Step 4: Run the game
./pacman
```
> Made with ❤ in C++. Enjoy the game and don’t get eaten!
