# 🪙 12 Coins Logic Puzzle

A modern, interactive implementation of the classic 12 coins logic puzzle built with React and Tailwind CSS. Can you find the fake coin in 3 weighings or fewer?

[![Live Demo](https://img.shields.io/badge/Live%20Demo-12coins.netlify.app-blue?style=for-the-badge)](https://12coins.netlify.app)

## 🎯 About The Puzzle

Among 12 identical-looking coins, exactly **one has a different weight** (it could be either lighter or heavier than the others). Your mission is to identify the fake coin using a balance scale in **3 weighings or fewer**.

This is a classic logic puzzle that tests your deductive reasoning and strategic thinking. With 12 coins and an unknown weight direction, there are 24 possible scenarios - but with the right strategy, you can solve it every time!

## ✨ Features

### 🎮 Realistic Physics Simulation
- **Authentic Balance Scale**: Realistic tilt mechanics with binary physics (full tilt or balanced)
- **Real-time Response**: Immediate visual feedback when coins are placed
- **Smooth Animations**: Coin dropping animations and scale oscillation effects

### 🔒 Advanced Latch Mechanism
- **Turn-based System**: Red latch locks scale during setup, green latch shows results
- **Measurement Control**: Arrange coins without premature reveals
- **Visual Feedback**: Animated latch engagement and release

### 📱 Responsive Design
- **Mobile-First**: Fully responsive design that works on all devices
- **Adaptive Scaling**: Balance scale resizes appropriately for different screen sizes
- **Touch-Friendly**: Optimized for both mouse and touch interactions

### 🎨 Modern UI/UX
- **Drag & Drop Interface**: Intuitive coin-by-coin dragging between all areas
- **Clean Design**: Minimalistic professional aesthetic
- **Visual Hierarchy**: Clear separation of game areas and instructions
- **Smart Sorting**: Coins automatically sort 1-12 when returned to available area

### 🧠 Educational Value
- **No Hints**: Pure physics observation without strategic guidance
- **Clean Rules**: Comprehensive sidebar with game instructions
- **Real Learning**: Develop logical thinking and problem-solving skills

## 🚀 How to Play

### Setup Phase (🔒 Red Latch)
1. Drag coins from the available area to the left and right pans
2. Arrange your coins without seeing the scale result
3. Click "Release Latch & Measure" when ready

### Measurement Phase (🔓 Green Latch)
1. Observe the scale tilt direction (or balanced state)
2. Coins are locked during measurement for fair play
3. Click "Ready for Next Turn" to continue

### Final Selection
1. Drag your suspected fake coin to the purple selection shelf
2. Click "Submit as Fake" to make your final guess
3. Win by finding the correct coin in 3 weighings or fewer!

## 🛠️ Technical Stack

- **Frontend**: React 18 with Hooks
- **Styling**: Tailwind CSS with custom animations
- **Build**: Babel for JSX compilation
- **Deployment**: Netlify with automatic builds
- **No Backend Required**: Pure client-side implementation

## 📁 Project Structure

```
12coins/
├── index.html          # Single-file React application
├── README.md           # Project documentation
└── .gitignore         # Git ignore patterns
```

## 🎯 Game Logic

The puzzle uses **information theory** principles:
- **24 Possibilities**: 12 coins × 2 weight directions (lighter/heavier)
- **3 Weighings Maximum**: Each weighing provides ternary information (left, right, balanced)
- **Optimal Strategy**: Systematic elimination through strategic grouping

### Physics Implementation
- **Binary Tilt System**: Scales show full 25° tilt or remain balanced
- **Weight Calculation**: Fake coin weighs 0.9 (lighter) or 1.1 (heavier) vs normal 1.0
- **Immediate Response**: React useEffect hooks ensure instant physics updates

## 🔧 Development

### Local Setup
```bash
# Clone the repository
git clone https://github.com/yourusername/12coins.git
cd 12coins

# Open in browser
open index.html
```

### Key Components
- **State Management**: React hooks for game state, coin positions, and physics
- **Drag & Drop**: HTML5 Drag and Drop API with visual feedback
- **Physics Engine**: Custom balance scale calculation with latch mechanism
- **Responsive CSS**: Media queries for mobile, tablet, and desktop

### Performance Features
- **Minimal Dependencies**: Only React, ReactDOM, Babel, and Tailwind CSS
- **Single File**: No build process required for development
- **Optimized Rendering**: Efficient state updates and re-renders
- **Smooth Animations**: CSS transforms and transitions for 60fps performance

## 🎨 Design Principles

### User Experience
- **Intuitive Interface**: Natural drag-and-drop interactions
- **Clear Feedback**: Visual cues for all game states
- **Progressive Disclosure**: Information revealed at appropriate times
- **Error Prevention**: UI prevents invalid actions during measurement phase

### Visual Design
- **Professional Aesthetic**: Clean, minimalistic design
- **Consistent Theming**: Cohesive color scheme throughout
- **Accessibility**: High contrast ratios and clear typography
- **Mobile Optimization**: Touch-friendly targets and responsive layout

## 🚀 Deployment

### Netlify Deployment
1. Connected to GitHub repository
2. Automatic builds on push to main branch
3. Custom domain: `12coins.netlify.app`
4. HTTPS enabled by default

### Build Optimization
- **Minification**: HTML, CSS, and JavaScript optimized
- **CDN Delivery**: Global content distribution
- **Cache Headers**: Optimal caching strategy
- **Mobile Performance**: Lighthouse score optimization

## 🤝 Contributing

Contributions are welcome! Please feel free to submit issues and pull requests.

### Areas for Enhancement
- **Sound Effects**: Audio feedback for interactions
- **Animations**: Enhanced visual transitions
- **Statistics**: Win rate and attempt tracking
- **Themes**: Dark mode and color variants
- **Tutorials**: Interactive strategy guides

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Classic 12 coins puzzle from mathematical recreation literature
- React team for the excellent framework
- Tailwind CSS for the utility-first styling approach
- Netlify for seamless deployment and hosting

---

**Ready to test your logic?** [Play the 12 Coins Puzzle →](https://12coins.netlify.app)

*Can you solve it in 3 weighings? The challenge awaits!* 🪙⚖️🧠