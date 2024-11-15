# **Car Racing Game**

A dynamic and competitive car racing game built using Python and Pygame. This game challenges players to compete against an AI-driven bot car across 10 progressively harder levels. The game features intuitive controls, responsive mechanics, and an engaging gameplay experience.

---

## **Features**

- **Dynamic Gameplay**:
  - Player-controlled car with smooth acceleration, deceleration, and steering.
  - AI-driven bot car with adaptive difficulty and path-following logic.
- **Progressive Levels**:
  - 10 levels with increasing difficulty for the bot.
  - Level progression triggers upon the player’s victory.
- **Real-Time Display**:
  - Displays current level, time elapsed, and car velocity.
- **Collision Detection**:
  - Car collisions with track borders and finish line handled via masks.

---

## **Game Controls**

| Key         | Action                     |
|-------------|----------------------------|
| **W**       | Move forward               |
| **S**       | Move backward              |
| **A**       | Rotate left                |
| **D**       | Rotate right               |

---

## **How to Run the Game**

1. Clone the repository:

   ```
   git clone https://github.com/AKcode07/Car-Racing-Project.git
   ```

2. Navigate to the project directory:

  ```
    cd car-racing-game
  ```

3. Install the required library:

  ```
    pip install pygame
  ```
4. Ensure the imgs folder is in the same directory as the script. This folder must contain:

  grass.jpg
  track.png
  track-border.png
  finish.png
  red-car.png
  green-car.png

5. Run the game:

  ```
    python racing_game.py
  ```