# Snake Game

This is a simple Snake Game implemented in Java using the `javax.swing` library. The game features a snake that grows in length as it eats apples, and the player must avoid colliding with the walls or the snake's own body.

<img width="447" alt="Snake" src="https://github.com/user-attachments/assets/78d357e4-42c8-44b3-90a3-2b9257d60f0e" />

---

## Features

- **Classic Snake Gameplay**: Control the snake using arrow keys to eat apples and grow longer.
- **Score Tracking**: The game keeps track of the number of apples eaten.
- **Game Over Screen**: Displays the final score when the game ends.
- **Grid-based Movement**: The snake moves in a grid-based system for smooth and predictable movement.

---

## How to Run

### Prerequisites

- Java Development Kit (JDK) installed on your machine.
- An IDE or terminal to compile and run the Java code.

### Steps

1. **Clone the Repository** (if applicable):
   ```bash
   git clone https://github.com/your-username/snake-game.git
   cd snake-game
   ```

2. **Compile the Code**:
   - If using an IDE like IntelliJ or Eclipse, simply import the project and run it.
   - If using the terminal, navigate to the project directory and compile the code:
     ```bash
     javac GamePanel.java
     ```

3. **Run the Game**:
   - In the terminal, run the compiled code:
     ```bash
     java GamePanel
     ```
   - The game window should open, and you can start playing immediately.

---

## Controls

- **Arrow Keys**: Use the arrow keys to control the direction of the snake.
  - **Up Arrow**: Move the snake upwards.
  - **Down Arrow**: Move the snake downwards.
  - **Left Arrow**: Move the snake to the left.
  - **Right Arrow**: Move the snake to the right.

---

## Game Rules

- The snake grows longer each time it eats an apple.
- The game ends if the snake collides with the walls or its own body.
- The goal is to eat as many apples as possible without crashing.

---

## Code Structure

The main class is `GamePanel.java`, which handles the game logic, rendering, and user input. Here are the key methods:

- `startGame()`: Initializes the game and starts the timer.
- `draw(Graphics g)`: Renders the game components (snake, apple, grid, and score).
- `move()`: Updates the snake's position based on the current direction.
- `checkApple()`: Checks if the snake has eaten an apple and updates the score.
- `checkCollisions()`: Checks for collisions with walls or the snake's body.
- `gameOver(Graphics g)`: Displays the game over screen with the final score.

---

## Customization

You can customize the game by modifying the following constants in the `GamePanel` class:

- **Grid Size**: Change `SCREEN_WIDTH`, `SCREEN_HEIGHT`, and `UNIT_SIZE` to adjust the grid dimensions.
- **Game Speed**: Adjust the `DELAY` constant to change the speed of the game.
- **Colors**: Modify the `Color` values in the `draw()` method to customize the snake, apple, and background colors.

---
Enjoy the game! 🎮
---
