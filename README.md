# Mayo Martinez - Portfolio

> Research & Development Professional | Operations Specialist | Technical Leader

## 🚀 Live Website

**[Visit Portfolio](https://mayobanexmartinez.com)**

## 🎯 About

This portfolio showcases my unique position at the intersection of research, technology, and operations. From analyzing AI's impact on emerging economies to automating luxury fashion operations, I transform insights into efficiency and innovation into results.

## ✨ Features

- **Alien-Tech Animations**: 4 cutting-edge animated backgrounds using Vanta.js
- **Performance Optimized**: Adaptive quality based on device capabilities
- **Mobile Responsive**: Optimized for all screen sizes
- **Accessibility Compliant**: Respects reduced motion preferences

## 🚀 Live Demo

[View Live Portfolio](https://mayobanexmartinez.com) - See the animations in action!

## 📦 Technologies Included

### Core Libraries
- **Vanta.js** - Interactive 3D WebGL backgrounds
- **Particles.js** - Lightweight particle systems
- **Three.js** - Custom 3D scenes and geometries
- **Ambient Canvas** - Noise-based organic motion
- **CSS Animations** - Pure CSS gradient effects

### Performance Features
- 🔋 Battery level monitoring
- 📱 Mobile-first responsive design
- ⚡ GPU acceleration optimization
- 🎯 Adaptive quality settings
- 👁️ Visibility API integration
- ♿ Accessibility compliance

## 🛠️ Quick Start

```html
<!-- Include the library -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r134/three.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/vanta@latest/dist/vanta.waves.min.js"></script>

<!-- Add background container -->
<div id="animated-bg"></div>

<!-- Initialize -->
<script>
  VANTA.WAVES({
    el: "#animated-bg",
    mouseControls: true,
    touchControls: true,
    color: 0x667eea,
    waveHeight: 20,
    waveSpeed: 0.75
  });
</script>
```

## 📁 Project Structure

```
animated-backgrounds/
├── demos/
│   ├── vanta-examples/
│   ├── particles-showcase/
│   ├── three-scenes/
│   └── css-gradients/
├── src/
│   ├── optimizations/
│   ├── fallbacks/
│   └── utilities/
├── docs/
├── performance-tests/
└── examples/
```

## 🎨 Animation Types

### 1. Vanta.js Effects
- **Waves** - Fluid ocean-like motion
- **Birds** - Flocking algorithm visualization
- **Clouds** - Volumetric cloud rendering
- **Topology** - Network node connections
- **Particles** - Dynamic particle systems

### 2. Custom Three.js Scenes
- **Geometric Patterns** - Rotating 3D shapes
- **Particle Fields** - Custom particle physics
- **Procedural Landscapes** - Generated terrain
- **Abstract Art** - Algorithmic compositions

### 3. Performance-Optimized CSS
- **Gradient Animations** - Smooth color transitions
- **Particle CSS** - Pure CSS particle effects
- **Morphing Shapes** - CSS-based shape animations

## ⚡ Performance Optimization

### Adaptive Quality System
```javascript
// Automatic quality adjustment based on device capabilities
function getOptimalConfig(device) {
  return {
    particleCount: device.isLowPower ? 50 : 200,
    animationSpeed: device.batteryLevel > 0.3 ? 1.0 : 0.5,
    effects: device.supportsWebGL ? 'full' : 'fallback'
  };
}
```

### Battery Awareness
- Monitors battery level via Battery API
- Reduces animation complexity when battery < 30%
- Switches to static gradients in power-saving mode

### Mobile Optimizations
- Touch event throttling
- Reduced particle counts
- GPU acceleration hints
- Viewport-based lazy loading

## 🔧 Implementation Examples

### Professional Portfolio Setup
```javascript
// Enhanced configuration for business sites
const portfolioConfig = {
  effect: 'waves',
  colors: ['#667eea', '#764ba2'],
  intensity: 'subtle',
  interactions: true,
  accessibility: true,
  performance: 'optimized'
};
```

### Gaming/Creative Setup
```javascript
// High-impact configuration for creative sites
const creativeConfig = {
  effect: 'particles',
  colors: ['#ff6b6b', '#4ecdc4', '#45b7d1'],
  intensity: 'high',
  interactions: true,
  customShaders: true,
  performance: 'maximum'
};
```

## 📊 Performance Benchmarks

| Device Type | Frame Rate | Battery Impact | Load Time |
|-------------|------------|----------------|-----------|
| Desktop     | 60fps      | Minimal        | <1s       |
| Mobile      | 30fps      | Low           | <2s       |
| Low-end     | 15fps      | Very Low      | <3s       |

## 🌐 Browser Support

- ✅ Chrome 80+
- ✅ Firefox 75+
- ✅ Safari 13+
- ✅ Edge 80+
- ⚠️ IE11 (fallback only)

## ♿ Accessibility Features

- Respects `prefers-reduced-motion`
- Keyboard navigation support
- Screen reader friendly
- High contrast mode compatibility
- Focus indicators for interactive elements

## 📖 Documentation

### Installation Guide
[Getting Started](docs/installation.md)

### API Reference
[Complete API Documentation](docs/api.md)

### Performance Guide
[Optimization Best Practices](docs/performance.md)

### Accessibility Guide
[Making Animations Inclusive](docs/accessibility.md)

## 🤝 Contributing

Contributions welcome! Please read our [Contributing Guide](CONTRIBUTING.md) for details.

### Development Setup
```bash
git clone https://github.com/Mayomh11/animated-backgrounds
cd animated-backgrounds
npm install
npm run dev
```

## 📄 License

MIT License - see [LICENSE](LICENSE) for details.

## 🙏 Acknowledgments

- [Vanta.js](https://vantajs.com) for amazing WebGL effects
- [Three.js](https://threejs.org) for 3D capabilities
- [Particles.js](https://vincentgarreau.com/particles.js/) for lightweight particles

## 📞 Contact

**Mayo Martinez**
- Portfolio: [mayobanexmartinez.com](https://mayobanexmartinez.com)
- Email: Mayo9711@gmail.com
- LinkedIn: [mayo-martinez](https://linkedin.com/in/mayo-martinez-791492160)
- GitHub: [@Mayomh11](https://github.com/Mayomh11)

---

⭐ Star this repo if you find it useful!