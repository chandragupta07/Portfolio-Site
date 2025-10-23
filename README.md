# Chandragupta Maurya — Portfolio Website

A simple responsive portfolio website built with HTML, CSS and a small amount of JavaScript. It showcases profile, about, experience, projects and contact sections.

## Features
- Clean, responsive layout for desktop and mobile
- Projects section with links to GitHub and live demos
- Downloadable resume and contact links
- Accessible mobile hamburger menu and keyboard support

## Technologies
- HTML5
- CSS3 (style.css, mediaquery.css)
- Vanilla JavaScript (script.js)
- Static assets in the `assets/` folder

## Project structure
- index.html — main markup
- style.css — primary styles
- mediaquery.css — responsive rules
- script.js — interactive behavior (hamburger toggle, etc.)
- assets/ — images, icons and Resume.pdf
- README.md — this file

## Quick start (view locally)
1. Clone or copy the project folder to your machine.
2. Open `index.html` directly in a browser, or serve the folder to avoid CORS issues for some assets:
   - Using Python 3: `python -m http.server 8000`
   - Then open: `http://localhost:8000/`

## Notes & improvements
- Fonts and color variables can be moved into CSS variables for easier theming.
- Consider optimizing images (webp) and adding lazy-loading for performance.
- Extract any embedded styles or scripts into external files for maintainability.
- Add simple unit of accessibility checks (alt text, ARIA roles) where missing.

## Contributing
- Feel free to open issues or submit pull requests. Keep changes small and focused.
- Update README with any new scripts, build steps or dependencies you add.

## Author / Contact
Chandragupta Maurya  
LinkedIn: https://www.linkedin.com/in/chandragupta01/  
GitHub: https://github.com/chandragupta07

## License
Use and modify freely. Add a LICENSE file if you want a specific open-source license.
