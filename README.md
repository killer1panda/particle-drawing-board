# 3D Particle Drawing Board

An interactive 3D particle drawing application that uses hand tracking via webcam to create stunning particle effects in real-time.

## Features

- **Hand Tracking Control** - Uses MediaPipe Hands for real-time hand detection
- **Dual Hand Support** - Draw with both hands simultaneously
- **4 Particle Modes**:
  - 🎆 **Fireworks** - Explosive particle bursts
  - 💖 **Heart** - Heart-shaped particle patterns
  - 🪐 **Ring** - Circular ring effects
  - 🌸 **Flower** - Beautiful flower patterns
- **Dynamic Colors** - Colors change based on hand position
- **3D Depth** - Particles respond to hand depth for 3D effects
- **High Performance** - Supports up to 50,000 particles

## Demo

Open `index.html` in a modern browser with webcam access to try it out!

## Requirements

- Modern web browser (Chrome, Firefox, Edge, Safari)
- Webcam
- JavaScript enabled

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/particle-drawing-board.git
   ```

2. Open `index.html` in your browser

3. Allow camera access when prompted

## Usage

| Gesture | Action |
|---------|--------|
| Point with index finger | Draw particles |
| Pinch thumb + index finger | Lift (stop drawing) |
| Show 1 finger | Fireworks mode |
| Show 2 fingers | Heart mode |
| Show 3 fingers | Ring mode |
| Show 4 fingers | Flower mode |
| Move hand left/right | Change colors |

## Technologies Used

- [Three.js](https://threejs.org/) - 3D graphics library
- [MediaPipe Hands](https://mediapipe.dev/) - Hand tracking
- HTML5 Canvas & WebGL

## Browser Support

| Browser | Support |
|---------|---------|
| Chrome | ✅ Full support |
| Firefox | ✅ Full support |
| Edge | ✅ Full support |
| Safari | ⚠️ Limited (WebGL issues possible) |

## Performance Tips

- Use good lighting for better hand tracking
- Keep your hand within the camera frame
- Close other browser tabs for better performance

## License

MIT License - feel free to use and modify!

## Acknowledgments

- [Three.js](https://threejs.org/) for 3D rendering
- [MediaPipe](https://mediapipe.dev/) for hand tracking technology
