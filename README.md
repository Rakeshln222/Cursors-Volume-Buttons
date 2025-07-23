 🎨 Creative Cursors & Volume Buttons

A fully responsive, interactive, and aesthetic showcase of **25 custom cursor styles** and **25 volume button animations**, all built using **pure HTML, CSS, and JavaScript**. This project demonstrates how modern web design techniques can create visually engaging UI components with smooth animations and dynamic interactions — all in a single HTML file.

---

## 📁 Project Overview

* **Title**: Creative Cursors & Volume Buttons
* **Technology Stack**: HTML5, CSS3 (with variables and animations), Vanilla JavaScript
* **UI Elements**:

  * 🎯 25 Animated Cursor Designs
  * 🔊 25 Volume Button Styles

---

## 🌐 Live Preview

> ⚠️ Not hosted yet — but you can simply open `index.html` in any modern browser to see the demo.

---

## 📦 File Structure

```plaintext
📂 project-root/
└── index.html   # Contains all HTML, CSS, and JavaScript in one file
```

---

## ✨ Features

### 🖱️ Cursor Styles

* Dynamic preview on hover
* Pure CSS cursor shapes and animations
* Examples include:

  * Bubble Glow
  * Pixel Arrow
  * Magic Wand
  * Ninja Shuriken
  * Neural Network

### 🔊 Volume Buttons

* Interactive buttons with visual feedback
* Hover-triggered animations and morphing effects
* Examples include:

  * Gradient Orb
  * Equalizer Bars
  * Neon Tube
  * Binary Toggle
  * Eclipse Control

### 📱 Responsive Layout

* Mobile-friendly grid using CSS Grid
* Adapts gracefully to different screen sizes

### ⚙️ JavaScript Logic

* Dynamically generates all items from data arrays
* Handles hover interactions, cursor tracking, and live DOM updates
* Dynamic `styleElement.sheet.insertRule()` usage for runtime styling

---

## 🧠 How It Works

1. **Data Structures**:
   JavaScript arrays `cursors[]` and `volumeButtons[]` store all metadata (name, class, description).

2. **Rendering Logic**:
   The script dynamically populates two `.grid` containers: one for cursors and another for volume buttons.

3. **Hover Previews**:
   On hover over cursor blocks, a temporary `<div class="custom-cursor">` is created and follows mouse movement.

4. **Dynamic CSS Injection**:
   Additional cursor types and animations are added at runtime using the DOM's stylesheet API.

5. **Animation Logic**:
   CSS keyframes like `spin`, `pulse`, `bounce`, and `eq1–eq5` give motion to cursors and buttons.

---

## 🛠 Technologies Used

| Tech              | Purpose                           |
| ----------------- | --------------------------------- |
| **HTML5**         | Markup structure                  |
| **CSS3**          | Styling, transitions, animations  |
| **CSS Variables** | Theme-based color customization   |
| **JavaScript**    | Dynamic rendering, event handling |

---

## 🔍 Example Cursor & Button Classes

### Cursor Examples:

```css
.cursor-1 { background: rgba(108, 92, 231, 0.5); border: 2px solid #6c5ce7; }
.cursor-3 { border: 3px dashed #6c5ce7; animation: spin 4s linear infinite; }
.cursor-6 { animation: pulse 2s infinite; box-shadow: 0 0 15px #a29bfe; }
```

### Volume Button Examples:

```css
.volume-1:hover { transform: scale(1.1); box-shadow: 0 0 20px rgba(108, 92, 231, 0.5); }
.volume-2::before { transition: all 0.3s; }
```

---

## 💡 Customization

You can easily extend this project by:

* Adding new entries to the `cursors` or `volumeButtons` arrays.
* Creating new CSS classes with custom animations.
* Applying new icons using emojis or SVG.

---

## 🚀 How to Run

1. Download or clone this repo
2. Open `index.html` in any modern browser
3. Hover over each element to see interactive effects

---

## 📚 Learning Objectives

This project helps understand:

* DOM manipulation in Vanilla JavaScript
* CSS keyframe animations
* Responsive layouts with CSS Grid
* Real-time dynamic styling using JavaScript
* Building single-page UI showcases without frameworks

---

## 🧾 License

This project is **open source** and can be used freely for **learning and demonstration purposes**.

---

## 🙌 Author

**Rakesh L N**
Frontend Enthusiast | Creative Web Developer

---

