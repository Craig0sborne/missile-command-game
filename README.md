# Missile Command Game

A modern, browser-based implementation of the classic arcade game *Missile Command*. Defend your cities from incoming enemy missiles and smart bombs using precise missile strikes, all rendered with HTML5 Canvas and enhanced with retro-futuristic visuals and sound effects.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [How to Play](#how-to-play)
- [Controls](#controls)
- [Technical Details](#technical-details)
- [License](#license)
- [Credits](#credits)

## Overview
This project recreates the iconic *Missile Command* game with a focus on nostalgic arcade aesthetics and modern JavaScript capabilities. Players protect six cities from waves of enemy missiles and smart bombs by launching defensive missiles. The game features dynamic difficulty scaling, bonus multipliers, high score tracking with player name input, and immersive audio-visual effects.

## Features
- **Retro-Futuristic Graphics**: Pixel-perfect visuals with a starry sky, nebula backdrop, and animated cities using HTML5 Canvas.
- **Dynamic Gameplay**: Increasing difficulty with each level, including faster enemies and smart bombs that evade threats.
- **High Score System**: Players can input a name (up to 10 letters) when achieving a new high score, stored in `localStorage`.
- **Sound Effects**: Custom-generated audio for missile launches, explosions, double hits, and game over events using Web Audio API.
- **Bonus System**: Earn points for remaining cities, ammo, and double hits, with a x2 multiplier every 10,000 points.
- **City Restoration**: Restore a destroyed city every 5,000 points.
- **Pause and Mute**: Toggle pause with 'P' and sound with 'M'.
- **Responsive Controls**: Mouse-based aiming and firing for intuitive gameplay.

## Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Craigosborne/missile-command.git
   
## How to Play
Objective: Protect six cities from enemy missiles and smart bombs by launching defensive missiles to intercept them.

Game Start: Click the "Start Game" button on the title screen.

Waves: Each level consists of 30 enemies. Survive the wave to earn bonuses based on remaining cities, ammo, and double hits.

Game Over: The game ends when all cities are destroyed. Your final score is compared to the high score.

High Score: If you achieve a new high score, enter a name (up to 10 letters) to be displayed on the title screen, HUD, and game over screen.

## Controls
Mouse Move: Aim the crosshair.

Left Click: Fire a defensive missile (40 ammo per level, replenished after each wave).

P: Pause/Unpause the game.

M: Toggle sound on/off.

## Technical Details
Language: JavaScript (ES6+)

Framework: None (Vanilla JavaScript)

Rendering: HTML5 Canvas for 2D graphics

Audio: Web Audio API for procedurally generated sound effects

Storage: localStorage for persisting high score and player name

Font: Google Fonts 'Orbitron' for a sci-fi aesthetic

Classes:
Star, Particle, PlayerMissile, EnemyMissile, SmartBomb, Explosion, BonusText, City, BonusMultiplierMessage

## Key Mechanics:
Collision detection for explosions and enemies

Particle systems for explosions and debris

Dynamic enemy spawning with adjustable intervals

Level progression with increasing enemy speed and smart bomb probability

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Credits
Development: Craig OSborne using Grok 3.0

Font: Orbitron by Google Fonts

Inspiration: Classic Missile Command by Atari (1980)

