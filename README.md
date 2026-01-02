# 👾 Space Invaders: My First Logic-First Project

A classic 2D arcade shooter built using **Python** and **Pygame**. This project marks my official entry into the tech field for 2026, focusing on fundamental logic building and mathematical implementation.

## 🚀 The Mission
Instead of just "copy-pasting" a tutorial, I built this to master the "why" behind game development. This project was a deep dive into:
* **Game Loop Architecture:** Managing events, physics updates, and rendering at 60 FPS.
* **Coordinate Geometry:** Handling 2D movement and edge detection (ensuring the player and enemies stay within the 800x600 boundaries).
* **Manual State Management:** Controlling the bullet's lifecycle from "ready" to "fire" states.

## 📐 The Math of the "Hit"
The core of this game is the collision logic. Rather than using built-in library shortcuts, I implemented the **Euclidean Distance Formula** to determine when a missile hits an alien:

$$distance = \sqrt{(x_2-x_1)^2 + (y_2-y_1)^2}$$

If the distance between the two coordinates is less than 27 pixels, the game triggers an explosion sound and resets the enemy position.



## 🛠️ Features
* **Dynamic Enemy Fleet:** Uses Python Lists to manage multiple enemy objects simultaneously.
* **Randomized Spawning:** Utilizes the `random` module to ensure every playthrough is unique.
* **Synchronized Audio:** Integrated background music and real-time sound effects for lasers and explosions.
* **Real-time Scoring:** A persistent UI that tracks your progress.

## 💻 Tech Stack
* **Language:** Python 3.x
* **Library:** Pygame
* **Version Control:** Git & GitHub

## 📥 Installation & Play
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/praptishahaha/Space-Invaders-Pygame.git](https://github.com/praptishahaha/Space-Invaders-Pygame.git) 

2. **Install Requirements:**
   ```bash
   pip install pygame 

3. **Launch The Game:**
   ```bash
   python space_Invaders.py
<!-- end list -->
Controls: Left/Right Arrows to move, Spacebar to fire.
If you're starting your journey in 2026, let this be your sign to :

**Stop consuming and start creating!**