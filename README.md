# Chrome Dino: Asteroid Strike

A web-based, single-file arcade game that puts a space-shooter twist on the classic Chrome Dinosaur. In this game, players control a pixelated ship at the bottom of the screen, moving side-to-side and shooting to defend against an endless barrage of falling dinosaurs. 

---

## Features

*   **Retro Interface:** The game is housed in a custom, mobile-friendly device shell featuring an on-screen D-pad and a prominent "A" action button. 
*   **Dynamic Difficulty Scaling:** The game levels up automatically based on both your score and your survival time, gradually increasing enemy speeds and spawn rates.
*   **Enemy Variants:**
    *   *Standard Dino:* Moves steadily down the screen, takes 1 hit to destroy, and awards 10 points. At higher levels (level 4+), they may move erratically side-to-side.
    *   *Big Dino (Boss):* Spawns occasionally from level 3 onward, requires 3 hits to destroy (indicated by health pips), and awards 50 points.
*   **Visual Flair:** Features a scrolling dotted background, a flashing level-up indicator, and comic-style "BOOM!" and "KABOOM!" starburst effects when enemies are destroyed.
*   **Interactive Game Over:** If a dinosaur hits the player or reaches the bottom of the screen, the game ends and a custom graphic of a smug, winking dinosaur appears alongside randomized taunts like "SKILL ISSUE." or "EASY CLAP.".

---

## Controls

The game supports both physical keyboard inputs and on-screen touch/click controls.

| Action | Keyboard Input | On-Screen UI |
| :--- | :--- | :--- |
| **Move Left** | `Left Arrow`| D-Pad `◀`|
| **Move Right** | `Right Arrow`| D-Pad `▶`|
| **Shoot / Start** | `Spacebar`| `A` Button|
| **Pause Game** | N/A | `PAUSE` Button (Blue)|
| **Reset Game** | N/A | `RESET` Button (Yellow)|

> **Note:** You can also use the pink on-screen `START` button to begin a new game.

---

## Setup and Installation

Because this game relies entirely on standard web technologies (HTML5 Canvas, vanilla JavaScript, and CSS3) bundled into a single file, there are no dependencies or build steps required.

1. Save the source code into a new file named `index.html` (or any name you prefer with an `.html` extension).
2. Double-click the file to open it in a modern web browser.
3. Press **Start**, **Spacebar**, or the **A** button to begin playing.
