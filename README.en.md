# 🐍 Snake Game · Ultimate IE6 Compatibility

> A Snake game that runs flawlessly on Internet Explorer 6 and all modern browsers, supporting keyboard, WASD, touch swipe, on-screen buttons, and gamepad controls.

---

## ✨ Features

- **Ultimate Compatibility**: Supports IE6+, Chrome, Firefox, Edge, Safari, and all major browsers
- **Multiple Control Methods**:
  - ⌨️ **Keyboard**: Arrow keys ↑↓←→
  - ⌨️ **WASD**: W/A/S/D
  - 🖱️ **On-Screen Buttons**: Directional buttons below the game board
  - 👆 **Touch Swipe**: Swipe directly on the game area (mobile)
  - 🎮 **Gamepad**: Use left joystick or D-Pad after connecting a controller
- **Smart Food Generation**: Uses BFS (Breadth-First Search) algorithm to ensure every spawned food is reachable by the snake's head, preventing deadlocks
- **High Score Persistence**: Saves the highest score locally via Cookie
- **Visual Aid**: Semi-transparent grid lines for better positioning accuracy
- **Full DOM Rendering**: No Canvas dependency, ensuring complete IE6 compatibility

---

## 🎮 Game Rules

- Control the snake to eat the red food 🍎
- Each food eaten increases the snake's length by 1 and score by 1
- Hitting the wall or your own body ends the game
- Win condition: Fill the entire 20×20 (400 cells) board with the snake's body 🏆

---

## 💻 System Requirements

This game is designed to be extremely lightweight and runs on virtually any device with a web browser.

- **Operating Systems**: Windows 95/98/2000/XP/Vista/7/8/10/11, macOS, Linux, Android, iOS (any browser-supported system)
- **Browsers**:
  - **Minimum**: Internet Explorer 6 and above (requires script execution)
  - **Recommended**: Microsoft Edge, Google Chrome, Mozilla Firefox, Apple Safari, Opera (for better performance and touch support)
- **Screen Resolution**: 800×600 or higher recommended (game board is 400×400 pixels)
- **Memory**: At least 16 MB RAM (actual usage is much lower)
- **Other**: JavaScript must be enabled (IE6 enables it by default; if prompted with a script restriction, click "Allow blocked content")

---

## 🚀 How to Run

### Local Execution
1. Download the `贪吃蛇.html` or `贪吃蛇精简版.html` file from this repository
2. Double-click the file to open it in your browser and start playing

> **IE6 Note**: If you're using IE6, you may see a prompt saying "Internet Explorer has restricted this webpage from running scripts." Click "Allow blocked content" to play normally.


---

## 📁 Project Structure
tanchishe/
├── 贪吃蛇.html # Full game code (includes HTML/CSS/JS)
├── 贪吃蛇精简版.html # Minified version (smaller size, same features)
├── README.md # Project documentation (Chinese)
├── README.en.md # Project documentation (English)
├── LICENSE # Non-Commercial Use License v5.4
└── COMPLIANCE.md # Export Control & Data Protection Compliance Reference

All code is contained in a single file with no external dependencies — just download and run.

---

## 🛠️ Technical Implementation

- **Language**: Pure JavaScript (ECMAScript 3 syntax, IE6-compatible)
- **Rendering**: DOM manipulation (`innerHTML`), no Canvas usage
- **Algorithm**: BFS for food reachability detection
- **Event Handling**:
  - Keyboard: `document.onkeydown` (IE6-compatible)
  - Touch: `touchstart` / `touchmove` / `touchend`
  - Gamepad: `Gamepad API` (modern browsers only)
- **Data Persistence**: Cookie-based high score storage

---

## 📄 License

This project is licensed under the [Non-Commercial Use License v5.4](./LICENSE). Commercial use is strictly prohibited. For commercial licensing, please contact the author.

---

## 🤝 Contributing

Issues and Pull Requests are welcome! Help improve the game.

---

## 📧 Contact

- **Author**: WT-XDWI
- **GitHub**: [@WT-XDWI](https://github.com/WT-XDWI)

---

**Enjoy the game!** 🎉
