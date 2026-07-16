# Portfolio — Jissin Kochumannarthu Jose

A personal portfolio website showcasing my work as a Frontend Developer and Research Assistant at inIT, TH OWL. Built with vanilla HTML, CSS, and JavaScript — no frameworks, no dependencies, just clean code.

**Live:** [jissinkochumannarathu.github.io/portfolio](https://jissinkochumannarathu.github.io/portfolio)

---

## About Me

I'm currently pursuing an M.Sc. in Information Technology at TH OWL in Lemgo, Germany, while working as a Research Assistant at the inIT institute. My focus is frontend development — building responsive SPAs with Angular and TypeScript, integrating REST APIs, and contributing to research software in Agile environments. I'm expanding into React, cloud-native architectures, and CI/CD practices.

This portfolio serves as a central hub for my projects, skills, and professional background. It's also the site I share when recruiters and collaborators ask to see my work.

---

## What's Inside

| Section | Description |
|---|---|
| **Hero** | Quick intro with title, location, and contact links |
| **About** | Professional summary and key facts |
| **Skills** | Frontend, backend, mobile, ML, DevOps, and soft skills with proficiency bars |
| **Experience** | Timeline of my Research Assistant role at inIT TH OWL |
| **Projects** | Six key projects with tech stacks — research, academic, and published work |
| **Education** | M.Sc. IT at TH OWL and B.Tech CSE at APJ KTU |
| **Certifications** | NPTEL, Oracle Academy, LinkedIn Learning, Coursera |
| **Contact** | Email, phone, location, LinkedIn, and a working contact form |

---

## Projects Highlighted

- **PD Assist** — Cross-platform Flutter app for Parkinson patient monitoring (inIT TH OWL)
- **AI-Assisted Learning Interaction Study** — Angular/TypeScript research platform with Python/MongoDB backend
- **Aircraft Nose Gear Pose Estimation** — Deep learning system achieving 91.5% accuracy with ResNet18 and PyTorch
- **Alzheimer's Disease Detection** — Published at NACORE 2023 using ResNet and DenseNet architectures
- **Municipal Complaint Management System** — Next.js + Firebase web app for public service feedback
- **XY Plotting Robot (SCARA)** — Arduino-based robotic 2D plotter with embedded C control

---

## Tech Stack (This Site)

- **HTML5** — Semantic, accessible structure
- **CSS3** — Custom properties, grid, flexbox, animations, responsive design
- **JavaScript (Vanilla)** — Intersection Observer API for scroll animations, smooth scrolling, mobile navigation, form handling
- **Font Awesome** — Icon library

No build tools, no npm, no frameworks. The site is fully static and deployable on any hosting platform (GitHub Pages, Netlify, Vercel, or a simple nginx server).

---

## Setup & Deployment

### Local Development

```bash
git clone https://github.com/JissinKochumannarathu/portfolio.git
cd portfolio
```

Open `index.html` in your browser, or serve it with any static server:

```bash
npx serve .
# or
python -m http.server 8000
```

### Deploy to GitHub Pages

The site is automatically deployed via GitHub Pages from the `main` branch. To deploy your own:

1. Push to the `main` branch
2. Go to repository Settings → Pages
3. Set Source to "Deploy from a branch" and select `main` → `/ (root)`
4. Your site will be live at `https://<username>.github.io/portfolio`

---

## Repository Structure

```
portfolio/
├── index.html          # Main HTML document with all sections
├── style.css           # Complete stylesheet (CSS custom properties, responsive)
├── script.js           # Vanilla JS for interactivity and animations
├── CV.md               # Markdown version of my CV
├── Jissin_CV_SAP_Fioneer.pdf   # PDF CV (original)
└── README.md
```

---

## Design Decisions

- **No frameworks** — Chose vanilla HTML/CSS/JS to keep the site lightweight, fast, and easy to deploy. No `node_modules`, no build step, no runtime overhead.
- **CSS custom properties** — Centralized color palette, spacing, and typography for consistent theming.
- **Mobile-first responsive** — Grid and flexbox layouts adapt seamlessly from 320px to 4K screens.
- **Accessibility** — Semantic HTML5 elements, proper heading hierarchy, ARIA-friendly navigation.
- **Performance** — No external dependencies (except Font Awesome CDN), minimal CSS footprint, lazy animations via Intersection Observer.

---

## Contact

- **Email:** jissinkjose2018@gmail.com
- **Phone:** +49 163 702 4019
- **LinkedIn:** [linkedin.com/in/jissin-k-jose-6b65831b1](https://www.linkedin.com/in/jissin-k-jose-6b65831b1/)
- **Location:** Lemgo, NRW, Germany

---

*Built with care. No templates, no shortcuts.*
