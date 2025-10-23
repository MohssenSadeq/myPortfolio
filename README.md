# Mohssen Sadeq – Portfolio

A modern, fully responsive portfolio showcasing my journey as a Systems Administrator and Cloud Engineer. Built to give hiring managers and collaborators a polished view into my background, projects, and tooling expertise.

![License](https://img.shields.io/badge/license-MIT-0b0d12?style=flat-square)
![Built with](https://img.shields.io/badge/Built%20with-HTML5%20%7C%20CSS3%20%7C%20JS-004d40?style=flat-square)
![Hosted on](https://img.shields.io/badge/Hosted%20on-AWS%20S3%20%7C%20CloudFront-ffb300?style=flat-square)

## 🧭 Overview

- **Live Site:** https://msadeq.de/
- **Focus:** Present experience, projects, skills, education, and contact info in a premium single-page experience.
- **Tech:** Vanilla HTML/CSS/JS with Typed.js for hero animation, custom styling for light/dark themes, and responsive layouts tuned for devices of all sizes.

## ✨ Highlights

- Sticky navigation with scroll-aware section highlighting and theme toggle (dark/light).
- Hero banner mirroring a personal brand palette and type pairing (Playfair Display + Poppins).
- Cards and grids for Experience, Projects, Skills, and Education, each designed to reduce visual noise while surfacing key facts quickly.
- Contact section with inline SVG icons and actionable links (phone, mail, GitHub, LinkedIn).

## 🚀 Getting Started

1. **Clone the repo**
   ```bash
   git clone https://github.com/your-username/myPortfolio.git
   cd myPortfolio
   ```
2. **Serve locally** (optional but recommended)
   ```bash
   python3 -m http.server
   ```
   Visit `http://localhost:8000` to preview changes.
3. **Customize content**
   - Update `index.html` text/image references.
   - Replace assets in `assets/img/` as needed.
   - Adjust styling in `assets/css/style.css` (variables defined at the top enable quick palette changes).

## 🧱 Structure

```
myPortfolio/
├── index.html           # Main single-page site
├── assets/
│   ├── css/style.css    # Custom styling + media queries + theme overrides
│   └── img/             # Portrait, project thumbnails, favicons
├── assets/vendor/       # Third-party scripts (Typed.js)
└── readme1              # Alternate profile README for GitHub
```

## ☁️ Deployment

I host the site on **AWS S3** with **CloudFront** for global distribution and **Route 53** for DNS. You can deploy in a few ways:

- **GitHub Pages:** Push to `<username>.github.io` and enable pages.
- **AWS S3 + CloudFront (recommended):** Upload the build to S3, set up CloudFront for CDN caching, and point your custom domain via Route 53.
- **Any static host** (Netlify, Vercel, etc.) works since it’s plain HTML/CSS/JS.

## 🔧 Tooling

- **Typed.js** – Hero typing animation.
- **SVG & Shields.io** – For crisp icons and badges.
- **Custom CSS** – No heavy frameworks; just handcrafted styles for better control.

## 📝 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

---

> Built with passion for precision, resilience, and storytelling – the same qualities I bring to infrastructure and cloud engineering.
