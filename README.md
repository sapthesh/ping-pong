# 🏓 Browser Pong  
A tiny, dependency-free ping-pong game that runs in any modern browser.  
One file → double-click → play.

---

## Features
* Classic two-paddle mechanics  
* Real-time keyboard controls  
* Score tracker (first to 5 wins)  
* **AI opponent** toggle (1P / 2P)  
* Pure HTML5 Canvas + vanilla JavaScript  
* Zero build tools, zero external libraries

---

## File
Save the code as `index.html` (or `index-ai.html` for the AI version).

---

## Controls
| Action | Player 1 (left) | Player 2 (right) |
|--------|-----------------|------------------|
| Up     | W               | ↑ (Arrow Up)     |
| Down   | S               | ↓ (Arrow Down)   |

*In 1-Player mode the right paddle is AI-controlled.*

---

## How to Run
1. Copy the complete HTML snippet  
2. Paste into a new file named `index.html`  
3. Double-click the file (or open via any browser)  
4. Click **“New Game”** → serve!  

---

## Rules
* Ball speed increases slightly on every paddle hit  
* First side to reach **5 points** wins → “Game Over” banner  
* Press **“New Game”** anytime to restart

---

## Customising
* Paddle size: change `paddleHeight` (line ~15)  
* Ball speed: tweak `vx`/`vy` initial values (line ~18)  
* Win target: replace `5` in `checkWin()` (line ~95)  
* AI difficulty: adjust `aiSpeed` (line ~16) – bigger = harder

---

## License
Public domain / CC-0 – do whatever you want.
