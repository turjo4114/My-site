<div align="center">
Sadid Ahmed Turjo — Portfolio
Engineer · AI explorer · Photographer
A fast, single-page personal portfolio built with plain HTML, CSS and JavaScript. No frameworks, no build step.
LinkedIn · GitHub · Instagram
![Hero](assets/screenshots/hero.png)
</div>
Highlights
Class selector hero – Builder, Explorer and Researcher cycle automatically with animated stat bars, a progress-fill button and an accent colour that re-themes the whole page. Hover pauses it; clicking a class takes manual control.
Project explorer – filterable project cards with a detail dialog.
Beyond code – a music visualizer and a photography gallery with a lightbox.
Light and dark theme – follows the system setting and remembers your choice.
Typewriter intro, scroll progress bar and reveal-on-scroll sections.
Responsive and accessible – mobile menu, keyboard focus styles, ARIA labels, and `prefers-reduced-motion` support.
Screenshots
Projects	Beyond code
![Projects](assets/screenshots/projects.png)	![Beyond code](assets/screenshots/beyond.png)
Tech
HTML5 · CSS3 (custom properties, `color-mix`, `@property`, grid) · Vanilla JavaScript · Google Fonts (Bricolage Grotesque, Figtree)
Project structure
```
turjo-portfolio/
├── index.html          # markup, styles and scripts in one file
├── assets/
│   ├── turjo.png       # hero portrait
│   ├── photos/         # photography gallery images
│   └── screenshots/    # images used in this README
└── README.md
```
Run locally
```bash
git clone https://github.com/turjo4114/turjo-portfolio.git
cd turjo-portfolio
# just open index.html, or serve it:
python3 -m http.server 8000
```
Then visit http://localhost:8000. An internet connection is only needed for Google Fonts.
Customise
Photos: drop images into `assets/photos/` and add `['file.jpg', 'description']` to the `photos` array near the bottom of `index.html`.
Projects: edit the `P` array in the script.
Classes and stats: edit the `CL` object. Cycle speed is `DUR` (milliseconds).
Colors: change the CSS variables in `:root`.
Deploy
GitHub Pages: push the repo, then Settings → Pages → deploy from the `main` branch root.
Netlify / Vercel: drag and drop the folder, or connect the repo.
Contact
Open to projects, internships and research collaborations. Find me on LinkedIn.
---
<div align="center"><sub>Build. Break. Learn. Repeat.</sub></div>
