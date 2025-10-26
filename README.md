# Interactive 3D Globe with Project Rays

A visually stunning interactive 3D globe built with **Three.js**, displaying projects as glowing points connected with rays. Users can hover or click on rays to reveal corresponding project cards. Fully responsive with support for desktop and mobile devices.

---

## Features

* **3D Interactive Globe**: Rotate, zoom, and explore the globe using mouse or touch controls.
* **Project Rays**: Each project is represented as a glowing ray and point on the globe.
* **Project Cards**: Dynamic cards appear on ray hover or click, showing project images, titles, and descriptions.
* **Responsive Design**: Optimized for desktop, tablets, and mobile devices.
* **Custom Visual Effects**:

  * Neon glow effect around the globe.
  * Decorative rays for ambient visual depth.
  * Smooth background motion tied to globe rotation.
* **Touch Support**: Mobile-friendly touch gestures for rotating the globe and selecting projects.

---

## Installation & Setup

1. Clone the repository:

```bash
git clone https://github.com/anum-349/Interactive-3D-Globe-with-Project-Rays.git
```

2. Open `test1.html` in a web browser.

> **Note:** The project uses CDN links for **Three.js** and **OrbitControls**, so an internet connection is required.

---

## Usage

* **Rotate Globe**: Click and drag on the globe (desktop) or use touch drag (mobile).
* **Zoom Globe**: Scroll mouse wheel or pinch on mobile.
* **View Project**: Hover over or tap the glowing points/rays to display project cards at the bottom-right.
* **Project Cards**: Scroll through details or click "Read More" to navigate to the project page.

---

## Project Structure

```
/project-folder
__ index.html           # Main HTML file with globe container and project column
```

---

## Technologies Used

* **Three.js** – 3D graphics and rendering
* **OrbitControls** – Camera control (rotate, zoom)
* **HTML/CSS/JS** – Frontend interface and layout
* **WebGL** – Rendering 3D globe in browser
* **ShaderMaterial** – Custom shaders for glow and rays

---

## Customization

* **Add Projects**: Modify `projectData` array in the JavaScript section.
* **Change Globe Texture**: Replace the `globeTexture` URL with your preferred image.
* **Glow/Effects**: Adjust shader uniforms like `glowColor`, `opacity`, and `borderWidth`.

---

## Responsive Behavior

* **Desktop (>768px)**: Globe centered, project cards appear bottom-right.
* **Tablet (480px–768px)**: Adjusted globe size, project cards remain fixed.
* **Mobile (<480px)**: Globe scales to fit screen, project cards width reduced, touch interaction enabled.
