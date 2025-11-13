
# Web-Based Gravity Simulator

An interactive, browser-based **planitary gravity sandbox** built with **Vite**, **React**, and **TypeScript**.  

The goal is to create a fast, accessible, and moddable environment for experimenting with orbital mechanics, planetary systems.

## ✨ Features (current / planned)

- 🌌 Real-time N-body gravitational simulation
- 🪐 3D rendering using WebGL + Three.js
- 🎛 Live controls (time scale, body parameters, presets)

More advanced features (planned):
- Planet surfaces & atmospheric effects
- Habitats, ecosystems
- GPU compute (WebGPU) for large-scale simulations
- Save/load & shareable worlds

## 🤝 Contributing

Contributions are welcomed!
See CONTRIBUTING.md for guidelines on how to help.

## Tech Stack

- **Vite** – blazing fast dev server & bundler  
- **React + TypeScript** – UI and app structure  
- **Three.js** – 3D rendering  
- **WebGL / WebGPU** – future GPU-based physics and rendering  

## Getting Started

### Clone Repo
```bash
git clone https://github.com/MmaxRra/starborn-engine.git
cd <repo-name>
```

### Install dependencies
```bash
npm install
```

### Run locally 
```bash
npm run dev
```

## Project Structure

```
src/
  engine/      # Physics, world logic
  render/      # Three.js renderer & scene setup
  uiux/        # Components, styles, assets
  main.tsx
  App.tsx
```