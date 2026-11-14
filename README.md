# 🎡 Animated Ferris Wheel

<p align="center">
  <strong>A rotating Ferris wheel animation built entirely with HTML5 and CSS3.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-Structure-orange?style=for-the-badge&logo=html5" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-Animation-blue?style=for-the-badge&logo=css3" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-Not%20Required-lightgrey?style=for-the-badge" alt="No JavaScript">
  <img src="https://img.shields.io/badge/Responsive-Design-success?style=for-the-badge" alt="Responsive Design">
</p>

---

## 📌 Project Overview

The **Animated Ferris Wheel** is a front-end development project that demonstrates how HTML and CSS can be combined to create a rotating mechanical illustration with smooth animations.

The Ferris wheel features six rotating spokes, six passenger cabins, animated colour transitions, and a central rotating hub.

The entire animation is created using CSS positioning, transforms, keyframes, and animation timing functions without requiring JavaScript.

This project demonstrates practical knowledge of CSS animation and visual layout techniques while creating an engaging browser experience.

## 🌐 Live Demo

**GitHub Repository:**  
https://github.com/Regalson001/css-animated-ferris-wheel

**Live Website:**  
https://regalson001.github.io/css-animated-ferris-wheel/

*The live demo URL becomes available after successfully enabling GitHub Pages.*

## ✨ Features

### 🎡 Rotating Ferris Wheel
- Circular Ferris wheel structure.
- Smooth 360-degree continuous rotation.
- Six evenly distributed spokes.
- CSS-based animation using `@keyframes`.

### 🚡 Animated Passenger Cabins
- Six individually positioned cabins.
- Cabin rotation synchronized with the wheel.
- Automatic colour transitions.
- Rounded cabin design with borders and shadows.

### 🎨 Visual Design
- Dark modern background.
- Blue and cyan accent colours.
- Gradient effects.
- Glowing central hub.
- Custom support structure and ground decoration.

### 📱 Responsive Layout
- Flexible wheel sizing using CSS `min()` and viewport units.
- Responsive typography using `clamp()`.
- Mobile-specific adjustments.
- Layout adapts to different screen sizes.

### ♿ Accessibility
- Semantic HTML structure.
- Descriptive page metadata.
- Reduced-motion support through `prefers-reduced-motion`.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Page structure and content |
| CSS3 | Styling and visual presentation |
| CSS Animations | Continuous Ferris wheel rotation |
| CSS Keyframes | Animation sequences |
| CSS Transforms | Rotation and positioning |
| CSS Flexbox | Layout alignment |
| CSS Gradients | Background and visual effects |
| Media Queries | Responsive design |

**No JavaScript, frameworks, external libraries, or build tools are required.**

## 📂 Project Structure

```text
css-animated-ferris-wheel/
│
├── index.html
│   └── Main HTML document
│
├── styles.css
│   └── Complete styling and animation logic
│
└── README.md
    └── Project documentation
```

## 🚀 Getting Started

You can run this project locally in a few simple steps.

### Prerequisites

- A computer with a modern web browser.
- Visual Studio Code or another code editor.
- Git installed on your computer.

### 1. Clone the Repository

Open your terminal and run:

```bash
git clone https://github.com/Regalson001/css-animated-ferris-wheel.git
```

### 2. Navigate into the Project

```bash
cd css-animated-ferris-wheel
```

### 3. Open in Visual Studio Code

```bash
code .
```

### 4. Run the Project

Open `index.html` in your browser.

Alternatively, install the Live Server extension in Visual Studio Code and select **Open with Live Server**.

The Ferris wheel animation will start automatically when the page loads.

## 💡 CSS Techniques Demonstrated

This project highlights several important CSS concepts.

### 1. CSS Positioning

The Ferris wheel uses:

- `position: relative`
- `position: absolute`
- `top`
- `left`
- `right`

These properties position the spokes and cabins around the circular wheel.

### 2. CSS Transforms

The `transform` property rotates the wheel and its individual components.

Example:

```css
transform: rotate(60deg);
```

### 3. CSS Transform Origin

The cabins use:

```css
transform-origin: 50% 0%;
```

This controls the point around which each cabin rotates.

### 4. CSS Keyframe Animations

The Ferris wheel rotates continuously using:

```css
@keyframes wheel {
  0% {
    transform: rotate(0deg);
  }

  100% {
    transform: rotate(360deg);
  }
}
```

### 5. Animation Timing

The wheel uses:

```css
animation: wheel 12s linear infinite;
```

This creates a smooth, continuous rotation that repeats indefinitely.

### 6. Responsive Design

The project uses viewport-based sizing, `min()`, `clamp()`, and media queries to adapt to different screen sizes.

### 7. Accessibility and Reduced Motion

The project respects users who prefer reduced motion:

```css
@media (prefers-reduced-motion: reduce) {
  .wheel,
  .cabin {
    animation: none;
  }
}
```

## 🎯 Learning Objectives

Through this project, I practised:

- Building visual structures using HTML elements.
- Positioning multiple elements inside a circular layout.
- Creating continuous CSS animations.
- Working with CSS transforms and transform origins.
- Synchronizing multiple animations.
- Applying colour transitions using keyframes.
- Creating responsive layouts.
- Using CSS gradients, shadows, and borders.
- Supporting reduced-motion accessibility preferences.

## 🔧 Possible Future Improvements

Potential enhancements include:

- Add interactive pause and resume controls.
- Add adjustable animation speed.
- Create a more detailed Ferris wheel support structure.
- Add decorative background elements.
- Introduce different cabin designs.
- Add day and night visual themes.
- Build additional amusement park animations.

## 📸 Project Preview

Add a screenshot or GIF of your completed Ferris wheel here when available.

For example:

```markdown
![Animated Ferris Wheel Preview](./assets/ferris-wheel-preview.png)
```

Create an `assets` folder and place your screenshot inside it before using this image reference.

## 🌍 Deployment with GitHub Pages

This project can be hosted for free using GitHub Pages.

1. Open this repository on GitHub.
2. Navigate to **Settings**.
3. Select **Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Choose the `main` branch.
6. Select `/(root)` as the deployment folder.
7. Click **Save**.

GitHub will publish the website after the deployment process completes.

## 👨‍💻 Author

**Stephen Oyugi**

Front-End Developer | AI Automation Practitioner | Machine Learning Practitioner

📍 Nairobi, Kenya

- **GitHub:** https://github.com/Regalson001
- **LinkedIn:** https://linkedin.com/in/stephenoyugi001
- **Email:** stephennyarangi03@gmail.com

## 📄 License

This project is licensed under the MIT License.

You are free to use, modify, and distribute this project in accordance with the license terms.

---

<p align="center">
  <strong>Designed and developed by Stephen Oyugi.</strong>
</p>

<p align="center">
  Building interfaces. Exploring CSS. Creating through code.
</p>
