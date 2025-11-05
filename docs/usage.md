# 🪟 Liquid Glass Framework

A minimalist, Apple-inspired front-end framework built with pure **CSS** and **JavaScript**,  
designed for glassy, fluid interfaces that feel natural, elegant, and modern.

---

## ✨ Features

- 🧊 Frosted glass components (buttons, cards, overlays)
- 🩶 Built-in light & dark themes
- 🎨 Accent color customization
- 📐 Responsive 12-column grid system
- ⚙️ Smooth animations (scroll, hover, parallax)
- 🔋 No dependencies — pure CSS & JS

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/liquid-glass-framework.git
cd liquid-glass-framework
````

### 2. Link the Framework

In your HTML file:

```html
<link rel="stylesheet" href="src/base/_reset.css">
<link rel="stylesheet" href="src/base/_variables.css">
<link rel="stylesheet" href="src/base/_globals.css">
<link rel="stylesheet" href="src/layout/_grid.css">
<link rel="stylesheet" href="src/utilities/_themes.css">
<script type="module" src="src/js/main.js"></script>
```

---

## 🪩 Example Usage

```html
<div class="glass-card" data-animate data-glow>
  <h3>Hello Glass</h3>
  <p>This is a frosted, adaptive card component.</p>
  <button class="glass-btn" data-toggle-theme>Toggle Theme</button>
</div>
```

---

## 🎨 Theming & Customization

* Toggle light/dark theme:

  ```html
  <button data-toggle-theme>Toggle Theme</button>
  ```

* Change accent color:

  ```html
  <button data-set-accent="green">Green</button>
  <button data-set-accent="pink">Pink</button>
  ```

* Adjust blur level:

  ```html
  <html data-glass="strong">
  ```

---

## 🧱 Layout System

The grid uses a 12-column responsive structure.

```html
<div class="glass-row">
  <div class="glass-col-6-md">
    <div class="glass-card">Left Column</div>
  </div>
  <div class="glass-col-6-md">
    <div class="glass-card">Right Column</div>
  </div>
</div>
```

---

## 🧩 Animations

Elements with `data-animate` fade in smoothly when they enter the viewport.
Add `data-parallax="0.3"` for parallax motion on scroll, or `data-glow` for hover effects.

---

## 📦 Folder Structure

```
liquid-glass-framework/
├── docs/
│   ├── changelog.md
│   ├── index.html
│   └── usage.md
├── src/
│   ├── base/
│   │   ├── _reset.css
│   │   └── _variables.css
│   ├── components/
│   │   ├── _animations.css
│   │   ├── _buttons.css
│   │   ├── _cards.css
│   │   ├── _modals.css
│   │   └── _navbar.css
│   ├── js/
│   │   ├── _animations.js
│   │   ├── _helpers.js
│   │   ├── _theme.js
│   │   └── main.js
│   ├── layout/
│   │   ├── _containers.css
│   │   ├── _footer_.css
│   │   ├── _grid.css
│   │   └── _header.css
│   └── utilities/
│   │   ├── _helpers.css
│   │   ├── _responsive.css
│   │   └── _themes.css
├── LICENSE
├── package.json
└── README.md

```

---

## 💡 License

MIT © 2025 — Created with ✨ by [Oliver Kent Santos](https://github.com/javascript2025course-Oliver)