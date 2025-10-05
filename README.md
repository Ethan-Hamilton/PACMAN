<div align="center">

# PACMAN

<img src="favicon.ico" alt="Pacman Favicon" width="64" height="64">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**A classic arcade game reimagined with modern web technologies!**

[🎮 Play Now](https://ethan-hamilton.github.io/PACMAN/) • [Features](#-features) • [Controls](#-controls) • [Installation](#-installation)

</div>

---

## 📖 About

Experience the nostalgic thrill of **Pacman** right in your browser! This HTML5 Canvas implementation brings the classic arcade game to life with smooth animations, responsive controls, and customizable features. Navigate through the maze, eat dots, avoid ghosts, and chase high scores!

## ✨ Features

### 🎨 **Customization**
- 🎨 **Custom Colors** - Change wall and Pacman colors to your preference
- 🔊 **Sound Controls** - Toggle sound effects on/off
- 💾 **Persistent Settings** - Your preferences are saved using localStorage

### 🎮 **Gameplay**
- 👻 **4 Unique Ghosts** - Each with their own AI behavior
- 🍒 **Classic Mechanics** - Power pills, scoring system, and multiple levels
- 📱 **Touch Support** - Play on mobile with intuitive swipe controls
- ⌨️ **Keyboard Controls** - Smooth arrow key navigation
- 🎯 **Progressive Difficulty** - Game gets harder as you advance

### 🖥️ **Technical**
- 🚀 **Pure JavaScript** - No heavy frameworks, just optimized vanilla JS
- 📐 **HTML5 Canvas** - Smooth 30 FPS rendering
- 💻 **Cross-Browser** - Works on 97% of browsers (Chrome, Firefox, Safari, Edge)
- 📱 **Responsive Design** - Playable on desktop, tablet, and mobile
- 🎵 **Audio Support** - Classic Pacman sound effects (OGG/MP3 fallback)

## 🎯 Controls

### 🖱️ Desktop
| Key | Action |
|-----|--------|
| **Arrow Keys** | Move Pacman (↑ ↓ ← →) |
| **P** | Pause/Resume Game |
| **S** | Toggle Sound |
| **H** | Return to Home Menu |

### 📱 Mobile
| Gesture | Action |
|---------|--------|
| **Swipe Up** | Move Pacman Up |
| **Swipe Down** | Move Pacman Down |
| **Swipe Left** | Move Pacman Left |
| **Swipe Right** | Move Pacman Right |
| **Tap** | Access Game Menu |
| **Tap Burger Menu (☰)** | Open Settings/Options |

## 🚀 Quick Start

### Option 1: Play Online (Recommended)
**[🎮 Play Now - Live Demo](https://ethan-hamilton.github.io/PACMAN/)**

### Option 2: Play Locally
1. Clone this repository
2. Open `index.html` in your browser
3. Click **"LET'S GO!!!"** and start playing!

### Option 3: Local Server
```bash
# Clone the repository
git clone https://github.com/ethan-hamilton/PACMAN.git
cd PACMAN

# Start a simple HTTP server
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Node.js
npx http-server
```

Then open `http://localhost:8000` in your browser.

## 📦 Installation

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies required!

### Setup
```bash
# Clone the repository
git clone https://github.com/ethan-hamilton/PACMAN.git

# Navigate to project directory
cd PACMAN

# Open in browser
start index.html  # Windows
open index.html   # macOS
xdg-open index.html  # Linux
```

## 🎨 Customization

### Changing Colors
1. Click the **burger menu (☰)** icon
2. Select **Settings** from the menu
3. Use the color pickers to customize:
   - Wall Color
   - Pacman Color
4. Click **Reset Colours** to restore defaults

### Sound Settings
- Toggle sound using the **S** key
- Or use the **SOUND ON/OFF** button in settings

## 🏗️ Project Structure

```
pacman/
├── index.html          # Main HTML file
├── script.js           # Game logic and mechanics
├── styles.css          # Styling and animations
├── assets/
│   ├── audio/         # Sound effects (.ogg files)
│   └── fonts/         # Custom fonts (Emulogic, Pacmania)
└── README.md          # You are here!
```

## 🖼️ Visual Showcase

### 🎮 Game Icon
![Game Favicon](favicon.ico)
*Custom favicon representing the classic Pacman character*

### 🎨 Font Preview
The game uses authentic arcade fonts from the `assets/fonts/` directory:
- **Emulogic**: Classic arcade-style font for retro authenticity
- **Pacmania**: Custom Pacman-themed fonts for enhanced branding

### 🎵 Audio Files
Located in `assets/audio/` directory:
- High-quality OGG audio files for optimal web performance
- Classic sound effects that capture the original arcade experience

## 🎮 Gameplay Tips

1. **💊 Power Pills** - Eat the large dots to turn ghosts blue and vulnerable
2. **👻 Ghost AI** - Each ghost has unique behavior patterns
3. **🎯 Strategy** - Plan your route to maximize dot collection
4. **⚡ Speed** - Ghosts get faster in higher levels
5. **🏆 High Score** - Gain an extra life every 10,000 points!

## 🌐 Browser Compatibility

| Browser | Version | Status |
|---------|---------|--------|
| Chrome | 4+ | ✅ Fully Supported |
| Firefox | 3.6+ | ✅ Fully Supported |
| Safari | 4+ | ✅ Fully Supported |
| Edge | All | ✅ Fully Supported |
| Opera | 10+ | ✅ Fully Supported |
| Mobile Browsers | iOS 9+, Android 4.4+ | ✅ Fully Supported |
| IE | 11 | ⚠️ Partial Support |
| IE | ≤8 | ❌ Not Supported |

**Coverage:** ~97% of all internet users

## 🛠️ Technologies Used

- **HTML5 Canvas** - Game rendering engine
- **Vanilla JavaScript (ES5)** - Game logic and mechanics
- **CSS3** - Styling with flexbox, animations, and transitions
- **localStorage** - Persistent settings storage
- **HTML5 Audio API** - Sound effects
- **jQuery 3.6.0** - DOM manipulation
- **Modernizr** - Feature detection

## 🎵 Audio Credits

Sound effects are from the original Pac-Man arcade game by Namco.

## 🎨 Custom Assets

- **Custom Fonts**: Authentic arcade-style fonts including:
  - `Emulogic-zrEw.ttf` - Classic arcade font
  - `Pacmania.otf` & `Pacmania Italic.otf` - Custom Pacman fonts
- **Game Icon**: Custom `favicon.ico` for authentic branding
- **Sound Effects**: 
  - `pacman_beginning.ogg` - Game start sound
  - `pacman_chomp.ogg` - Eating dots sound
  - `pacman_death.ogg` - Death sound
  - `pacman_eatghost.ogg` - Eating ghost sound
  - `pacman_intermission.ogg` - Intermission music

## 📄 Font License

**Emulogic** font by Pixel Sagas (Neale Davidson)
- License: Free for personal use
- Website: [pixelsagas.com](http://www.pixelsagas.com)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is created for educational purposes. Pac-Man is a trademark of Bandai Namco Entertainment Inc.

## 🎯 Roadmap

- [ ] Add leaderboard system
- [ ] Implement multiplayer mode
- [ ] Add more maze layouts
- [ ] Create difficulty levels
- [ ] Add achievements system
- [ ] Implement save/load game state

## 🙏 Acknowledgments

- Original Pac-Man game by Toru Iwatani (Namco, 1980)
- Font by Neale Davidson / Pixel Sagas
- Sound effects from the original arcade game

---

<div align="center">

**Made with ❤️ and JavaScript**

⭐ Star this repo if you enjoyed the game!

[Report Bug](https://github.com/ethan-hamilton/PACMAN/issues) • [Request Feature](https://github.com/ethan-hamilton/PACMAN/issues)

</div>

