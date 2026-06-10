# 🐍 Snake Game

A classic Snake Game implemented in Python using the `turtle` graphics library. This project features high-score persistence, responsive controls, and smooth gameplay mechanics.

## 🚀 Features

- **Classic Gameplay**: Navigate the snake to collect food and grow longer.
- **High Score Tracking**: Your highest score is saved locally in `data.txt` and persists across game sessions.
- **Dynamic Growth**: The snake grows in length every time it consumes food.
- **Collision Detection**: 
  - Wall collisions reset the game.
  - Tail collisions reset the game.
- **Responsive Controls**: Supports both arrow keys and WASD.

## 🎮 Controls

| Action | Keys |
|--------|------|
| **Move Up** | `Up Arrow` / `W` | 
| **Move Down** | `Down Arrow` / `S` |
| **Move Left** | `Left Arrow` / `A` |
| **Move Right** | `Right Arrow` / `D` |

## 🛠️ Requirements

- **Python 3.x**
- No external libraries required (uses built-in `turtle` and `time` modules).

## 🏃 How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/MSameer7-tech/Snake-Game.git
   cd Snake-Game
   ```

2. **Run the game:**
   ```bash
   python main.py
   ```

## 📂 Project Structure

- `main.py`: The entry point of the game, managing the game loop and collisions.
- `snake.py`: Contains the `Snake` class, handling movement and growth. 
- `food.py`: Contains the `Food` class, managing food spawning.
- `scoreboard.py`: Handles score display and high-score logic.
- `data.txt`:  Stores the high score.
