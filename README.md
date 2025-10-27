# MacBook GSAP Landing Page 2025

A stunning Apple-style landing page showcasing MacBook products with immersive 3D animations, scroll-driven effects, and smooth transitions built using modern web technologies.

![MacBook GSAP Landing](https://img.shields.io/badge/React-18+-61DAFB?style=for-the-badge&logo=react&logoColor=white)
![GSAP](https://img.shields.io/badge/GSAP-3.0+-88CE02?style=for-the-badge&logo=greensock&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-Latest-000000?style=for-the-badge&logo=three.js&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind-3.0+-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

## 🌐 Live Demo

Visit the live website: [https://gsap-macbook-landing-2025.vercel.app/](https://gsap-macbook-landing-2025.vercel.app/)

## ✨ Features

### 🎬 Advanced GSAP Animations
- **ScrollTrigger Effects**: Powerful scroll-based animations with precise timeline control
- **Pinned Sections**: Lock sections in view while animating content for engaging experiences
- **SplitText Animations**: Bold text reveals with character-by-character animation
- **Image Masking Effects**: Scroll-triggered pins and masks for visually striking transitions
- **Seamless Timeline Animations**: Smooth animation sequences spanning multiple sections
- **Custom Animated Carousel**: Fully custom carousel with GSAP-powered transitions

### 🎨 3D Visualization
- **Interactive 3D Models**: MacBook models rendered with Three.js
- **Realistic Lighting**: Professional lighting setup for product showcase
- **Scroll-Synced Video Playback**: Video content that responds to scroll position
- **Parallax Scrolling**: Multi-layered depth effects for immersive experience

### 📱 Modern Design
- **Responsive Layout**: Fluid UI that adapts to all screen sizes
- **Apple-Style Aesthetics**: Premium design language inspired by Apple's website
- **Smooth Transitions**: Hardware-accelerated animations for 60fps performance
- **Highlights Section**: Animated product images with scroll effects

## 🛠️ Tech Stack

- **React 18+** - Component-based UI architecture
- **Three.js** - WebGL 3D graphics rendering
- **GSAP 3.0+** - Professional-grade animation library
    - ScrollTrigger plugin
    - SplitText plugin
- **TailwindCSS 3.0+** - Utility-first CSS framework
- **Vite** - Next-generation frontend build tool

## 🚀 Getting Started

### Prerequisites

- Node.js 16+ and npm/yarn/pnpm installed
- Modern web browser with WebGL support

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/gsap-macbook-landing-2025.git
   cd gsap-macbook-landing-2025
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   ```

4. **Open your browser**

   Navigate to `http://localhost:5173` to view the project

## 📁 Project Structure

```
gsap-macbook-landing-2025/
├── public/
│   └── assets/          # Static assets (images, models, videos)
├── src/
│   ├── components/      # React components
│   │   ├── Features.jsx
│   │   ├── Highlights.jsx
│   │   ├── Performance.jsx
│   │   ├── Footer.jsx
│   │   └── Macbook.jsx
│   ├── utils/           # Utility functions and helpers
│   ├── store/           # State management
│   ├── App.jsx          # Main application component
│   ├── index.css        # Global styles with Tailwind
│   └── main.jsx         # Application entry point
├── index.html
├── package.json
├── tailwind.config.js
├── vite.config.js
└── README.md
```

## 🎯 Key Components

### Features Section
Interactive 3D visualization with scroll-driven animations showcasing MacBook capabilities.

### Highlights Section
Product images with animated scroll effects and smooth transitions between different views.

### Performance Section
Detailed specifications and performance metrics with engaging animations.

### Macbook 3D Model
Three.js powered 3D model with realistic materials, lighting, and scroll-controlled animations.

## 🎨 GSAP Animation Patterns

### Basic ScrollTrigger Setup
```javascript
gsap.to(element, {
  scrollTrigger: {
    trigger: section,
    start: "top center",
    end: "bottom center",
    scrub: 1,
    pin: true
  },
  opacity: 1,
  y: 0
});
```

### Timeline Animations
```javascript
const tl = gsap.timeline({
  scrollTrigger: {
    trigger: container,
    start: "top top",
    end: "+=300%",
    scrub: true,
    pin: true
  }
});

tl.to(image, { scale: 1.5, rotation: 180 })
  .to(image, { x: 100, opacity: 0.5 });
```

## 🌟 Performance Optimizations

- **Hardware Acceleration**: GPU-accelerated transforms and opacity
- **Lazy Loading**: Progressive asset loading for faster initial render
- **Code Splitting**: Dynamic imports for optimal bundle size
- **Optimized Three.js**: Efficient rendering with proper dispose patterns
- **GSAP Best Practices**: Using `will-change` and `force3D` properties

## 🎓 Learning Resources

- [GSAP Documentation](https://greensock.com/docs/)
- [ScrollTrigger Guide](https://greensock.com/docs/v3/Plugins/ScrollTrigger)
- [Three.js Fundamentals](https://threejs.org/manual/)
- [React Performance Tips](https://react.dev/learn/render-and-commit)

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 Code Quality

- Follow React best practices and hooks guidelines
- Use ESLint for code linting
- Maintain consistent code formatting
- Write meaningful commit messages
- Add comments for complex animations

## 🐛 Known Issues

- Ensure WebGL is enabled in your browser for 3D models
- Mobile performance may vary depending on device capabilities
- Some animations may need adjustment for very large screens

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspired by Apple's product landing pages
- GSAP (GreenSock) for the powerful animation library
- Three.js community for 3D rendering capabilities
- React team for the excellent framework
- TailwindCSS for utility-first styling

## 📧 Contact

For questions or feedback, please open an issue on GitHub or reach out to the maintainers.

---

**Built with ❤️ using GSAP, React, Three.js, and TailwindCSS**

⭐ Star this repository if you find it helpful!