# Dither Forge
A modern, WebGL2-powered playground for real-time image dithering and creative digital art.

![Dither Forge Banner](https://dummyimage.com/1200x400/0f0f0f/ffffff&text=DITHER+FORGE)

Dither Forge transforms images into pixel-perfect art using fast, GPU-accelerated algorithms and customizable palettes.

---

## Overview
Dither Forge is a browser-based, real-time image processing tool built for creative coders, digital artists, and developers.  
It lets you experiment with dithering techniques, retro palettes, and shader-based effects — all powered by React, WebGL2, and Web Workers.

Drop in any image, tweak the algorithm settings, and see the results instantly.

---

## Features
- Real-time previews powered by WebGL2 shaders
- Multiple dithering algorithms:
  - Bayer 8×8 Ordered Dithering (GPU)
  - Floyd–Steinberg Error Diffusion (CPU Web Worker)
  - Atkinson and Jarvis-Judice-Ninke (coming soon)
- Built-in retro palettes: Game Boy, C64, Mono, 16-color, and more
- Drag-and-drop image uploads
- Export lossless PNGs with palette JSON metadata
- Extensible architecture for adding custom palettes, kernels, and shaders

---

## Tech Stack
- **Frontend:** React + TypeScript + Vite
- **Rendering Engine:** WebGL2 + Web Workers
- **Styling:** Tailwind CSS
- **Image Export:** Indexed PNG via UPNG.js

---

## Installation

```bash
# Clone the repository
git clone https://github.com/<your-username>/dither-forge.git
cd dither-forge

# Install dependencies
npm install

# Start the development server
npm run dev

# Build for production
npm run build
