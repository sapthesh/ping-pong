# 🏓 Browser Pong
A tiny, dependency-free ping-pong game that runs directly in any modern web browser.

[![License: CC0-1.0](https://img.shields.io/badge/License-CC0--1.0-lightgrey.svg)](LICENSE)
[![GitHub Actions Workflow Status](https://github.com/sapthesh/ping-pong/workflows/static/badge.svg)](https://github.com/sapthesh/ping-pong/actions?query=workflow%3Astatic)

## Overview
This project presents a minimalistic and classic two-player (or one-player with AI) Ping-Pong game, fully implemented using pure HTML5 Canvas and vanilla JavaScript. Designed for simplicity and immediate play, **Browser Pong** requires no build tools, no external libraries, and runs directly from a single HTML file in any modern web browser. It's an ideal showcase for fundamental web development concepts and a fun, quick distraction for anyone seeking a classic arcade experience.

## Key Features
*   **Instant Play**: Simply double-click a single HTML file to start playing immediately.
*   **Classic Mechanics**: Experience the timeless two-paddle, bouncing ball gameplay.
*   **Responsive Controls**: Real-time keyboard input provides fluid and precise paddle movement.
*   **AI Opponent**: Play solo against an AI-controlled right paddle (available in `index-ai.html`).
*   **Score Tracking**: The first player to reach 5 points wins, triggering a "Game Over" display.
*   **Progressive Difficulty**: The ball's speed subtly increases with every paddle hit, adding challenge as the game progresses.
*   **Pure Web Technologies**: Built exclusively with HTML5 Canvas and vanilla JavaScript, ensuring zero dependencies and an extremely lightweight footprint.

## Tech Stack
*   **HTML5 Canvas**: Utilized for all game rendering, drawing paddles, the ball, and scores.
*   **Vanilla JavaScript**: Powers all game logic, including physics, collision detection, player controls, AI behavior, and score management.
*   **(Implicit) CSS**: Basic, minimal styling is handled either inline or via default browser rendering.

## Getting Started

### Prerequisites
You only need a modern web browser (e.g., Chrome, Firefox, Edge, Safari) to run this game. No other software, servers, or build tools are required.

### Installation
Since **Browser Pong** is a single-file application, there's no complex installation process.

1.  **Clone the repository (recommended for development or customization):**
    ```bash
    git clone https://github.com/sapthesh/ping-pong.git
    cd ping-pong
    ```
2.  **Alternatively, download the file directly:**
    *   Navigate to the repository on GitHub (`sapthesh/ping-pong`).
    *   Click on either `index.html` (two-player version) or `index-ai.html` (one-player with AI).
    *   Click the "Raw" button to view the raw code.
    *   Save the page (e.g., `Ctrl+S` or `Cmd+S`) as `index.html` (or `index-ai.html`) to your local machine.

## Usage
To play the game:

1.  **Open the Game File**: Locate the `index.html` or `index-ai.html` file you downloaded and double-click it. Your default web browser will open the game.
2.  **Start a New Game**: Click the "New Game" button within the browser window to initialize the ball and paddles and begin the match.
3.  **Controls**:
    | Action | Player 1 (left) | Player 2 (right) |
    |--------|-----------------|------------------|
    | Up     | `W`             | `↑` (Arrow Up)   |
    | Down   | `S`             | `↓` (Arrow Down) |

    *In 1-Player mode (using `index-ai.html`), the right paddle is AI-controlled.*

4.  **Gameplay Rules**:
    *   The ball's speed increases slightly with every paddle hit.
    *   The first side to reach **5 points** wins, displaying a "Game Over" banner.
    *   Press **"New Game"** anytime to restart the match.

## Customising
**Browser Pong** is designed to be easily modifiable. Open either `index.html` or `index-ai.html` in a text editor to tweak game parameters:

*   **Paddle Size**: Adjust the `paddleHeight` variable (around line ~15).
*   **Initial Ball Speed**: Modify `vx` and `vy` initial values (around line ~18).
*   **Win Target**: Change the score `5` in the `checkWin()` function (around line ~95).
*   **AI Difficulty**: Alter the `aiSpeed` variable (around line ~16) in `index-ai.html` – larger values make the AI harder.

## License
This project is released into the Public Domain under the [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/) (CC0-1.0) license. You are free to do whatever you want with it. See the [LICENSE](LICENSE) file for more details.
