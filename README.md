# Byte-Bandits-Pacman

🕹 Game Description - Pacman with OpenGL
This is a 2D Pacman-style arcade game created using OpenGL and C++. The player controls Pacman, navigating through a maze to collect food while avoiding colorful monsters.

🔧 Key Features
Graphics: Built using OpenGL and GLUT, the game includes simple shapes for walls, food, Pacman, and monsters.

Maze Design: Walls and obstacles are defined via coordinate vectors. The maze is drawn using glRectf with predefined borders and multiple obstacle layers (top, middle, bottom).

Pacman Movement: Controlled using keyboard input (WASD or arrow keys). Movement is managed using xIncrement, yIncrement, and rotation.

Monsters: Four ghosts with unique starting positions and simple AI to move randomly or follow paths.

Food Items: Small white dots scattered across the maze. When Pacman touches them, they disappear and
