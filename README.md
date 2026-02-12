# You Can't Play Video Games 🎮

An interactive HTML5 platformer game with 6 unique levels, each featuring different themes, enemies, and animated backgrounds. Prove that you CAN play video games by collecting stars while avoiding various characters trying to stop you!

## 🎯 Game Overview

Navigate through 6 increasingly challenging levels as a man in a tuxedo (🤵), collecting stars while evading enemies. Each level features unique environments, from office settings to London's Piccadilly Circus, enchanted forests, and more!

## 🎮 How to Play

### Getting Started
1. Open `index.html` in any modern web browser
2. Click "Play Anyway" to start the game
3. Complete each level by collecting **3 stars** ⭐

### Controls
- **Arrow Keys** or **WASD**: Move left/right
- **Space Bar** / **Up Arrow** / **W**: Jump
- Get caught by enemies and you'll respawn with temporary invincibility (green glow)

### Gameplay Mechanics
- **Invincibility**: 3 seconds at level start, 2 seconds after getting caught
- **Goal**: Collect 3 out of 6 stars per level to advance
- **Enemies**: AI-controlled characters that chase and try to catch you
- **Getting Caught**: Resets your star count but you respawn immediately

## 🌟 Levels

### Level 1: You Are Separated 🏢
**Theme**: Office Environment
- **Enemies**: Police officer (👮‍♂️), Detective (🕵️), Judge (👨‍⚖️)
- **Features**: 
  - Animated printer printing documents
  - Windows, filing cabinets, office plants
  - Motivational posters
- **Platforms**: Brown office desks

### Level 2: You Are Terminated 🏗️
**Theme**: Construction Site
- **Enemies**: Police officer (👮‍♂️), Construction workers (👷‍♂️, 👷‍♀️)
- **Features**: 
  - Construction crane
  - Scaffolding
  - Traffic cones and barriers
  - Caution tape
  - Building under construction
- **Platforms**: Steel beams with rivets

### Level 3: UK Police 🇬🇧
**Theme**: London's Piccadilly Circus
- **Enemies**: Police officer (👮‍♂️), King (🤴), Queen (👸), Doctor (👨‍⚕️)
- **Features**: 
  - Animated neon billboards ("LONDON WEST END", "THEATRE DISTRICT")
  - Moving double-decker London bus
  - Red phone booth
  - Piccadilly Circus sign
  - Tall modern buildings with glowing windows
- **Platforms**: Solid brown wood

### Level 4: Witchcraft 🌙
**Theme**: Enchanted Forest at Night
- **Enemies**: Police officer (👮‍♂️), Genie (🧞‍♀️), Wizard (🧙)
- **Features**: 
  - Full moon with craters
  - Animated flying fairies with sparkles (✨)
  - Starry night sky
  - Dark forest trees
- **Platforms**: Wooden logs

### Level 5: You Are Pregnant 🎉 (BONUS)
**Theme**: Baby Shower Party
- **Enemies**: Police officer (👮‍♂️), Pregnant person (🤰), Technologist (🧑‍💻)
- **Features**: 
  - "Boy or Girl?" banner
  - Floating animated balloons (pink & blue)
  - Falling confetti animation
  - Wrapped presents
- **Platforms**: Alternating pink and blue platforms

### Level 6: Leave 🍂 (BONUS)
**Theme**: Rainy Autumn Day
- **Enemies**: Police officer (👮‍♂️), Person gesturing no (🙅‍♀️), Falling leaf (🍃)
- **Features**: 
  - Animated rainfall
  - Rotating falling leaves
  - Gray rainy clouds
  - Moody atmosphere
- **Platforms**: Dark green grass

## 🎨 Features

### Visual Effects
- Smooth animations and transitions
- Dynamic lighting and shadows
- Glow effects on billboards and neon lights
- Day/night cycles across levels
- Weather effects (rain)

### Game Mechanics
- Realistic physics (gravity, jumping, collision detection)
- Enemy AI that chases the player
- Platform collision system
- Invincibility system with visual feedback
- Score tracking
- Level progression system

### Audio-Visual Design
- Animated backgrounds for each level
- Emoji-based characters
- Gradient backgrounds
- Smooth character movements
- Level transition screens
- Win screen celebration

## 🛠️ Technical Details

### Technologies Used
- **HTML5 Canvas**: For game rendering
- **Vanilla JavaScript**: Game logic and animations
- **CSS3**: Styling and UI animations
- **No external libraries required**: Fully standalone

### Browser Compatibility
- Chrome (Recommended)
- Firefox
- Safari
- Edge
- Any modern browser with HTML5 Canvas support

### Performance
- Optimized rendering for 60 FPS
- Efficient collision detection
- Minimal memory footprint
- Reduced particle counts for smoother performance

## 📋 Game Statistics

- **Total Levels**: 6
- **Stars per Level**: 6 (collect 3 to advance)
- **Enemy Types**: 12 unique characters
- **Animated Elements**: 
  - Printer animation (Level 1)
  - London bus (Level 3)
  - Fairies (Level 4)
  - Balloons & confetti (Level 5)
  - Rain & falling leaves (Level 6)
  - Billboards (Level 3)

## 🎯 Tips & Strategies

1. **Use invincibility wisely**: You spawn with 3 seconds of protection
2. **Plan your route**: Not all 6 stars are needed, choose the easiest 3
3. **Jump timing**: Master the jump mechanics to avoid enemies
4. **Enemy patterns**: Learn enemy movement to predict their paths
5. **Platform advantage**: Use higher platforms to avoid ground enemies
6. **Speed matters**: Your character is faster than most enemies

## 🏆 Winning the Game

Complete all 6 levels by collecting 3 stars in each level. Upon completing Level 6, you'll see the victory screen:

**"🎉 YOU WON! 🎉"**  
**"You completed all 6 levels!"**  
**"You CAN play video games! 🎮"**

Click "Play Again" to restart from Level 1.

## 📱 Installation

No installation required! Simply:

1. Download the `index.html` file
2. Open it in your web browser
3. Start playing!

## 🎮 Development

### File Structure
```
index.html          # Complete game (standalone file)
README.md          # This file
```

### Customization
The game is fully contained in a single HTML file, making it easy to:
- Modify level designs
- Add new enemies
- Adjust difficulty (enemy speed, jump power)
- Change themes and colors
- Add more levels

### Key Variables to Modify
```javascript
// Player stats
speed: 5           // Movement speed
jumpPower: 11      // Jump height
gravity: 0.4       // Fall speed

// Enemy stats (per level)
speed: 0.7-1.5     // Chase speed
jumpPower: 4-8     // Jump height
```

## 🐛 Known Issues

None currently reported. Please report any bugs you encounter!

## 📄 License

This project is free to use and modify for personal and educational purposes.

## 🤝 Contributing

Feel free to fork, modify, and enhance this game! Some ideas:
- Add sound effects and music
- Create new levels
- Add power-ups
- Implement a scoring system with time bonuses
- Add difficulty levels
- Create mobile touch controls

## 🎉 Credits

**Game Design & Development**: Created as a fun, interactive browser-based platformer

**Emoji Graphics**: Unicode emoji characters

**Theme Inspiration**: Various life situations turned into playful game levels

---

**Enjoy the game and remember: You CAN play video games!** 🎮✨

*Version 1.0 - Fully playable with 6 unique levels*
