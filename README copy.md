# F1 Pac-Man Game

A modified version of Pac-Man featuring F1 racing cars and flags! The game window has been optimized to fit better on smaller screens.

## Game Features

### Characters
- **Player**: Red F1 race car (replaces Pac-Man)
- **Ghosts**: Racing flags (replace the original ghosts)
- **Power Pellets**: Tires with different effects

### Window Size
- **Optimized Size**: 600x650 pixels (fits better on smaller screens)
- **Compact Layout**: Smaller board design for better visibility

### Controls
- **Arrow Keys**: Move the race car
  - Right Arrow: Move right
  - Left Arrow: Move left  
  - Up Arrow: Move up
  - Down Arrow: Move down
- **Space Bar**: Restart game (when game over or won)

### Tire Power-Ups
- **Yellow Tires (S)**: Speed boost - doubles car speed for 5 seconds
- **Green Tires (M)**: Balance - gives points but no special effect
- **Red Tires (H)**: Invincibility - temporary immunity to flags for 10 seconds

### Power-Up Indicators
- **Blue Circle**: Standard power pellet active
- **Yellow Circle**: Speed boost active
- **Red Circle**: Invincibility active

### Gameplay
- Collect all dots and tires to win
- Avoid the flag ghosts unless you have a power-up
- Use the different tire types strategically
- The race car moves smoothly in all directions
- Flags move around the track like traditional Pac-Man ghosts

## How to Run
```bash
python pacman.py
```

## Requirements
- Python 3.x
- Pygame library

## Assets Used
- Race car images for the player (directional red race cars)
- Flag images (1.png, 2.png, 3.png, 4.png) for the ghosts
- Custom tire images for power-ups 