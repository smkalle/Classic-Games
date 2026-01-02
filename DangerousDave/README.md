# 🎮 Dangerous Dave - AI Recreation

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

A faithful recreation of the classic **Dangerous Dave** (1990) platformer game, originally created by John Romero. This version is built as a single-page HTML5 application with embedded CSS and JavaScript.

## 🕹️ Play Now

Simply open `index.html` in any modern web browser - no installation required!

**[▶️ Play Online](https://smkalle.github.io/Classic-Games/DangerousDave/index.html)**

## 📸 Screenshots

```
    ████                    🏆 DANGEROUS DAVE 🏆
   ██████                   
   █▀██▀█                   Score: 2500  Level: 3  Lives: ❤❤❤
   ██████                   
    ████                    Collect the trophy to unlock the exit!
   ██████
  ████████
```

## 🎯 Gameplay

Guide Dave through **5 challenging levels** filled with gems, enemies, and hazards!

### Objective
1. **Collect gems** 💎 for points (100 pts each)
2. **Find the trophy** 🏆 to unlock the exit door (500 pts)
3. **Reach the exit** 🚪 to complete the level
4. **Avoid enemies** 👾 and spikes ⚠️

### Controls

| Action | Keyboard | Mobile |
|--------|----------|--------|
| Move Left | `←` or `A` | D-Pad Left |
| Move Right | `→` or `D` | D-Pad Right |
| Jump | `Space` or `W` or `↑` | Jump Button |

## ✨ Features

- 🎨 **Authentic DOS-era pixel art** - Procedurally drawn sprites faithful to the original
- 🖥️ **CRT scanline effect** - Nostalgic retro display simulation
- 🔊 **Retro sound effects** - Web Audio API chiptune sounds
- 📱 **Mobile responsive** - Touch controls for phones and tablets
- 🏃 **Smooth physics** - Gravity, collision detection, platform mechanics
- 👾 **Patrolling enemies** - Classic AI behavior
- ⚡ **5 unique levels** - Progressive difficulty curve
- 💾 **Zero dependencies** - Pure HTML/CSS/JavaScript

## 🛠️ Technical Details

| Component | Implementation |
|-----------|----------------|
| Rendering | HTML5 Canvas (640x480) |
| Physics | Custom gravity & tile-based collision |
| Audio | Web Audio API oscillators |
| Graphics | Procedural pixel art (32x32 tiles) |
| Frame Rate | 60 FPS via requestAnimationFrame |

## 📂 File Structure

```
DangerousDave/
├── index.html      # Complete game (single file)
└── README.md       # This file
```

## 🎮 Game Elements

### Tiles
- 🧱 **Brick walls** - Solid obstacles
- 🟫 **Ground** - Floor tiles
- ➖ **Platforms** - Jump-through surfaces
- ⚠️ **Spikes** - Instant damage hazards

### Collectibles
- 💎 **Gems** - 100 points each
- 🏆 **Trophy** - 500 points + unlocks exit

### Characters
- 🔴 **Dave** - Our hero in his signature red cap
- 👾 **Enemies** - Green patrolling monsters

## 🏆 Scoring

| Item | Points |
|------|--------|
| Gem | 100 |
| Trophy | 500 |
| Level Complete Bonus | 1,000 |

## 📜 History

**Dangerous Dave** was originally created by John Romero in 1988 and published by Softdisk in 1990. It became one of the pioneering platformers for DOS and helped establish id Software's game development legacy.

This AI recreation pays homage to the original while being completely rebuilt from scratch using modern web technologies.

## 🤝 Contributing

Feel free to submit issues and enhancement requests!

## 📄 License

This is a fan recreation for educational purposes. The original Dangerous Dave is © John Romero / Softdisk.

---

<div align="center">

**Made with ❤️ using Claude AI**

*Part of the [Classic-Games](https://github.com/smkalle/Classic-Games) collection*

</div>
