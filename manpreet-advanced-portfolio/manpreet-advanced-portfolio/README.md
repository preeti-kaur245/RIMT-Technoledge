# Manpreet Kaur — Advanced Portfolio

A responsive, animated personal portfolio built using **HTML5, CSS3 and vanilla JavaScript only**. No React, Bootstrap, Tailwind, npm or build tools are required.

## Features
- Responsive desktop and mobile layouts
- Animated hero artwork and ambient pointer glow
- Scroll progress indicator
- Scroll-triggered reveal animations with reduced-motion support
- Interactive project category filters
- Mobile navigation menu
- CSS-built project mockups (no image assets required)
- Contact link using `mailto:`

## Run locally
1. Download or clone this repository.
2. Open `index.html` in a browser.

For a local development server, use VS Code Live Server or run:
```bash
python -m http.server 5500
```
Then visit `http://localhost:5500`.

## Before publishing
Search `index.html` and replace:
- `https://github.com/` project placeholders with the actual repository URLs.
- Project descriptions/technology stacks with the exact implementation details.
- Email and social links if they change.
- Add a real resume PDF only if you want a resume download link.

## Deploy on GitHub Pages
1. Create a public GitHub repository, for example `advanced-portfolio`.
2. Upload `index.html`, `style.css`, `script.js` and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select `main` and `/ (root)`, then save.
6. Wait for GitHub Pages to publish the site.

## Project structure
```text
advanced-portfolio/
├── index.html
├── style.css
├── script.js
└── README.md
```

## Academic note
This project demonstrates semantic HTML, responsive CSS layouts, keyframe animations, CSS transitions, Intersection Observer, DOM manipulation, event listeners and accessible interaction patterns.
