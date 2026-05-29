# 🃏 Memory Match! — NeumanGames™

A **free, browser-based memory card game** designed for preschoolers and early learners. Match pairs of cards to build memory skills while learning numbers, letters, colors, and shapes — all in a playful, screen-friendly format.

🌐 **Live Game:** [memorymatch.neumangames.com](https://memorymatch.neumangames.com)
📦 **Repository:** [github.com/NeumanGames/MemoryMatch](https://github.com/NeumanGames/MemoryMatch)

-----

## ✨ Features

### 🎮 Four Learning Categories

|Category     |Description                                                                                                              |
|-------------|-------------------------------------------------------------------------------------------------------------------------|
|🔢 **Numbers**|Cards show the *count* of themed emoji icons (e.g., the “5” card shows five 🌈). Numbers 1–24 supported.                  |
|🔤 **Letters**|Each card shows the capital letter, a matching emoji, and the full word (e.g., **H · 🐴 · Horse**). Letters A–X supported.|
|🎨 **Colors** |Cards use the actual color as the background, paired with a matching emoji and color name. 24 colors supported.          |
|⭐ **Shapes** |Shape emoji cards with the shape name label. 24 shapes supported.                                                        |

### 🌟 Six Difficulty Levels

|Level|Name        |Cards   |Pairs   |
|-----|------------|--------|--------|
|1    |🌱 Seedling  |6 cards |3 pairs |
|2    |🐣 Hatchling |12 cards|6 pairs |
|3    |🦊 Explorer  |16 cards|8 pairs |
|4    |🚀 Adventurer|20 cards|10 pairs|
|5    |🏆 Champion  |24 cards|12 pairs|
|6    |💥 EXTREME!  |48 cards|24 pairs|

### 📐 Three Card Sizes

|Size        |Description                                                           |
|------------|----------------------------------------------------------------------|
|🔹 **Small** |More cards visible at once; ideal for higher levels and larger screens|
|🔶 **Medium**|Balanced default; works well across all levels and screen sizes       |
|🔷 **Large** |Easier to tap; best for younger children and lower levels             |

Card size can be selected on the setup screen and changed at any time during gameplay using the **S · M · L** toggle in the game toolbar.

### 📱 Fully Responsive Layout

- Cards are automatically sized to fit the visible screen — no scrolling required
- Card dimensions are calculated from both the available width **and** height of the viewport, choosing whichever constraint is tighter
- The footer always snaps immediately below the game content: it never floats away when cards are small, and never overlaps when cards are large
- Grid re-renders automatically when the window is resized
- Tested across mobile, tablet, and desktop screen sizes

### 👥 Multiplayer Support

- **1 to 4 players** with customizable names and color-coded score cards
- Turn-based play: miss a pair and the turn passes to the next player
- Match a pair: keep your turn and earn a point
- Win screen ranks all players by matches found, with a gold medal for the winner

### 🃏 Card Mechanics

- Smooth **3D flip animation** on card reveal
- Matched pairs play a satisfying **pop animation**, then collapse off the board
- Mismatched cards **shake** and flip back face-down
- Cards are randomly shuffled each game

### 🧭 In-Game Controls

|Control                          |Location        |Function                                                                                 |
|---------------------------------|----------------|-----------------------------------------------------------------------------------------|
|**❓ How do the options work?**   |Setup screen    |Opens the **Game Options** summary — explains categories, levels, card sizes, and players|
|**❓ Help** button                |Game toolbar    |Opens the **How to Play** summary — explains flipping, matching, scoring, and card size  |
|**❓ How to Play** (menu item)    |Home menu       |Same gameplay summary, accessible without leaving the menu                               |
|**📖 Full Instructions on GitHub**|Both help modals|Opens the full README on GitHub in a new tab                                             |
|**S · M · L** toggle             |Game toolbar    |Resize cards without restarting                                                          |
|**🏠 Home** button                |Game toolbar    |Opens the game menu (Resume, Restart, New Game, Help)                                    |
|Footer **How to Play**           |All screens     |Context-sensitive: shows Game Options on setup/win, How to Play during gameplay          |
|Footer **Donate / Patreon**      |All screens     |Support NeumanGames                                                                      |

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
- **Responsive:** Cards auto-size to fit both width and height of the viewport; layout adjusts for any screen
- **No frameworks:** Pure HTML5, CSS3, and vanilla JavaScript

-----

## 📚 Learning Goals

|Category|Skills Practiced                                                                       |
|--------|---------------------------------------------------------------------------------------|
|Numbers |Counting, number recognition, quantity association (seeing 7 icons = understanding “7”)|
|Letters |Letter recognition, phonics, vocabulary (letter → image → word)                        |
|Colors  |Color naming, visual discrimination, color–word association                            |
|Shapes  |Shape naming, visual pattern recognition                                               |

Memory Match also builds:

- **Working memory** — holding card positions in mind across turns
- **Concentration** — sustained attention throughout the game
- **Turn-taking** — patience and social skills in multiplayer mode

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