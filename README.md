# Asteroids Game

A Python implementation of the classic arcade game *Asteroids*, built using the `pygame` library. This project features a complete game loop, collision detection, asteroid splitting mechanics, and a custom logging system to record game states and events.

## Features

* **Player Control:** Physics-based movement with rotation and acceleration.
* **Combat System:** Shoot projectiles to destroy asteroids.
* **Asteroid Mechanics:** Asteroids spawn dynamically from the screen edges and split into smaller chunks when hit.
* **Collision Detection:** Circle-based collision detection for precise interactions.
* **Game Logging:** Automatically logs detailed game state (position, velocity, rotation) and events (shots, collisions) to JSONL files for analysis.

## Requirements

* **Python**: 3.13 or higher
* **Dependencies**: `pygame` (v2.6.1)

## Installation

1.  **Clone the repository:**
    ```bash
    git clone <repository-url>
    cd asteroid-game
    ```
