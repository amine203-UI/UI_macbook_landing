

<div align="center">
  <h1 align="center">💻 Macbook Pro: 3D Experience</h1>

  <p align="center">
    An immersive, high-end product showcase featuring advanced 3D rendering and scroll-driven cinematic storytelling.
  </p>

  <br />
  <img src="public/readme/hero.webp" alt="Macbook Landing Page Banner" width="800">
  <br />

  <div>
    <img src="https://img.shields.io/badge/-React-61DAFB?style=for-the-badge&logo=React&logoColor=black" />
    <img src="https://img.shields.io/badge/-GSAP-88CE02?style=for-the-badge&logo=greensock&logoColor=white" />
    <img src="https://img.shields.io/badge/-Three.js-black?style=for-the-badge&logo=three.js&logoColor=white" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />
    <img src="https://img.shields.io/badge/-Zustand-443E38?style=for-the-badge&logo=react&logoColor=white" />
  </div>
</div>

---

## 📖 Table of Contents
- [✨ Introduction](#introduction)
- [⚙️ Tech Stack](#tech-stack)
- [🔋 Features](#features)
- [🤸 Quick Start](#quick-start)

---

## <a name="introduction">✨ Introduction</a>

This project is a high-performance **Apple-style 3D landing page** built to push the boundaries of web interactivity. By combining **Three.js** for 3D rendering and **GSAP** for intricate animation timelines, it creates a "scrollytelling" experience where the product comes to life as the user explores the page.

From reactive 3D models to seamless video transitions, this landing page demonstrates modern front-end engineering at its finest.

---

## <a name="tech-stack">⚙️ Tech Stack</a>

### 🎨 Frontend & Design
* **React.js:** Orchestrates the modular UI and manages the lifecycle of 3D scenes.
* **Tailwind CSS:** Provides a utility-first approach for pixel-perfect, responsive layouts.
* **Zustand:** A lightweight state management solution used to sync animations and UI states across different sections.

### 🚀 Animation & 3D
* **Three.js:** The core engine for rendering the Macbook 3D model, handling realistic PBR materials, lighting, and environmental reflections.
* **GSAP (GreenSock):** The powerhouse behind the motion:
    * **ScrollTrigger:** For frame-by-frame 3D model control.
    * **SplitText:** For cinematic typography reveals.
    * **Pinning:** To create high-impact focal points during scroll transitions.

### 🛠️ Development Tools
* **Vite:** Ensures an ultra-fast development cycle with Hot Module Replacement (HMR).
* **GLTF Pipeline:** Optimized 3D model loading for fast initial page paint.

---

## <a name="features">🔋 Key Features</a>



* **Realistic Lighting System:** Dynamic environment maps and studio-quality lighting that react to the 3D model's orientation.
* **Scroll-to-Animate:** The Macbook model opens, rotates, and transforms seamlessly as you scroll through different feature sets.
* **Interactive Carousel:** A custom-built slider that integrates 3D depth with traditional UI elements.
* **Video Masking & Transitions:** Visually striking transitions between 2D video content and 3D webgl scenes using GSAP masking.
* **Ultra-Responsive Layout:** Adaptive camera FOV (Field of View) and animation scaling to ensure the 3D experience feels native on both mobile and 4K displays.

---

## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to get the environment running locally.

### 1. Clone the Repo
```bash
git clone [https://github.com/amine203-UI/UI_macbook_landing.git](https://github.com/amine203-UI/UI_macbook_landing.git)
cd UI_macbook_landing

```
2. Install Dependencies
```
npm install

```
3. Run Development Server
```
npm run dev

```
Visit http://localhost:5173 and start exploring.


