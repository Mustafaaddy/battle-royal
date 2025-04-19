# 2D Battle Royale Game

A simple 2D battle royale style game built with Python and Pygame.

## Setup

1. Make sure you have Python 3.7+ installed on your system
2. Install the required dependencies:
```bash
pip install -r requirements.txt
```

## How to Play

Run the game:
```bash
python main.py
```

### Controls:
- WASD - Move the player
- Left Mouse Button - Shoot
- R - Restart game when game over
- ESC or close window to quit

### Features:
- Player movement with WASD keys
- Shooting mechanics with mouse aim
- Health and ammo system
- Score tracking
- Enemy AI that chase and shoot at the player
- Shrinking play zone (purple circle) that damages players outside
- Pickups:
  - Green: Health (+25 HP)
  - Yellow: Ammo (+15 bullets)

### Game Mechanics:
- Start with 100 health and 30 ammo
- Enemies spawn from the edges of the screen
- Enemy bullets deal 10 damage
- Your bullets deal 25 damage to enemies
- Each enemy killed gives 10 points
- The play zone (purple circle) shrinks over time
- Being outside the play zone causes damage
- Game ends when player health reaches 0

## Tips:
- Collect pickups to maintain health and ammo
- Stay inside the purple circle to avoid damage
- Keep moving to avoid enemy bullets
- Use obstacles and positioning to your advantage
- Don't waste ammo - make your shots count!

## Current Features
- Basic player movement
- Shooting mechanics
- Simple HUD with health, ammo, and score

More features coming soon! 
