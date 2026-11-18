# Retro C++ Console Pong 🏓

A classic two-player Pong game implemented in C++ using the Windows Console API (`windows.h`, `conio.h`). It features a real-time game loop, randomized ball angles, collision detection, and dynamic console rendering.

## Controls

* **Player 1:**
  * Move Up: `W`
  * Move Down: `S`

* **Player 2:**
  * Move Up: `I`
  * Move Down: `K`

* **General:**
  * Quit Game: `Q`

## Prerequisites
* **OS:** Windows (relies on Windows-specific headers `<conio.h>` and `<windows.h>`).
* **Compiler:** A C++ compiler (MSVC via Visual Studio, GCC via MinGW, or Clang).

## How to Compile and Run
1. Open your terminal in the root repository directory.
2. Compile the source code:
   ```bash
   g++ PongGame/PongGame.cpp -o pong.exe
