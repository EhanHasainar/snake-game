# 🐍 Snake Game

A classic Snake Game built using Python's `turtle` module. Control the snake to eat food, grow longer, and avoid collisions with the wall or its own tail. Score increases with each food item consumed.

---

## ✅ Features

- Classic snake movement using arrow keys.
- Random food generation and score tracking.
- "Game Over" detection on collision with walls or self.
- Easily customizable screen size, snake speed, and food color.

---

## 📁 Project Structure

```
snake-game/
├── main.py          # Main game loop and controls
├── snake.py         # Snake class: movement, growth, and reset logic
├── food.py          # Food class: random generation and appearance
├── scoreboard.py    # Scoreboard class: score display and game over logic
```

---

## 📄 File Descriptions

- **`main.py`**: Initializes the screen, sets up keyboard controls, and runs the game loop.
- **`snake.py`**: Defines the `Snake` class for movement, extending, and collision detection.
- **`food.py`**: Defines the `Food` class which randomly places food items on the screen.
- **`scoreboard.py`**: Manages the display of the score and game over messages.

---

## 🎮 How to Play

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/snake-game.git
   cd snake-game
   ```
2. Ensure you have Python 3 installed.
3. Run the game:
   ```bash
   main.py
   ```

### Controls

- **⬆️ Up Arrow**: Move Up  
- **⬇️ Down Arrow**: Move Down  
- **⬅️ Left Arrow**: Move Left  
- **➡️ Right Arrow**: Move Right  

> 🍎 Eat food to grow.  
> 💥 Avoid hitting walls or your own body.

---

## 🖼️ Example Gameplay

- Snake starts in the center of the screen.
- Food appears at random locations.
- The score is shown at the top.
- The game ends with a "Game Over" message if the snake hits the wall or itself.

---

## ⚙️ Customization

- **Snake Speed**: Modify `time.sleep(0.1)` in `main.py` to increase or decrease game speed.
- **Screen Size**: Adjust `screen.setup(width=600, height=600)` in `main.py`.
- **Food Color**: Change `self.color("blue1")` in `food.py` to your preferred color.

---

## 📦 Requirements

- Python 3.x
- The `turtle` module (comes pre-installed with Python)

---

## 🙌 Acknowledgments

Inspired by the classic Snake Game. A great beginner-friendly project to practice Python, game loops, and OOP with the turtle module.
