# PumpKingGame
# PumpKingGame

An **HTML5 arcade game** featuring a **Pumpking** that collects crowns, avoids coins, and dodges rugs – all represented by emojis during MVP development. Once complete, the emojis will be replaced with custom artwork.

## Table of Contents

- [Overview](#overview)
- [Gameplay](#gameplay)
- [Installation](#installation)
- [Playing on GitHub Pages](#playing-on-github-pages)
- [Folder Structure](#folder-structure)
- [Credits](#credits)
- [License](#license)

---

## Overview

**PumpKingGame** (working title) is a quick, fun side-project where you:
1. Move left/right to collect crowns for points.
2. Avoid coins (reset your score) and rugs (cost a life).
3. Earn extra lives by collecting enough crowns and by using the special **Red Halo** mechanic.
4. Survive as long as possible!

## Gameplay

- **Lives**: Start with 6.
- **Crowns** (👑): +1 point each.
- **Coins** (♎, 🇷🇺, 💸): On collision, your score resets to **0**.
- **Rugs** (🧻): On collision, your score resets **0** and you lose **1 life**.
- **Red Halo** mechanic spawns after avoiding 69 rugs in a row.
- After **420 points**, it gets more difficult (fewer crowns, faster speeds, more frequent rugs).
- Game Over => Displays **"RUGGED AGAIN"**.

## Installation

1. **Clone** or **Download** this repository.
2. Open `index.html` in your preferred browser, or launch a local web server (e.g., `http-server .`) to run it.

```bash
git clone https://github.com/BasedCaveman/PumpKingGame.git
cd PumpKingGame

Credits
	•	Developer: Based Caveman
	•	Emojis: Provided by Unicode
	•	Inspiration: Original “Pumpkin Panic” concept, adapted to Crown Collector mechanics.

License

MIT License (example)
Copyright (c) 2023

Permission is hereby granted, free of charge, to any person obtaining a copy of this 
software and associated documentation files ...
