# Morphing Shape Studio
An interactive, premium 3D creative playground built with **Three.js** exploring fluid geometry morphs, physically based rendering (PBR) materials, responsive lighting systems, and tactile touch interactions.
✨ **[Live Demo](https://your-username.github.io/your-repo-name/)** *(Replace with your GitHub Pages URL once published)*
---
## 🎨 Visual Preview & Features
Morphing Shape Studio is a self-contained, lightweight 3D sandbox designed with a clean, glassmorphic UI. It features:
*   **Fluid Morphing Physics:** Smooth transitions between 6 distinct geometries using custom spring mechanics and vertex interpolation.
    *   *Blob:* A dynamically vibrating, breathing noise-deformed organic mass.
    *   *Sphere:* A pristine, perfect unit sphere highlighting pure reflections.
    *   *Torus Knot:* A complex parametric curve with Frenet-frame tube mapping.
    *   *Cube:* A sharp box with rounded edges.
    *   *Crystal:* A low-poly, faceted crystal projection.
    *   *Cone:* A mathematically clean cone structure.
*   **Tactile Deformations:** Hover, drag, or touch to "push" and deform the shape surface with elastic spring physics.
*   **Physically Based Materials (PBR):**
    *   *Holographic:* A highly metallic (95%), ultra-glossy iridescent pearl foil reflecting shifting rainbow spectrums using viewing-angle iridescence.
    *   *Liquid Metal:* A mirror-like, high-reflectivity liquid mercury finish.
    *   *Frosted Glass:* High-transmission glass featuring thickness-based absorption and internal refraction.
    *   *Matte Clay:* A soft, tactile chalk surface with a gentle velvet sheen.
    *   *Wireframe:* A glowing lattice overlay with a secondary semi-transparent dark hull for visual weight.
    *   *Neon Glow:* A transparent glass shell containing a volumetric, self-luminous gas tube with a pulsating heartbeat aura.
*   **Color-Adaptive Lighting & Moods:** Dynamic environmental themes (**Aurora**, **Ember**, **Arctic**, **Void**, and **Prism**) that proceduraly rebuild the scene reflection maps (specular spots) and transition ambient lights, directional fills, and UI accents to match your active theme or custom colors.
*   **Fully Responsive & Keyboard Assisted:** Glassmorphic dashboard panel that collapses into a drawer on mobile viewports. Includes hotkeys (`1`-`6` for shapes, `Q`-`Y` for materials, `Space` to toggle auto-rotation).
---
## 🛠️ Technology Stack
*   **Core:** HTML5, CSS3, JavaScript (ES6 Modules)
*   **3D Render Engine:** Three.js (WebGL 2, ACES Filmic Tone Mapping, Perspective Camera)
*   **Lighting Utilities:** PMREM Generator (Procedural reflection map generator) & RectAreaLight Uniforms
*   **Math:** 3D Simplex Noise algorithm for stable, organic deformation vibrations
---
## 🚀 Getting Started
No installation, complex builds, Node modules, or bundlers are required. The project is completely self-contained.
### Local Execution
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```
2. Rename the main file to `index.html` so Web Servers recognize it as the home page:
   ```bash
   mv morphing-shape-studio.html index.html
   ```
3. Run a local web server (e.g. VS Code's **Live Server** extension, or Python's HTTP module):
   ```bash
   # Python 3
   python -m http.server 8000
   ```
4. Open `http://localhost:8000` in your web browser.
---
## 🌐 Deploy to GitHub Pages
Since the project is a static site (HTML, JS, CSS), you can host it for free on **GitHub Pages** in under 1 minute:
1. Create a public repository on GitHub.
2. Push your files (ensure `morphing-shape-studio.html` is renamed to `index.html`).
3. In your GitHub repository:
   *   Go to **Settings** (gear icon).
   *   Scroll down to the **Pages** tab on the left sidebar.
   *   Under **Build and deployment**, set **Source** to `Deploy from a branch`.
   *   Select the `main` (or `master`) branch and folder `/ (root)`.
   *   Click **Save**.
4. Within a few seconds, GitHub will provide a link (e.g., `https://your-username.github.io/your-repo-name/`) where your project is live globally!
---
## 📄 License
This project is open-source and available under the [MIT License](LICENSE).
