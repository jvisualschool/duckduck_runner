# DUCKDUCK RUNNER

**[Demo] https://ai.jvisualschool.com/duckduck_runner/**

## 🚀 Project Overview
DUCKDUCK RUNNER is a cross-platform retro-style endless runner game inspired by the classic Chrome dinosaur game, supporting both PC and mobile devices. Play as a duck-like character, jump over cacti, duck under pterodactyls, and collect power-up items to achieve the highest score!

## ✨ Key Features
- **PC/Mobile Cross-Platform:** Works perfectly on both desktop and mobile devices.
- **Intuitive Controls:** PC uses keyboard, mobile uses touch buttons for easy operation.
- **Classic Endless Runner Gameplay:** Jump and duck to avoid obstacles.
- **Day/Night Cycle:** The game world transitions between day and night for visual variety.
- **Various Obstacles:** Encounter different types of cacti and flying pterodactyls.
- **Jump Boost Power-up:** Collect blue spring items to increase jump height by 50% for 10 seconds.
- **High Score Tracking:** Your best score is saved locally in the browser.
- **Fireworks Celebration:** Enjoy spectacular fireworks when you achieve a new high score!
- **Retro Sound Effects:** Simple sound effects for jumping, scoring, and game over.
- **Responsive Design:** Automatically adjusts to various screen sizes.
- **iPhone Optimization:** Smooth operation without screen flickering on iOS Safari.

## 🎮 How to Play

### 💻 PC (Desktop)
1.  **Open Game:** Open the `index.html` file in a web browser.
2.  **Start Game:** Press **SPACEBAR** to start the game.
3.  **Jump:** Press **SPACEBAR** to make the character jump over obstacles.
4.  **Duck:** Hold the **DOWN ARROW** key to make the character duck.
5.  **Restart:** After game over, press **SPACEBAR** to play again.

### 📱 Mobile (Smartphone/Tablet)
1.  **Open Game:** Open the `index.html` file in a mobile browser.
2.  **Start Game:** Touch the **JUMP button** or tap anywhere on the screen to start.
3.  **Jump:** Touch the **JUMP button** to make the character jump over obstacles.
4.  **Duck:** Hold the **DUCK button** to make the character duck.
5.  **Restart:** After game over, touch the **JUMP button** to play again.

### Resetting High Score
To reset your saved high score:
1.  Open the game in your browser.
2.  Right-click anywhere on the page and select "Inspect" (or "Inspect Element") to open Developer Tools.
3.  Go to the "Console" tab.
4.  Type `localStorage.removeItem('dinoHiScore');` and press Enter.
5.  Refresh the page.

## 🛠️ Technologies Used
-   **HTML5** - Game structure and canvas rendering
-   **CSS3** - Responsive design and retro styling
-   **JavaScript** - Game logic and event handling
-   **Canvas API** - 2D graphics rendering
-   **Web Audio API** - Real-time sound effect generation
-   **Touch Events** - Mobile touch support
-   **Local Storage** - High score persistence

## 🌟 Special Features
- **Cross-Platform Compatibility:** Single HTML file supports both PC and mobile
- **Flicker Fix:** Complete solution for screen flickering issues on iOS Safari
- **Hold-to-Duck Action:** DUCK button and down arrow key work while held down
- **Multi-Input Support:** Supports keyboard, mouse, and touch events
- **Auto-Scaling:** Game screen automatically adjusts to various screen sizes

## 📜 License
This project is open source and available under the [MIT License](LICENSE). (Note: A `LICENSE` file is not included in this response, but you may want to create one.)

## 🙏 Credits
-   Inspired by the Google Chrome Dinosaur Game.
