# Bouncing Ball Game

A classic arcade-style brick breaker game built with Python and Pygame. Control a paddle to bounce a ball and break all the bricks to win!


<img width="1920" height="1080" alt="Screenshot (4)" src="https://github.com/user-attachments/assets/beba65af-e84b-47da-a098-6a251fd683a2" />


##  Description

This is a simple yet engaging implementation of the classic brick breaker game. The player controls a paddle at the bottom of the screen, bouncing a ball to destroy bricks at the top. The game features smooth physics, score tracking, multiple lives, and win/lose conditions.

## Features

- **Smooth Ball Physics** - Realistic bouncing with angle variation based on paddle impact
- **Multiple Brick Rows** - 5 rows of colorful bricks to destroy
- **Score System** - Earn 10 points for each brick destroyed
- **Lives System** - 3 lives to complete the game
- **Win/Lose Conditions** - Destroy all bricks to win, lose all lives to game over
- **Easy Controls** - Intuitive keyboard controls
- **Restart Functionality** - Quick restart after game over or victory

## How to Play

- **Objective**: Destroy all bricks by bouncing the ball with your paddle
- **Controls**:
  - Move Left: `LEFT ARROW` or `A` key
  - Move Right: `RIGHT ARROW` or `D` key
  - Restart: `SPACE` (after game over or win)
  - Quit: `ESC` key

## Installation

1. **Install Python** (3.6 or higher) from [python.org](https://www.python.org/)

2. **Install Pygame**:
   ```bash
   pip install pygame
   ```

3. **Download the Game**:
   - Clone this repository or download the `ball_game.py` file

4. **Run the Game**:
   ```bash
   python ball_game.py
   ```

## Gameplay Mechanics

- The ball bounces off walls, ceiling, paddle, and bricks
- Hitting the paddle at different positions changes the ball's angle
- Each brick destroyed adds 10 points to your score
- You have 3 lives - lose a life when the ball falls below the paddle
- The game ends when all bricks are destroyed (win) or lives reach zero (lose)

## Code Structure

```
ball_game.py
├── Ball Class          # Handles ball movement and drawing
├── Paddle Class        # Handles paddle movement and drawing
├── Brick Class         # Handles brick properties and drawing
└── Game Class          # Main game loop and collision detection
```

##  Possible Enhancements

Want to make the game even better? Here are some ideas:

- [ ] Add sound effects for collisions
- [ ] Implement power-ups (larger paddle, multi-ball, etc.)
- [ ] Add different brick types (harder bricks, unbreakable bricks)
- [ ] Create multiple levels with increasing difficulty
- [ ] Add particle effects for brick destruction
- [ ] Implement a high score system
- [ ] Add background music
- [ ] Create different ball skins or paddle designs

## Requirements

- Python 3.6+
- Pygame 2.0+

## Contact & Support

Om Gedam

GitHub: @itsomg134

Email: omgedam123098@gmail.com

Twitter (X): @omgedam

LinkedIn: Om Gedam

Portfolio: https://ogworks.lovable.app

## License

This project is open source and available under the [MIT License](LICENSE).

- Inspired by classic arcade games like Breakout and Arkanoid
- Built with the awesome [Pygame](https://www.pygame.org/) librar
