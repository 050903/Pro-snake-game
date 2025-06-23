# 🐍 Pro Snake - Enhanced Edition

A professional-grade Snake game built with Python and Pygame, featuring smooth animations, customizable themes, particle effects, and a polished user interface.

![Python](https://img.shields.io/badge/Python-3.7+-blue.svg)
![Pygame](https://img.shields.io/badge/Pygame-2.0+-green.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)

## ✨ Features

### 🎮 Core Gameplay
- **Wall Wrapping**: Snake teleports through walls instead of dying
- **Lives System**: 3 lives with visual heart display
- **Progressive Difficulty**: Speed increases every 5 foods eaten
- **High Score Tracking**: Persistent best score display
- **Directional Snake Head**: Eyes and nose face movement direction

### 🎨 Visual Excellence
- **5 Snake Themes**: Classic, Fire, Ice, Gold, and Neon color schemes
- **Smooth Movement**: 60 FPS interpolated animations
- **Particle Effects**: Explosive effects when eating food
- **Professional UI**: Clean, modern interface with organized layout
- **Glowing Food**: Multi-layer glow effects
- **Optional Grid**: Toggle background grid display

### ⚙️ Customization
- **4 Speed Settings**: Slow, Normal, Fast, and Insane modes
- **Visual Options**: Toggle grid, particles, and smooth movement
- **Theme Selection**: Live preview of snake colors
- **Tabbed Settings**: Organized Game, Visual, and Snake options

## 🚀 Installation

### Prerequisites
- Python 3.7 or higher
- Pygame library

### Setup
1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/pro-snake-game.git
   cd pro-snake-game
   ```

2. **Install dependencies**
   ```bash
   pip install pygame
   ```

3. **Run the game**
   ```bash
   python prosnake.py
   ```

## 🎮 Controls

### Main Menu
- **SPACE**: Start game
- **S**: Open settings

### Settings Menu
- **←→**: Switch between tabs (Game/Visual/Snake)
- **↑↓**: Navigate options
- **G**: Toggle grid display
- **P**: Toggle particle effects
- **M**: Toggle smooth movement
- **SPACE**: Start game with current settings
- **ESC**: Return to main menu

### Gameplay
- **Arrow Keys**: Control snake movement
- **ESC**: Return to main menu

### Game Over
- **SPACE**: Play again
- **ESC**: Return to main menu

## 🎯 Game Mechanics

### Scoring System
- **+10 points** per food eaten
- Score preserved across lives
- High score tracking

### Lives System
- Start with **3 lives** (displayed as hearts)
- Lose a life when snake hits itself
- Game over when all lives are lost
- Snake respawns at center after losing a life

### Speed Progression
- Base speed determined by settings (8-22 FPS)
- Speed increases by 1 every 5 foods eaten
- Maximum speed cap at base + 8

## 🎨 Snake Themes

| Theme | Description |
|-------|-------------|
| **Classic** | Traditional green snake |
| **Fire** | Red and orange flame colors |
| **Ice** | Cool blue and cyan tones |
| **Gold** | Luxurious golden appearance |
| **Neon** | Bright electric green |

## 🛠️ Technical Details

### Architecture
- **Object-Oriented Design**: Clean SnakeGame class structure
- **State Management**: Menu, Settings, Playing, Game Over states
- **Modular Rendering**: Separate draw methods for each component
- **Smooth Animation**: Interpolated movement system

### Performance
- **60 FPS** rendering for smooth visuals
- **Efficient Collision Detection**: Optimized algorithms
- **Particle System**: Physics-based particle effects
- **Memory Management**: Proper cleanup of game objects

## 📁 Project Structure

```
pro-snake-game/
├── prosnake.py          # Main game file
├── README.md            # This file
├── requirements.txt     # Python dependencies
└── .gitignore          # Git ignore rules
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🎯 Future Enhancements

- [ ] Sound effects and background music
- [ ] Power-ups and special foods
- [ ] Multiplayer support
- [ ] Level system with obstacles
- [ ] Leaderboard with name entry
- [ ] Save/load game settings
- [ ] Additional snake themes
- [ ] Mobile touch controls

## 🐛 Known Issues

- None currently reported

## 📞 Support

If you encounter any issues or have suggestions:
1. Check existing [Issues](https://github.com/yourusername/pro-snake-game/issues)
2. Create a new issue with detailed description
3. Include your Python and Pygame versions

## 🙏 Acknowledgments

- Built with [Pygame](https://www.pygame.org/)
- Inspired by classic Snake games
- Professional UI design principles

---

**Enjoy playing Pro Snake! 🐍✨**