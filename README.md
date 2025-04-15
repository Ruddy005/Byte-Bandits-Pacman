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

✨ **Clean 2D Graphics** with OpenGL  
🧠 **Monster AI** with random movement and obstacle awareness  
🎯 **Collision Detection** using a bitmap grid  
🕹️ **Intuitive Controls** with WASD + Spacebar  
🍭 **Dot Eating Mechanism** + Score Tracking  
🔁 **Replay System** to restart after losing  

---

## 🖥️ Requirements

- ✅ C++ Compiler (e.g., Visual Studio, g++)
- ✅ OpenGL Libraries
- ✅ GLUT (OpenGL Utility Toolkit)
- ✅ Windows.h *(For Windows users only)*

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
