# Angry LED Eyes - Camera Tracking

An interactive 3D eye-tracking animation using Three.js and facial recognition. The eyes follow your face in real-time using your webcam.

## 🎯 Features

- **Real-time face tracking** using TensorFlow.js and BlazeFace
- **3D animated eyes** with angry LED-style design
- **Smooth animations** with pupil movement and expressive eyebrows
- **Responsive design** that works across different screen sizes
- **Clean architecture** following SOLID principles and DRY methodology

## 🚀 Live Demo

**[View Live Demo](https://imranrahimov1995.github.io/eyes/)**

## 🛠️ Technologies

- **Three.js** - 3D graphics rendering
- **TensorFlow.js** - Machine learning framework
- **BlazeFace** - Face detection model
- **WebRTC** - Camera access
- **ES6+ JavaScript** - Modern JavaScript with class-based architecture

## 📋 Files

- `cam-eyes.html` - Face-tracking eyes with webcam integration
- `eyes-mouse.html` - Mouse-tracking eyes alternative

## 🎮 How It Works

1. **Face Detection** - Uses BlazeFace model to detect faces in real-time
2. **Position Mapping** - Converts face coordinates to normalized values
3. **Smooth Animation** - Interpolates pupil and eyebrow positions for fluid movement
4. **Visual Effects** - Pulsing glow effects and dynamic expressions

## 🔧 Usage

Simply open the HTML file in a modern web browser that supports:
- WebRTC (for camera access)
- WebGL (for 3D rendering)
- ES6 modules

Grant camera permissions when prompted, and the eyes will start tracking your face!

## 📐 Architecture

The code follows clean architecture principles:
- **Config Management** - Centralized configuration
- **Factory Patterns** - Material and shape creation
- **Component-Based** - Modular eye components
- **Separation of Concerns** - Distinct classes for tracking, animation, and rendering

## 📄 License

MIT License - Feel free to use and modify!

## 👤 Author

**Imran Rahimov**
- GitHub: [@ImranRahimov1995](https://github.com/ImranRahimov1995)

---

