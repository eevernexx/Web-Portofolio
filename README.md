# Aryasatya Muhammad Aqsel — Personal Portfolio

A single-page personal portfolio website for **Aryasatya Muhammad Aqsel**, a Data Scientist and Computer Science graduate from University of Dian Nuswantoro (UDINUS). Built with vanilla HTML, CSS, and JavaScript — animated with GSAP, deployed on Vercel.

**Live site:** https://web-portofolio-nu-one.vercel.app/

---

## Overview

A modern, dark-themed portfolio designed around a single-file architecture for fast load and zero build steps. The site highlights services, selected projects, peer-reviewed research, certifications, and contact channels — all in one continuous scrollable experience.

## Features

- **Custom cursor** with hover-reactive ring (desktop only)
- **GSAP-powered animations** — hero entrance, scroll reveals, parallax, smooth scroll
- **Responsive layout** with a dedicated mobile menu and adaptive grids
- **Tech stack grid** with devicon SVG logos (lazy-loaded)
- **Portfolio filter** by category — Website / Web App / Dashboard
- **Featured publication** card linking to the JAIC journal paper
- **Certifications & internships** section (BNSP, Diskominfo, MySkill, etc.)
- **Contact form** that opens a pre-filled email via `mailto:`
- **Downloadable CV** (PDF)
- **Subtle noise overlay** and gradient hero shapes for depth
- **Smooth section-based navigation** with active-state tracking

## Sections

1. **Hero** — name, role, social links, CTA, tech stack grid
2. **Education & Languages** — UDINUS, Global Madani, language proficiency
3. **Services** — Machine Learning, Computer Vision, Data Analysis, Predictive Modeling, Data Visualization & Dashboards, Web Development
4. **Portfolio** — Live projects (F1 Strategy Dashboard, Jakarta Air Quality EDA, Gue Ngekost, PaperStory, this site)
5. **Research** — *A Roasted Coffee Bean Identification Using ResNet50 Model* (JAIC, Dec 2025)
6. **Certifications** — BNSP Associate Data Scientist, AI Literacy, Diskominfo internship, UX Writing
7. **About** — short bio and visual block
8. **Contact** — email, social, contact form

## Tech Stack

- **Markup & Styling:** HTML5, CSS3 (custom properties, clamp-based fluid typography)
- **Scripting:** Vanilla JavaScript (ES2020)
- **Animation:** [GSAP](https://greensock.com/gsap/) — `ScrollTrigger`, `ScrollToPlugin`
- **Fonts:** Syne, DM Sans, Clash Display (Google Fonts)
- **Icons:** [devicon](https://devicon.dev/) via jsDelivr CDN
- **Hosting:** [Vercel](https://vercel.com/)

No build step. No framework. No package manager. Just open `index.html`.

## Project Structure

```
.
├── index.html              # The entire site — markup, styles, scripts
├── CV.pdf                  # Downloadable CV
├── *.png / *.jpg           # Project thumbnails, logos, hero image
├── Sertifikat *.pdf        # Certificate files linked from the Credentials section
├── .gitignore
└── README.md
```

## Getting Started

Clone the repo and open `index.html` in a browser — that's it.

```bash
git clone https://github.com/eevernexx/Web-Portofolio.git
cd Web-Portofolio
# Open index.html directly, or serve it locally:
python -m http.server 5500
# then visit http://localhost:5500
```

> A local HTTP server is recommended so that relative asset paths (PDFs, images) resolve cleanly.

## Deployment

The site is deployed on Vercel as a static project — no framework preset required.

1. Push to GitHub.
2. Import the repository on [vercel.com](https://vercel.com/new).
3. Framework preset: **Other**. Output directory: project root.
4. Deploy.

## Featured Projects

| Project | Category | Live |
|---|---|---|
| F1 Dashboard Visualization | Dashboard | https://f1-strategy-dashboard-phi.vercel.app/ |
| Jakarta Air Quality EDA | Dashboard | https://eda-project-indonesia-urban-air-qua.vercel.app/ |
| Gue Ngekost | Web App | https://aplikasi-gue-ngekost.vercel.app/ |
| PaperStory | Web App | https://paper-story-five.vercel.app/ |
| Personal Portfolio | Website | https://web-portofolio-nu-one.vercel.app/ |

## Publication

**A Roasted Coffee Bean Identification Using ResNet50 Model**
Aryasatya Muhammad Aqsel, Eko Hari Rachmawanto
*Journal of Applied Informatics and Computing (JAIC)*, Vol. 9, No. 6, Dec 2025
[Read paper ↗](https://jurnal.polibatam.ac.id/index.php/JAIC/article/view/11460)

## Contact

- **Email:** [aryasatyaaqsel@gmail.com](mailto:aryasatyaaqsel@gmail.com)
- **LinkedIn:** [aryasatya-muhammad-aqsel](https://www.linkedin.com/in/aryasatya-muhammad-aqsel-38bb553b1)
- **Instagram:** [@aqselll](https://www.instagram.com/aqselll)
- **GitHub:** [@eevernexx](https://github.com/eevernexx)

## License

© 2026 Aryasatya Muhammad Aqsel. All rights reserved.
Source code is published for reference; assets (photos, CV, certificates, project thumbnails) are personal and not licensed for reuse.
