# Soulful Heaven - 3D/Interactive Web Experience

A high-performance, visually stunning, and interactive landing page for **Soulful Heaven** (celebrating Indian cultural and spiritual toys since 2026). This project serves as a showcase for state-of-the-art interactive web animations, combining smooth scroll-driven storytelling with rich vector animations.

---

## 🚀 Live Demo Tech Stack

This project is built using a modern frontend stack optimized for rich animations and interactive UI:

*   **Vite**: Next-generation frontend tooling for hot module replacement (HMR) and fast production builds.
*   **Rive (WebGL2 Renderer)**: Interactive, state-machine-driven vector animations (`.riv`) rendered on high-performance `<canvas>` elements.
*   **GSAP (GreenSock Animation Platform) & ScrollTrigger**: Custom timeline-based and scroll-driven animation controls for letters, text splits, and structural layouts.
*   **Vanilla CSS**: Flexible, custom-themed layouts utilizing modern styling variables.
*   **HTML5 Semantic Markup**: Clean and SEO-friendly document structure.

---

## ✨ Features

1.  **Immersive Motion Graphics**:
    *   Dynamic Rive vector integrations (including `surfer.riv`, `palm_tree.riv`, `boom.riv`, `intro.riv`) that scale and animate seamlessly.
    *   Scroll-bound typographic transformations that split, stagger, and glide as you traverse the page.
2.  **Interactive Aesthetics**:
    *   Custom fullscreen overlay menu with micro-animations.
    *   Curated retro colors and typography reminiscent of the late '70s and early '80s.
3.  **Fully Responsive**:
    *   Fluid viewport sizing across desktop, tablet, and mobile browsers.
    *   Adaptive layouts with dedicated mobile menu controls.
4.  **Language Support**:
    *   Integrated frontend shell structured to handle multi-locale switches (e.g., FR, EN, IT, ES, DE).

---

## 📁 Project Structure

```text
├── dist/                          # Compiled JavaScript modules and CSS stylesheets
├── wp-content/                    # Core assets folder
│   └── themes/blueprint/theme/
│       └── public/
│           └── rives/             # Interactive Rive (.riv) animation binary files
├── index.html                     # Core HTML5 page structure and runtime configuration
├── package.json                   # Project dependencies and script controls
├── vite.config.js                 # Vite bundler and development server configuration
└── README.md                      # Project documentation
```

---

## 🛠️ Getting Started

### Prerequisites

Ensure you have [Node.js](https://nodejs.org/) installed (v18+ recommended).

### Installation & Run

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/BadushaPN/scan-analyzer-tool-test.git
    cd scan-analyzer-tool-test
    ```

2.  **Install dependencies**:
    ```bash
    npm install
    ```

3.  **Run the local development server**:
    ```bash
    npm run dev
    ```

4.  **Open the browser**:
    Navigate to `http://localhost:5173` to explore the website.
