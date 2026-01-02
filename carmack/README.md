# 🔥 CATACOMB 3D - A Tribute to John Carmack

![Catacomb 3D Banner](https://img.shields.io/badge/TRIBUTE-John%20Carmack-ff6600?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0iI2ZmZiIgZD0iTTEyIDJMMyAyMGgyMEwxMiAyeiIvPjwvc3ZnPg==)
![Three.js](https://img.shields.io/badge/Three.js-r128-black?style=for-the-badge&logo=three.js)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

> *"Story in a game is like a story in a porn movie. It's expected to be there, but it's not that important."* — John Carmack

A modern WebGL recreation of the classic **Catacomb 3D** (1991), the groundbreaking first-person shooter that pioneered the genre and laid the foundation for Wolfenstein 3D and DOOM.

## 🎮 Play Now

Simply open `catacomb3d.html` in any modern web browser. No installation required!

**[▶️ CLICK TO PLAY](./catacomb3d.html)**

---

## 📜 The Legend

**Catacomb 3D** was released in 1991 by Softdisk, created by the legendary **John Carmack** with John Romero and Adrian Carmack. It was one of the first games to feature:

- **Texture-mapped 3D environments** using raycasting
- **First-person shooter** gameplay mechanics
- **Real-time combat** in a 3D space

This game directly evolved into **Wolfenstein 3D** (1992) and ultimately **DOOM** (1993), changing video games forever.

---

## ✨ Features

### 🏰 Authentic Dungeon Atmosphere
- Procedurally textured stone walls, floors, and ceilings
- Dynamic torch lighting with realistic flickering
- Atmospheric fog for depth and mystery
- Dark, foreboding catacomb environment

### 👹 Combat System
- **Fireball casting** with mana management
- **Skeleton enemies** with AI pathfinding
- **Health and mana pickups** scattered throughout
- Real-time combat with damage feedback

### 🗺️ Navigation
- **Real-time minimap** showing:
  - Wall layouts
  - Enemy positions (red dots)
  - Pickup locations (colored dots)
  - Player position and direction
- Fog-of-war style exploration

### 🎯 Controls

| Action | Key/Input |
|--------|-----------|
| Move Forward | `W` / `↑` |
| Move Backward | `S` / `↓` |
| Strafe Left | `A` |
| Strafe Right | `D` |
| Look Around | Mouse |
| Cast Fireball | Left Click |
| Sprint | `Shift` |
| Pause | `Esc` |

### 📊 HUD Elements
- **Health Bar** - Your life force
- **Mana Bar** - Regenerates over time
- **Score** - Points from kills and pickups
- **Level** - Current dungeon level
- **Kill Counter** - Enemies vanquished

---

## 🛠️ Technical Details

### Built With
- **Three.js r128** - WebGL 3D graphics library
- **Vanilla JavaScript** - No frameworks, pure performance
- **Canvas API** - For procedural textures and minimap
- **CSS3** - Retro-styled UI with modern effects

### Architecture
```
catacomb3d.html
├── CSS Styles (embedded)
│   ├── Retro UI styling
│   ├── HUD components
│   └── Animations & effects
│
├── Three.js Scene
│   ├── Procedural textures (walls, floor, ceiling)
│   ├── Dynamic lighting (torches)
│   ├── Enemy entities (skeletons)
│   ├── Projectile system (fireballs)
│   └── Pickup items (potions)
│
└── Game Systems
    ├── First-person camera controls
    ├── Collision detection
    ├── Enemy AI (chase, attack)
    ├── Minimap rendering
    └── Game state management
```

### Map Format
The dungeon uses a simple 2D array:
```javascript
// 0 = empty space
// 1 = wall
// 2 = torch spawn
// 3 = enemy spawn
// 4 = pickup spawn
```

---

## 🎨 Screenshots

```
    ╔═══════════════════════════════════════╗
    ║                                       ║
    ║     ▓▓▓▓     CATACOMB 3D     ▓▓▓▓    ║
    ║     ▓▓▓▓                     ▓▓▓▓    ║
    ║     ▓▓▓▓   ~~~~ FIRE ~~~~    ▓▓▓▓    ║
    ║     ▓▓▓▓        🔥           ▓▓▓▓    ║
    ║                                       ║
    ║  ████████████████████████████████    ║
    ╠═══════════════════════════════════════╣
    ║ HEALTH [████████░░]  MANA [██████░░]  ║
    ║ SCORE: 1250    LEVEL: 1    KILLS: 5   ║
    ╚═══════════════════════════════════════╝
```

---

## 🚀 Getting Started

### Quick Start
1. Download or clone this repository
2. Open `catacomb3d.html` in your browser
3. Click "ENTER THE CATACOMBS"
4. Survive!

### Local Development
```bash
# Clone the repository
git clone https://github.com/yourusername/catacomb3d-tribute.git

# Navigate to directory
cd catacomb3d-tribute

# Open in browser (or use any local server)
open catacomb3d.html

# Or with Python
python -m http.server 8080
# Then visit http://localhost:8080/catacomb3d.html
```

---

## 📈 Future Enhancements

- [ ] Multiple dungeon levels with progression
- [ ] More enemy types (demons, ghosts, mages)
- [ ] Additional weapons/spells
- [ ] Secret rooms and treasure
- [ ] Boss battles
- [ ] Sound effects and music
- [ ] Mobile touch controls
- [ ] Leaderboard system
- [ ] Level editor

---

## 🙏 Credits

### Original Game
- **John Carmack** - Programming genius, engine creator
- **John Romero** - Game design
- **Adrian Carmack** - Art direction (no relation to John)
- **Softdisk Publishing** - Original publisher (1991)

### This Tribute
- **Built by Claude AI** - Anthropic's AI assistant
- **Powered by Three.js** - The amazing WebGL library
- **Inspired by the legends** who changed gaming forever

---

## 📄 License

MIT License - Feel free to use, modify, and distribute!

---

## 🎮 Fun Facts About Catacomb 3D

1. **First of its kind** - It was the first texture-mapped, first-person shooter
2. **Raycasting pioneer** - John Carmack's raycasting engine was revolutionary
3. **16 colors** - The original ran in EGA 16-color mode
4. **Foundation for DOOM** - The tech evolved directly into id Software's legendary games
5. **Open source legacy** - Carmack later open-sourced the DOOM and Quake engines

---

<div align="center">

### 🔥 *"In the information age, the barriers to entry into programming have become almost non-existent."* 
### — John Carmack

---

**Made with ❤️ as a tribute to the pioneers of 3D gaming**

*This is a fan project and is not affiliated with John Carmack, id Software, or any original rights holders.*

</div>
