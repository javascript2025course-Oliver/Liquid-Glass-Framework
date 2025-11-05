# 🪟 Liquid Glass Framework

> A minimalist, glass-inspired front-end framework for creating fluid, elegant interfaces — powered by pure CSS and JavaScript.  
> Designed with the same precision and calm aesthetic found in Apple’s design language.

---

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Version](https://img.shields.io/badge/version-1.0.0-lightgrey.svg)
![Status](https://img.shields.io/badge/status-stable-success.svg)

---

## ✨ Features

- 🧊 **Glassy Components** — buttons, cards, overlays, and more  
- 🌗 **Light & Dark Themes** — auto and manual toggling  
- 🎨 **Accent Customization** — choose from Apple-inspired colors  
- 📐 **Responsive Grid** — modern 12-column layout  
- 💫 **Smooth Animations** — scroll, hover, and parallax  
- ⚙️ **Zero Dependencies** — built with pure CSS + JS  

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/liquid-glass-framework.git
cd liquid-glass-framework
````

### 2️⃣ Link the Framework in HTML

```html
<link rel="stylesheet" href="src/base/_reset.css">
<link rel="stylesheet" href="src/base/_variables.css">
<link rel="stylesheet" href="src/base/_globals.css">
<link rel="stylesheet" href="src/layout/_grid.css">
<link rel="stylesheet" href="src/utilities/_themes.css">
<script type="module" src="src/js/main.js"></script>
```

---

## 🧱 Example Usage

```html
<div class="glass-card" data-animate data-glow>
  <h3>Hello Glass</h3>
  <p>Beautifully simple, lightweight, and responsive.</p>
  <button class="glass-btn" data-toggle-theme>Toggle Theme</button>
</div>
```

**Live Demo:** → [docs/index.html](./docs/index.html)

---

## 🎨 Theming Options

```html
<!-- Toggle dark/light theme -->
<button data-toggle-theme>Toggle Theme</button>

<!-- Change accent color -->
<button data-set-accent="pink">Pink Accent</button>
<button data-set-accent="green">Green Accent</button>

<!-- Adjust glass intensity -->
<html data-glass="strong">
```

---

## 📦 Folder Structure

```
liquid-glass-framework/
├── src/
│   ├── base/
│   ├── components/
│   ├── layout/
│   ├── utilities/
│   └── js/
└── docs/
    ├── index.html
    ├── usage.md
    └── changelog.md
```

---

## 🧩 Coming Soon

* ✨ Modals, Navbars, and Dropdowns
* 🎚️ Configurable build via `glass.config.js`
* 📦 NPM/CDN distribution for easy integration
* 🌈 Theme presets and design tokens

---

## 💡 Contributing

Contributions, feedback, and ideas are always welcome!
Please open an [Issue](https://github.com/yourusername/liquid-glass-framework/issues)
or submit a [Pull Request](https://github.com/yourusername/liquid-glass-framework/pulls).

---

## 📜 License

Licensed under the **MIT License**.
© 2025 [Your Name]. All rights reserved.

---

> *Crafted with care, calm, and clarity — the Liquid Glass way.*