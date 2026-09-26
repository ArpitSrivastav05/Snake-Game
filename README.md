```markdown
#  Snake Game

A classic Snake Game built with **HTML, CSS, and JavaScript**.  
The player controls the snake using arrow keys, eats food to grow longer, and avoids colliding with walls or itself.  
Includes a **score tracker, high score, timer, and modal screens** for start and game over.

---

##  Features
- Responsive grid-based game board
- Snake movement controlled by keyboard (`ArrowUp`, `ArrowDown`, `ArrowLeft`, `ArrowRight`)
- Food spawns randomly on the board
- Score and high score tracking
- Timer to measure game duration
- Start screen and Game Over modal with restart functionality
- Simple, clean UI with CSS variables for easy customization

---

##  Getting Started

### Prerequisites
- A modern web browser (Chrome, Edge, Firefox, Safari)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/snake-game.git
   ```
2. Navigate into the project folder:
   ```bash
   cd snake-game
   ```
3. Open `index.html` in your browser.

---

## How to Play
1. Click **Start Game** on the modal.
2. Use arrow keys to move the snake:
   - ⬆️ `ArrowUp` → Move Up
   - ⬇️ `ArrowDown` → Move Down
   - ⬅️ `ArrowLeft` → Move Left
   - ➡️ `ArrowRight` → Move Right
3. Eat the red food blocks to grow longer and increase your score.
4. Avoid hitting the walls or colliding with yourself.
5. When the game ends, the **Game Over** modal appears with a **Restart Game** button.

---

## 📂 Project Structure
```
├── index.html   # Main HTML file
├── style.css    # Game styling
├── script.js    # Game logic
└── README.md    # Project documentation
```

---

## 🛠️ Customization
- Change block size in `script.js` (`blockHeight`, `blockWidth`)
- Update colors in `style.css` using CSS variables:
  - `--bg-primary-color` → Background
  - `--bg-fill-color` → Snake body
  - `--bg-food-color` → Food

---

## ✨ Future Improvements
- Add difficulty levels (speed increase)
- Add sound effects
- Mobile touch controls
- Save high score in local storage

---

## 📸 Screenshots
- **Start Screen**: Welcome message + Start button
- **Game Board**: Snake moving and eating food
- **Game Over Screen**: Game Over message + Restart button

---

## 👨‍💻 Author
Developed by **Arpit**  
Built for learning, fun, and practice with web development fundamentals.
```
