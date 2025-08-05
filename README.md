# 📺 CRT Shader Effect - Three.js

A stunning interactive CRT (Cathode Ray Tube) monitor simulation built with Three.js and custom GLSL shaders. Transform any image into a nostalgic retro display with authentic CRT effects including scanlines, curvature, chromatic aberration, and more!

## 🚀 [Live Demo](https://daenavan.github.io/crt-threejs/)

## ✨ Features

### 🎛️ Real-time Controls

- **Barrel Distortion**: Adjustable screen curvature for authentic CRT bulge
- **Scanlines**: Customizable thickness and brightness
- **Chromatic Aberration**: RGB color separation effects
- **Vignette**: Adjustable corner darkening
- **Noise**: Film grain and static effects
- **Flicker**: Subtle screen flicker simulation

### 🖼️ Image Support

- **File Upload**: Load your own images (PNG, JPEG, GIF)
- **Aspect Ratio Preservation**: Automatic letterboxing for any image size
- **High-Quality Rendering**: Maintains image clarity while applying effects

### 💾 Export Features

- **Download**: Save your CRT-processed images as PNG files
- **High Resolution**: Export at full canvas resolution

### 🎮 User Experience

- **Hide/Show Controls**: Clean viewing mode with minimalist interface
- **Responsive Design**: Works on desktop and mobile devices
- **Real-time Preview**: Instant feedback on all parameter changes

## 🎯 How to Use

1. **Visit the Live Demo** - Open the application in your browser
2. **Upload an Image** - Click "Choose File" to select your image
3. **Adjust Parameters** - Use the control panel to fine-tune the CRT effects:
   - **Curvature**: Control the screen's barrel distortion
   - **Scanlines**: Adjust the retro scan line appearance
   - **Chromatic Aberration**: Add color separation effects
   - **Vignette**: Darken the corners for authenticity
   - **Noise & Flicker**: Add film grain and screen instability
4. **Hide Controls** - Click "Hide" for a clean viewing experience
5. **Download Result** - Click "Download" to save your creation

## 🛠️ Technical Implementation

### Shader Pipeline

- **Vertex Shader**: UV mapping and position transformation
- **Fragment Shader**: Multi-effect processing including:
  - Barrel distortion mathematics
  - Scanline generation
  - RGB channel separation
  - Procedural noise generation
  - Vignette calculation

### Key Technologies

- **Three.js r128**: 3D graphics library and WebGL abstraction
- **Custom GLSL Shaders**: High-performance GPU-based image processing
- **lil-gui**: Real-time parameter control interface
- **Canvas API**: High-quality image export functionality

### Performance Features

- **GPU Acceleration**: All effects processed on graphics card
- **60 FPS Rendering**: Smooth real-time parameter adjustment
- **Memory Management**: Efficient texture loading and cleanup

## 🎨 Perfect For

- **Digital Art**: Create retro-aesthetic artwork
- **Game Development**: Prototype CRT monitor effects
- **Photography**: Add vintage computer monitor effects
- **Learning**: Understand shader programming and WebGL
- **Nostalgia**: Recreate the classic computing experience

## 🚀 Local Development

1. **Clone the repository**:

   ```bash
   git clone https://github.com/daenavan/crt-threejs.git
   cd crt-threejs
   ```

2. **Serve locally** (due to CORS restrictions with file loading):

   ```bash
   # Using Python 3
   python -m http.server 8000

   # Using Node.js
   npx serve .

   # Using PHP
   php -S localhost:8000
   ```

3. **Open in browser**: Navigate to `http://localhost:8000`

## 📦 Dependencies

- [Three.js](https://threejs.org/) - 3D graphics library
- [lil-gui](https://lil-gui.georgealways.com/) - Lightweight GUI controls

All dependencies are loaded via CDN - no build process required!

## 🤝 Contributing

Contributions are welcome! Feel free to:

- 🐛 Report bugs
- 💡 Suggest new features
- 🔧 Submit pull requests
- 📖 Improve documentation

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- **Three.js Team** - Amazing 3D graphics library
- **WebGL Community** - Shader programming resources
- **Retro Computing Enthusiasts** - Inspiration for authentic CRT effects

---

_Built with ❤️ and a love for retro computing aesthetics_
