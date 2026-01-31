# Asteroids - Python & Pygame

A modular implementation of the classic Asteroids arcade game.
This project focuses on **Object-Oriented Programming** principles and **Vector Mathematics** for game physics.

## 🎮 Features
* **Physics Engine:** Inertia and rotation handling using `pygame.Vector2`.
* **Collision System:** Custom circular hitbox detection logic.
* **OOP Structure:** Entity inheritance via a shared `CircleShape` base class.
* **Game Loop:** Optimized update/draw cycle locked at 60 FPS.

## 🛠️ Tech Stack
* **Language:** Python 3
* **Library:** Pygame
* **Architecture:** Component-based (Player, Asteroid, Field, Shot).

## 📦 How to Run

1. **Clone the repository**
   ```bash
   git clone [https://github.com/Pizza-beep307/asteroids-pygame.git](https://github.com/Pizza-beep307/asteroids-pygame.git)
   cd asteroids-pygame
   ```
2. **Install dependencies**
  ```bash
  pip install -r requirements.txt
  ```
3. **Start the game**
  ```bash
  python main.py
  ```
4. **Controls**
W / S: Move Forward / Backward
A / D: Rotate Ship
SPACE: Shoot
