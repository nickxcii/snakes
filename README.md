# 🐍 Snake Game

A modern, feature-rich implementation of the classic Snake game with power-ups, achievements, multiple themes, and mobile support.

## 🎮 Features

- **Enhanced Gameplay**: Classic snake mechanics with modern twists
- **Power-ups**: Speed boost, slow motion, ghost mode, double points, shrink, and extra life
- **Achievement System**: Unlock achievements as you play
- **Multiple Themes**: Retro, Neon, and Sunset visual themes
- **Progressive Difficulty**: Dynamic level system with increasing complexity
- **Audio System**: Background music and sound effects (8-bit style)
- **Mobile Support**: Touch controls and swipe gestures
- **High Score Tracking**: Local leaderboard system
- **Responsive Design**: Adapts to different screen sizes
- **Fullscreen Mode**: Immersive gaming experience

## 🎯 Game Controls

### Desktop
- **Arrow Keys** or **WASD**: Control snake direction
- **Spacebar**: Pause/Resume game
- **F**: Toggle fullscreen mode
- **ESC**: Pause menu

### Mobile
- **Swipe Gestures**: Control snake direction
- **Touch Controls**: On-screen directional buttons
- **Tap Center Button**: Pause/Resume

## 🚀 Live Demo

Play the game live at: [Your Render URL will be here]

## 🛠️ Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/nickxcii/snakes.git
   cd snakes
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```

4. Open your browser and navigate to `http://localhost:3000`

## 📦 Deployment on Render

This game is configured for easy deployment on Render:

1. **Fork or clone this repository** to your GitHub account

2. **Connect to Render**:
   - Go to [render.com](https://render.com)
   - Click "New +" and select "Web Service"
   - Connect your GitHub repository

3. **Configure the service**:
   - **Name**: `snake-game` (or your preferred name)
   - **Environment**: `Node`
   - **Build Command**: `npm install`
   - **Start Command**: `npm start`
   - **Instance Type**: `Free` (or higher for better performance)

4. **Deploy**: Click "Create Web Service"

Your game will be live at `https://[your-service-name].onrender.com`

## 🏗️ Project Structure

```
snakes/
├── index.html          # Main game file with HTML, CSS, and JavaScript
├── server.js           # Express server for serving static files
├── package.json        # Node.js dependencies and scripts
└── README.md          # Project documentation
```

## 🎨 Themes

The game includes three visual themes:

1. **Retro**: Classic green-on-black terminal style
2. **Neon**: Cyberpunk-inspired colors and effects  
3. **Sunset**: Warm orange and red color palette

## 🏆 Achievements

Unlock various achievements by:
- Eating your first food
- Reaching score milestones (100, 500, 1000+ points)
- Advancing to higher levels (5, 10+)
- Growing your snake to impressive lengths (20, 50+ segments)
- Mastering different gameplay mechanics

## 💫 Power-ups

Collect power-ups to gain temporary advantages:
- **⚡ Speed Boost**: Increases snake movement speed
- **🐌 Slow Motion**: Slows down time for easier navigation
- **👻 Ghost Mode**: Pass through walls and yourself
- **💎 Double Points**: Earn twice the points for food
- **📉 Shrink**: Reduces snake length by 3 segments
- **💚 Extra Life**: Bonus points (future: actual extra lives)

## 🔊 Audio

- **Background Music**: Retro 8-bit melody
- **Sound Effects**: Movement, eating, power-ups, achievements
- **Audio Controls**: Toggle music and SFX independently

## 🎮 Game Mechanics

- **Progressive Levels**: Each level introduces new wall patterns
- **Dynamic Speed**: Game speed increases with level progression  
- **Smart Collision**: Ghost mode power-up allows temporary wall/self-passing
- **Particle Effects**: Visual feedback for various game events
- **Screen Shake**: Impact feedback for collisions

## 🔧 Technical Details

- **Frontend**: Pure HTML5, CSS3, and vanilla JavaScript
- **Backend**: Node.js with Express (for deployment)
- **Canvas Rendering**: Hardware-accelerated 2D graphics
- **Local Storage**: Persistent high scores and achievements
- **Mobile Optimization**: Touch events and responsive design
- **Audio**: Web Audio API for sound generation

## 📱 Mobile Optimization

- Responsive canvas sizing
- Touch-friendly controls
- Swipe gesture recognition
- Virtual D-pad for precise control
- Optimized performance for mobile devices

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests
- Improve documentation

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🎯 Future Enhancements

- Multiplayer support
- Additional power-ups
- More visual themes
- Sound customization
- Leaderboard integration
- Social sharing features

---

**Enjoy the game!** 🐍✨