# MoodSpark — Color Palette Generator

A fun, interactive color palette generator for designers and developers. Click the spark button to generate a random five-color palette inspired by automotive color theory, copy individual hex codes with one click, and export your palette as ready-to-use CSS variables.

## ✨ Features

- **Random palette generation** — 5-color harmonious palettes on every click
- **One-click hex copying** — Click any swatch to copy its hex code instantly
- **CSS export** — Download your palette as ready-to-use CSS variables
- **Dark/light theme toggle** — Switch between modes with a beautiful toggle
- **Particle canvas background** — Smooth, interactive particle system
- **Keyboard shortcut** — Press <kbd>Space</kbd> to generate a new palette
- **Responsive design** — Looks great on desktop, tablet, and mobile
- **Animations** — Smooth transitions powered by CSS and JavaScript
- **No build step** — Just HTML, CSS, and vanilla JavaScript

## 🚀 Live Demo

**[https://jazblue.github.io/mood-spark/](https://jazblue.github.io/mood-spark/)**

## 🛠️ Technologies

- **HTML5** — Semantic markup
- **CSS3** — Custom properties, grid, flexbox, transitions, animations
- **JavaScript (ES6+)** — Vanilla JS, no frameworks
- **Canvas API** — Interactive particle background
- **Clipboard API** — Copy hex codes to clipboard
- **File API** — CSS variable export
- **Poppins** — Google Fonts (headings & body)
- **Fira Code** — Google Fonts (monospace for hex values)
- **Font Awesome** — Icons

## 📦 Running Locally

No build tools or dependencies required — just open the HTML file directly in your browser.

```bash
# Clone the repository
git clone https://github.com/Jazblue/mood-spark.git
cd mood-spark

# Open in your browser
open index.html
```

You need an internet connection for the first load (Google Fonts, CDN icons).

## 🎯 How It Works

1. **Click the "Generate Palette" button** (or press **Space**) to create a random 5-color palette
2. **Click any color swatch** to copy its hex code to your clipboard — a toast notification confirms the copy
3. **Toggle dark/light mode** in the top-right toggle for a different viewing experience
4. **Export as CSS** using the "Export CSS" button to download a `.css` file with CSS custom properties

### Color Generation Algorithm

Palettes are generated using a **harmonious HSL approach**:
- A base hue is selected randomly from the full 360° color wheel
- Each of the 5 colors is offset by 60° (60 × i) to create visually pleasing color relationships
- Saturation ranges from 50–90% and lightness from 30–70% for balanced contrast
- Text contrast is automatically calculated using luminance for readable swatches

### Particle System

The background features ~80 interactive particles connected by subtle lines. Particles:
- Float and drift naturally with slight random velocities
- Apply friction for smooth, organic movement
- Connect with lines when within 100px of each other
- React to mouse movement with gravitational pull
- Cycle through an accent color palette (purple, gold, blue, red)

## 📁 Project Structure

```
mood-spark/
├── index.html          # All markup, styles, and scripts in one file
├── README.md           # Project documentation
└── 404.html            # Custom 404 page
```

This project uses a single-file architecture for simplicity — no build step, no bundlers, no frameworks.

## 🧪 Testing

Verified in:
- ✅ Latest Chrome, Edge, Firefox
- ✅ Mobile Safari (iOS)
- ✅ Chrome on Android
- ✅ Responsive breakpoints at 600px and 900px

## 📄 License

MIT License — feel free to fork, modify, and use this project however you like!

- **Code**: [MIT License](https://opensource.org/licenses/MIT)
- **Fonts**: SIL Open Font License (Poppins, Fira Code)
- **Icons**: Font Awesome free tier
- **Theme toggle icon**: Custom SVG

## 👤 Author

Created by [Jason Harvey](https://github.com/Jazblue) — IT Cloud Engineer aspirant, Manchester United fan, and creative developer based in Chatham, UK.

[![GitHub](https://img.shields.io/badge/GitHub-Jazblue-black?logo=github)](https://github.com/Jazblue)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-blue?logo=githubpages)](https://jazblue.github.io/mood-spark/)