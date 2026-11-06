# 🎮 Simon Says Game

An interactive, browser-based memory challenge inspired by the classic **Simon Says**. Built with vanilla HTML5, CSS3, and JavaScript, this project tests players' pattern recognition and focus as color-and-sound sequences grow with each round.

---

## 🔗 Live Demo
Play the game live directly in your browser:  
👉 **Play Simon Says Game : https://poulami06.github.io/Simon-Say-Game/**

> ⚠️ **Note:** This game is exclusively designed for **Desktop and Laptop browsers** because gameplay relies on physical keyboard keypress events to start. It is not optimized for mobile touchscreens[cite: 1].

---

## 🕹️ Gameplay Rules

1. **Start:** Open the live link on your PC/laptop and press **any key** on your keyboard to begin.
2. **Observe:** A color tile will flash, marking Level 1.
3. **Repeat:** Click the exact tile that flashed.
4. **Advance:** With every successful pattern, the game advances to the next level and adds another random step to the sequence.
5. **Game Over:** Choosing the wrong sequence turns the background red and reveals your score. Press any key to reset and try again!

---

## 💻 Tech Stack

* **HTML5:** Layout structure and button containers.
* **CSS3:** Game board grid, active button glow effects, and game-over flashes.
* **JavaScript (ES6):** State machines, sequence tracking, array comparisons, and DOM updates.

---

## 📁 Repository Structure

```text
├── index.html       # Markup and DOM structure
├── style.css        # Colors, styling, and transitions
├── app.js           # Core game logic and event handlers
└── README.md        # Documentation and live preview

---

## 💻 Run Locally

To test or modify the source code on your local computer:

1. Clone this repository:
   ```bash
   git clone [https://github.com/Poulami06/Simon-Say-Game.git](https://github.com/Poulami06/Simon-Say-Game.git)

---

```bash
git add README.md
git commit -m "docs: streamline run locally steps"
git push origin main
