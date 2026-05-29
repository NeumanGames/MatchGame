# 🃏 Memory Match! — NeumanGames™

A **free, browser-based memory card game** designed for preschoolers and early learners. Match pairs of cards to build memory skills while learning numbers, letters, colors, and shapes — all in a playful, screen-friendly format.

🌐 **Live Game:** [memorymatch.neumangames.com](https://memorymatch.neumangames.com)
📦 **Repository:** [github.com/NeumanGames/MemoryMatch](https://github.com/NeumanGames/MemoryMatch)

-----

## ✨ Features

### 🎮 Four Learning Categories

|Category     |Description                                                                                            |
|-------------|-------------------------------------------------------------------------------------------------------|
|🔢 **Numbers**|Cards show the *count* of themed emoji icons (e.g., the “5” card shows five 🌈). Numbers 1–24 supported.|
|🔤 **Letters**|Each card shows the capital letter, a matching emoji, and the full word (e.g., **H · 🐴 · Horse**).     |
|🎨 **Colors** |Cards use the actual color as the background, paired with a matching emoji and color name.             |
|⭐ **Shapes** |Shape emoji cards with the shape name label.                                                           |

### 🌟 Six Difficulty Levels

|Level|Name        |Cards              |
|-----|------------|-------------------|
|1    |🌱 Seedling  |6 cards (3 pairs)  |
|2    |🐣 Hatchling |12 cards (6 pairs) |
|3    |🦊 Explorer  |16 cards (8 pairs) |
|4    |🚀 Adventurer|20 cards (10 pairs)|
|5    |🏆 Champion  |24 cards (12 pairs)|
|6    |💥 EXTREME!  |48 cards (24 pairs)|

### 👥 Multiplayer Support

- **1 to 4 players** with custom names and color-coded score cards
- Turn-based play: miss a pair and the turn passes to the next player
- Match a pair: keep your turn and score a point
- Final win screen ranks all players by matches found

### 🃏 Card Mechanics

- Smooth **3D flip animation** on card reveal
- Matched pairs play a satisfying **pop animation**, then collapse off the board
- Mismatched cards **shake** and flip back face-down
- Cards are randomly shuffled each game

### 🧭 In-Game Controls

- **❓ Help button** — opens a friendly how-to-play modal
- **🏠 Home button** — opens the game menu (Resume, Restart, New Game)
- **Footer buttons** — How to Play, Ko-fi Donate, Join Patreon

-----

## 🚀 Getting Started

No build tools, no dependencies, no installation needed.

### Play Instantly

Open `index.html` in any modern web browser.

### Deploy to GitHub Pages

1. Fork or clone this repository
1. Go to **Settings → Pages**
1. Set Source to **Deploy from branch → `main` → `/ (root)`**
1. Your game will be live at `https://yourusername.github.io/MemoryMatch`

### Custom Domain

Add a `CNAME` file to the repo root with your domain (e.g., `memorymatch.neumangames.com`) and configure your DNS to point to GitHub Pages.

-----

## 📁 Project Structure

```
MemoryMatch/
├── index.html     # Complete game — all HTML, CSS, and JS in one file
└── README.md      # This file
```

The entire game is self-contained in a single `index.html` file with no external dependencies beyond Google Fonts (loaded via CDN). It works fully offline if fonts are cached.

-----

## 🎨 Design

- **Font:** [Fredoka One](https://fonts.google.com/specimen/Fredoka+One) (display) + [Nunito](https://fonts.google.com/specimen/Nunito) (body)
- **Style:** Soft cream background, bright saturated colors, chunky rounded cards, playful emoji illustrations
- **Responsive:** Adapts card grid layout and sizes for any screen width
- **No frameworks:** Pure HTML5, CSS3, and vanilla JavaScript

-----

## 📚 Learning Goals

|Category|Skills Practiced                                               |
|--------|---------------------------------------------------------------|
|Numbers |Counting, number recognition, quantity association             |
|Letters |Letter recognition, phonics, vocabulary (letter → word → image)|
|Colors  |Color naming, visual matching                                  |
|Shapes  |Shape naming, visual pattern recognition                       |

Memory Match also builds:

- **Working memory** — remembering card positions
- **Concentration** — sustained attention across turns
- **Turn-taking** — social skills in multiplayer mode

-----

## 💛 Support NeumanGames

Memory Match is completely **free to play, always**. If you’d like to support development:

- ☕ **Ko-fi:** [ko-fi.com/neumangames](https://ko-fi.com/neumangames)
- 🎗 **Patreon:** [patreon.com/NeumanGames](https://patreon.com/NeumanGames)

-----

## 🔗 Other NeumanGames Projects

|Game              |URL                                                                   |Description                                     |
|------------------|----------------------------------------------------------------------|------------------------------------------------|
|🐍 Learn & Slither!|[snakegame.neumangames.com](https://snakegame.neumangames.com)        |Preschool Snake game — numbers, letters & shapes|
|🗺️ USA Explorer    |[usaexplorer.neumangames.com](https://usaexplorer.neumangames.com)    |Interactive US geography quiz                   |
|🌍 World Explorer  |[worldexplorer.neumangames.com](https://worldexplorer.neumangames.com)|World geography learning game                   |

-----

## 📄 License

Free to play. © 2024–2025 NeumanGames™  
Made with ❤️ by Tom & Shia Neuman.