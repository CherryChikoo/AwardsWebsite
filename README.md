# 🏆 Awards Website — Awwwards-Inspired Interactive Experience

<div align="center">
  <img src="https://img.shields.io/badge/-React_18-black?style=for-the-badge&logoColor=white&logo=react&color=61DAFB" alt="React 18" />
  <img src="https://img.shields.io/badge/-GSAP_Animations-black?style=for-the-badge&logoColor=white&logo=greensock&color=88CE02" alt="GSAP" />
  <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/-Vite-black?style=for-the-badge&logoColor=white&logo=vite&color=646CFF" alt="Vite" />
</div>

<br />

An immersive, visually captivating web application inspired by world-class Awwwards-winning designs (such as Zentry). This project pushes the boundaries of modern web user interfaces by leveraging **GSAP (GreenSock Animation Platform)** for intricate scroll-triggered animations, geometric transitions, interactive video storytelling, and dynamic sound integration.

---

## ✨ Key Features

- 🎬 **Dynamic Video Hero Section**: Engaging entrance animations with interactive video background previews and seamless transitions.
- ⚡ **GSAP ScrollTrigger Integration**: Multi-layered scroll animations, clip-path reveals, and parallax effects that respond fluidly to user scrolling.
- 🍱 **Interactive Bento Grid**: Modern feature showcase utilizing geometric grid layouts with hover effects and video embeds.
- 🎴 **3D Card Tilt & Storytelling**: Animated narrative section featuring custom 3D card tilt interactions and dynamic typography.
- 🎵 **Integrated Audio Experience**: Floating interactive navigation bar equipped with a background audio toggle for immersive browsing.
- 📱 **Responsive & Modern UI/UX**: Built with Tailwind CSS, ensuring flawless performance and visual appeal across desktop, tablet, and mobile devices.

---

## 🛠️ Tech Stack

* **Frontend Framework**: [React 18](https://react.dev/)
* **Build Tool**: [Vite](https://vitejs.dev/)
* **Styling**: [Tailwind CSS](https://tailwindcss.com/)
* **Animation Engine**: [GSAP (GreenSock)](https://gsap.com/) + `@gsap/react` & `ScrollTrigger`
* **Icons & Assets**: Custom SVG icons, webp imagery, and optimized HTML5 video

---

## 🚀 Quick Start

Follow these steps to set up the project locally on your machine.

### Prerequisites

Make sure you have [Node.js](https://nodejs.org/) (v16 or higher) and `npm` installed.

### 1. Clone the Repository

```bash
git clone https://github.com/CherryChikoo/AwardsWebsite.git
cd AwardsWebsite
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Start the Development Server

```bash
npm run dev
```

Open your browser and navigate to **`http://localhost:5173`** to view the live application!

---

## 🏗️ Project Structure

```text
├── public/
│   ├── audio/          # Background loop audio
│   ├── fonts/          # Custom typography (CircularWeb, General, Robert, Zentry)
│   ├── img/            # Optimized webp images & logos
│   └── videos/         # Hero and feature showcase MP4 videos
├── src/
│   ├── components/     # UI Components
│   │   ├── About.jsx           # Scroll-triggered clip-path about section
│   │   ├── AnimatedTitle.jsx   # Reusable GSAP text reveal component
│   │   ├── Button.jsx          # Custom styled interactive button
│   │   ├── Contact.jsx         # Call-to-action banner section
│   │   ├── Features.jsx        # Bento grid feature showcase
│   │   ├── Footer.jsx          # Minimalist footer with social links
│   │   ├── Hero.jsx            # Video preview & entrance animation
│   │   ├── Navbar.jsx          # Floating header with audio controller
│   │   ├── Story.jsx           # 3D interactive story card
│   │   └── VideoPreview.jsx    # Hover-responsive video container
│   ├── App.jsx         # Main application layout
│   ├── index.css       # Custom utility classes & font imports
│   └── main.jsx        # React DOM entry point
├── tailwind.config.js  # Custom theme colors, fonts, and extensions
└── vite.config.js      # Vite configuration
```

---

## 📦 Building for Production

To create an optimized production build:

```bash
npm run build
```

To preview the production build locally:

```bash
npm run preview
```

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
