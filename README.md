# Binary Kite

Live Demo: [https://rencheng0525.github.io/BinaryKite/](https://rencheng0525.github.io/BinaryKite/)

## Overview
**Binary Kite** is a WebGL interactive visual art project built with p5.js. It features a dynamically changing 3D cube array, driven by procedural random generation and smooth motion transitions.

## Features

### Visual Effects
- **Dynamic 3D Cube Array**: A layered cube grid that continuously evolves, producing a wave-like effect.
- **Procedural Black & White Patterns**: Uses a custom linear congruential generator (LCG) for randomized black-and-white transitions.
- **Lighting Effects**: Toggleable ambient and point lighting to adjust scene depth.
- **Smooth Animations**: Uses interpolation (`lerp`) for seamless mouse tracking, rotation, and zooming.

### Interactive Controls
- **Mouse Interactions**:
  - Drag to rotate the scene
  - Move the mouse to influence visual effects
- **Keyboard Controls**:
  - `e` Toggle cursor visibility
  - `q` Toggle lighting effects
  - `w` Toggle oscillation effect
  - `s/d` Zoom in / out
  - `a/f` Adjust the `b` variable to influence animation behavior
- **Responsive Design**: The canvas resizes dynamically to fit the browser window.

### Technical Highlights
- **Built with p5.js**: Utilizes WebGL rendering for high-performance graphics.
- **Custom Random Number Generator**: Implements an LCG-based generator for predictable randomness.
- **Multi-Layered Animation**: Creates depth through progressive cube transformations.
- **Smooth Transitions**: Uses `lerp()` to interpolate mouse movement, rotation, and scaling for fluid motion.

## Browser Support
- Works on all modern browsers (Chrome, Firefox, Edge, Safari).
- Best experienced on desktop for full interaction support.

## License
MIT License
