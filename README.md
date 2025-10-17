# CyDash - 3D Cyber Security Endless Runner

CyDash is a fast-paced, 3D endless runner game set in a futuristic cybersecurity world. As a cyber agent, your mission is to navigate through digital trenches, collect valuable data cubes, and avoid malicious obstacles like firewalls and malware. The game features dynamic difficulty, unlockable ships, daily missions, and a local leaderboard to track the top agents.

This project was built to be a fun, visually engaging web-based game that runs smoothly on both desktop and mobile devices.

## Gameplay & Features

### The Objective
The goal is simple: survive as long as you can while navigating through an ever-accelerating digital tunnel. Collect blue "data cubes" to increase your score and climb the leaderboard.

### Controls
The game is designed with responsive controls for a seamless experience on any device:

* **Desktop:** Use the `A`/`D` keys or the `Left`/`Right` arrow keys to switch between the three lanes.
* **Mobile:** Simply swipe left or swipe right anywhere on the screen to change lanes.

### Core Features
* **Dynamic Progression:** The game starts at a manageable pace and gradually increases in speed. The visual theme of the "trench" also changes as you collect more data cubes, transitioning through different zones like the "Encrypted Stream" and "Core Processor."
* **Obstacles & Power-ups:**
    * **Avoid:** Deadly red firewalls, rotating malware, and glitch mines that disrupt your view.
    * **Collect:** Grab power-ups to gain a temporary advantage:
        * 🛡️ **Shield:** Become invincible for a short period.
        * 🧲 **Magnet:** Automatically pull in nearby data cubes.
        * ⏳ **Slow-Mo:** Temporarily slow down the game's speed.
* **Ship Unlocks:** Achieve certain milestones (like reaching a cumulative score or surviving for a specific duration) to unlock new ship skins, including 'Stealth', 'Gladiator', and 'Gold' variants.
* **Daily Bounties:** Check in each day for a new mission, such as collecting a certain number of cubes or using a specific power-up. Completing the bounty grants a significant score bonus on your next run.
* **Leaderboard:** The game saves the top 10 scores, allowing you to compete against yourself and others.

## Technical Stack
CyDash is built entirely with web-native technologies and is contained within a single HTML file for maximum portability.

* **Graphics Engine:** **Three.js** is used for all 3D rendering, including the player ship, obstacles, and the dynamic environment.
* **Audio Engine:** **Tone.js** provides the web audio framework for creating the game's sound effects and background music loop.
* **Styling:** **Tailwind CSS** is used for creating the modern, responsive UI overlays and menus.
* **Core Technologies:** The game is built with **HTML5**, **CSS3**, and modern **JavaScript (ES Modules)**.

## How to Play
Since the game is a self-contained application, running it is incredibly simple:

* Visit cydash.netlify.app!
