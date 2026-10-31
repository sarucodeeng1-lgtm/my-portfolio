# Sarika Sindhu | 3D Portfolio

An immersive, scroll-driven 3D portfolio website inspired by [igloo.inc](https://www.igloo.inc/). As you scroll, the camera travels through a field of ice crystals, and each section of my resume appears alongside a rotating 3D crystal.

**Live site:** [sarucodeeng1-lgtm.github.io/my-portfolio](https://sarucodeeng1-lgtm.github.io/my-portfolio/)

---

## Features

- **Scroll-driven 3D scene.** The camera flies forward through floating crystals while the main crystal rotates and shifts sides for each section.
- **Orbiting skill tags.** Two tilted rings of skill tags circle the crystal in the skills section, with depth-based size and fade.
- **Frosted-glass UI.** Content cards use a blurred, translucent style that matches the icy theme.
- **Falling snow.** A particle system of 900 points adds depth and motion.
- **Pointer parallax.** The camera follows the mouse for a subtle 3D feel.
- **Responsive.** Layout and 3D scale adapt to phones and tablets.
- **Accessible.** Respects `prefers-reduced-motion`, has visible keyboard focus states, and falls back to a gradient if WebGL is unavailable.

## Sections

| Section | What it shows |
| --- | --- |
| Hero | Name and one-line introduction |
| About | Summary of my background and training |
| Skills | Tools in orbit around the 3D crystal |
| Projects | Easily Job Portal, Expense Tracker, Stock Market Portfolio, each with a live demo |
| Training | Coding Ninjas certification, BCA at LPU, and upcoming coursework |
| Contact | Email and phone |

## Tech Stack

- **HTML5, CSS3, JavaScript (ES5/ES6)** for structure, styling and logic
- **[Three.js](https://threejs.org/) r128** for the WebGL 3D scene
- **CSS** backdrop blur, gradients and custom properties for the glass design
- **Google Fonts (Sora)** for typography
- **GitHub Pages** for hosting

The whole site is a single self-contained `index.html` file with no build step.

## Run Locally

```bash
git clone https://github.com/sarucodeeng1-lgtm/my-portfolio.git
cd my-portfolio
```

Then either open `index.html` in a browser, or serve it locally:

```bash
npx serve
# or
python -m http.server 8000
```

An internet connection is needed because Three.js and the font load from CDNs.

## Project Structure

```
my-portfolio/
├── index.html   # markup, styles and the Three.js scene
└── README.md
```

## Featured Projects

- **[Easily Job Portal](https://easily-job-portal-wh2u.onrender.com/)**: Node.js, Express.js, EJS. Recruiter and job-seeker workflows, session-based authentication, role-based access and resume upload.
- **[Expense Tracker](https://expense-tracker-y3vg.onrender.com/)**: React.js, Node.js, Express.js, MongoDB Atlas. Full-stack app with REST APIs and a dashboard of balance, income and expenses.
- **[Stock Market Portfolio](https://sarucodeeng1-lgtm.github.io/stock-market-analysis/)**: HTML, CSS, JavaScript, Chart.js. Portfolio interface with data visualisation.

## Contact

- **Email:** [sarikasindhu1@gmail.com](mailto:sarikasindhu1@gmail.com)
- **GitHub:** [@sarucodeeng1-lgtm](https://github.com/sarucodeeng1-lgtm)

---

&copy; Sarika Sindhu. Feel free to take inspiration from this project, but please do not copy it as your own portfolio.
