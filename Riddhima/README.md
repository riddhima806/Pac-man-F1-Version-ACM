# Pac-Man F1 Version (ACM)

A modern, Python-based recreation of the classic Pac-Man game, built from scratch using PyGame. This project features custom graphics, smooth gameplay, and all the classic mechanics you love—dots, power pellets, ghosts, and more!

## Features

- **Classic Pac-Man Gameplay:** Eat dots, avoid ghosts, and collect power-ups to turn the tables!
- **Multiple Ghosts:** Includes Blinky, Pinky, Inky, and Clyde, each with unique behaviors.
- **Power-Ups:** Eat big dots to become temporarily invincible and eat ghosts.
- **Custom Graphics:** All player and ghost sprites are included in the assets.
- **Score and Lives Tracking:** See your score and remaining lives on screen.
- **Victory and Game Over Screens:** Get feedback when you win or lose.
- **Restart Option:** Press the space bar to restart after a win or loss.

## Screenshots

## Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone <repo-url>
   cd Pac-man-F1-Version-ACM/Riddhima
   ```

2. **Install dependencies:**
   - Make sure you have Python 3.x installed.
   - Install PyGame:
     ```bash
     pip install pygame
     ```

3. **Run the game:**
   ```bash
   python main.py
   ```

## Controls

- **Arrow Keys:** Move Pac-Man (Up, Down, Left, Right)
- **Space Bar:** Restart the game after a win or game over
- **Close Window:** Quit the game

## File Structure

- `main.py` — Main game logic and loop
- `board.py` — Board layout and level data
- `assets/`
  - `player_images/` — Pac-Man animation frames
  - `ghost_images/` — Ghost sprites (Blinky, Pinky, Inky, Clyde, power-up, dead)
- `README.md` — This file

## How to Play

- Eat all the small dots to win the level.
- Avoid the ghosts—if they catch you, you lose a life.
- Eat a big dot (power pellet) to turn ghosts blue and eat them for extra points.
- The game ends when you lose all your lives or clear the board.

## Credits

- **Developers:** ACM F1 Team
- **Graphics:** Custom sprites in `assets/`
- **Framework:** [PyGame](https://www.pygame.org/)

## License

This project is licensed under the MIT License. See `LICENSE` for details.

---
