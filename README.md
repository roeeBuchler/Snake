# Snake Game

## Overview
This project is a classic **Snake Game** implemented in Python using the **Pygame library**. It features smooth gameplay mechanics, collision detection, sound effects, and a visually appealing grid background. The game is a fun and interactive way to demonstrate Python programming skills and game development concepts.

---

## Features

### Gameplay Mechanics
- **Snake Movement**: Control the snake using the arrow keys (Up, Down, Left, Right).
- **Food Collection**: The snake grows in size as it collects apples.
- **Game Over Conditions**:
  - Snake collides with the screen boundaries.
  - Snake collides with itself.
- **Restart Functionality**: Press `SPACE` after Game Over to restart the game.

### Visual and Audio Elements
- **Grid Background**: Alternating grid colors for a polished visual effect.
- **Custom Snake Graphics**: Unique head, tail, and body graphics for a smooth visual experience.
- **Sound Effects**:
  - **Apple Crunch**: Plays when the snake eats an apple.
  - **Background Music**: Plays during gameplay for an immersive experience.

### Score Display
- The current score (number of apples collected) is displayed on the screen in real-time.

---

## Prerequisites
- **Python 3.8 or above**
- **Pygame library**

Install Pygame using pip:
```bash
pip install pygame
```

---

## How to Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/roeeBuchler/Snake.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd Snake
   ```

3. **Run the game**:
   ```bash
   python app.py
   ```

---

## Gameplay Instructions
- Use the **arrow keys** to control the snake's direction:
  - **UP**: Move up.
  - **DOWN**: Move down.
  - **LEFT**: Move left.
  - **RIGHT**: Move right.
- Eat the apples to grow the snake and increase your score.
- Avoid colliding with the walls or yourself.
- When the game ends, press **SPACE** to restart.

---

## File Structure
```
Snake/
│-- app.py              # Main game logic
│-- crunch.wav          # Apple eating sound effect
│-- game_sound.mp3      # Background game music
│-- Graphics/
│   │-- head_up.png     # Snake head facing up
│   │-- head_down.png   # Snake head facing down
│   │-- head_left.png   # Snake head facing left
│   │-- head_right.png  # Snake head facing right
│   │-- tail_up.png     # Snake tail facing up
│   │-- tail_down.png   # Snake tail facing down
│   │-- ...             # Other snake body graphics
│-- README.md           # Project documentation
```

---

## Showcase
Include screenshots or GIFs of the gameplay here.

---

## Skills Demonstrated
- **Python Programming**: Object-oriented design with classes for game components.
- **Game Development**: Smooth movement, collision detection, and restart functionality.
- **Pygame**: Managing graphics, sound effects, and events.
- **Problem Solving**: Implementing game logic for a responsive experience.

---

## Future Enhancements
- Add obstacles to increase difficulty.
- Implement multiple levels with increasing speeds.
- Create a high-score system.
- Add more sound effects and animations for enhanced visuals.

---

**Project by Roee Buchler**
