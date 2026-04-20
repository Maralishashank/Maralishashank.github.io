<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1e1b4b,50:3b82f6,100:06b6d4&height=180&section=header&text=Marali%20Shashank%20—%20Portfolio&fontSize=38&fontColor=ffffff&fontAlignY=40&desc=Java%20Backend%20Developer%20%7C%20Spring%20Boot%203%20%7C%20React%2018%20%7C%20AZ-900&descAlignY=62&descSize=15&animation=fadeIn"/>

<br/>

[![Portfolio Live](https://img.shields.io/badge/🌐_Portfolio_Live-3b82f6?style=for-the-badge)](https://maralishashank.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/marali-shashank/)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:maralishashank@gmail.com)
[![SMS Live Demo](https://img.shields.io/badge/SMS_Project_Demo-06b6d4?style=for-the-badge&logo=vercel&logoColor=white)](https://student-management-system-self-one.vercel.app)

<br/>

![Built With](https://img.shields.io/badge/Built_With-HTML5_%2F_CSS3_%2F_JS-E34F26?style=flat-square&logo=html5&logoColor=white)
![No Framework](https://img.shields.io/badge/Zero_Dependencies-Pure_CSS_%2B_Vanilla_JS-4ade80?style=flat-square)
![GitHub Pages](https://img.shields.io/badge/Hosted_On-GitHub_Pages-181717?style=flat-square&logo=github&logoColor=white)
![Status](https://img.shields.io/badge/Status-Live_%E2%9C%85-4ade80?style=flat-square)

</div>

---

## 📌 Overview

This repository contains the source code for my **personal developer portfolio website**, hosted on GitHub Pages at [maralishashank.github.io](https://maralishashank.github.io).

The portfolio is a **single-file, zero-dependency** HTML/CSS/JavaScript website showcasing my skills, projects, experience, education, and certifications. No React, no Bootstrap, no build step — just a single `index.html` with a fully custom dark design system.

---

## ✨ Features

- 🌑 **Dark theme** — deep navy/slate colour palette with grain texture overlay
- 🔤 **Premium typography** — `Sora` (body) · `DM Serif Display` (headings) · `JetBrains Mono` (code/labels)
- 🎞️ **Scroll-reveal animations** — IntersectionObserver-based fade-up reveals on every section
- ⌨️ **Typing animation** — cycling through roles in the hero section
- 📸 **Project photo banners** — actual screenshots with gradient overlays and floating tech badges
- 📱 **Fully responsive** — mobile, tablet, desktop
- 📬 **Working contact form** — connected to Formspree (AJAX, no page reload)
- ⬆️ **Back-to-top button** — appears after scrolling
- 🚫 **Zero dependencies** — no npm, no build process, no external CSS frameworks

---

## 🗂️ Repository Structure

```
maralishashank.github.io/
│
├── index.html                  # Entire portfolio — HTML + CSS + JS in one file
├── Marali_Shashank_Resume.pdf  # Downloadable resume
├── README.md                   # This file
│
├── img/
│   ├── student-ss.png          # Student Management System screenshot
│   ├── diabities.png           # Diabetes Prediction screenshot
│   ├── azure-cert.png          # Azure AZ-900 certificate badge
│   └── hackerrank-cert.png     # HackerRank SQL certificate badge
│
├── css/                        # Legacy files (not used by new index.html)
├── js/                         # Legacy files (not used by new index.html)
└── lib/                        # Legacy files (not used by new index.html)
```

> ✅ The entire website lives in `index.html`. All CSS and JavaScript are inline — no external stylesheets or scripts required.

---

## 🎨 Design System

The portfolio uses a fully custom CSS design system defined as CSS variables:

| Token | Value | Usage |
|---|---|---|
| `--bg` | `#07090f` | Page background |
| `--surface` | `#131c2e` | Card backgrounds |
| `--primary` | `#3b82f6` | Accent blue — buttons, links, badges |
| `--cyan` | `#22d3ee` | Secondary accent — headings italic, timeline |
| `--text` | `#dde4f0` | Primary text |
| `--ff` | `Sora` | Body font |
| `--ffd` | `DM Serif Display` | Display/heading font |
| `--ffm` | `JetBrains Mono` | Code, labels, monospace |

---

## 📄 Sections

| Section | Description |
|---|---|
| **Hero** | Name, typing role animation, location, CTA buttons, social links, info card |
| **About** | Bio, meta info, skills grouped by category |
| **Experience & Education** | Timeline with internship and education history |
| **Skills** | 8 skill cards covering Java, Spring Boot, JWT, MySQL, React, Docker, Azure, JUnit 5 |
| **Projects** | SMS (featured, with screenshot + live demo) · Diabetes Prediction |
| **Certifications** | Azure AZ-900 + HackerRank SQL with verify links |
| **Contact** | Info cards + Formspree contact form |

---

## 🚀 Projects Showcased

### 🎓 Student Management System
> Spring Boot 3 · Spring Security 6 + JWT · React 18 · MySQL · Docker · JUnit 5 · Swagger UI

Production-grade full-stack web application with Admin & Student RBAC, 9 REST controllers, 15+ secured endpoints, and a custom React UI.

[![Live Demo](https://img.shields.io/badge/Live_Demo-3b82f6?style=flat-square)](https://student-management-system-self-one.vercel.app)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github)](https://github.com/Maralishashank/student-management-system)

---

### 🩺 Diabetes Disease Prediction
> Python · Django · Scikit-learn · Pandas · Matplotlib

ML-powered healthcare app — 5 classification algorithms evaluated on the Pima Indians dataset, KNN achieved 76% accuracy.

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github)](https://github.com/Maralishashank/Diabetes-Disease-Prediction)

---

## 🛠️ How to Run Locally

No build step needed. Just open the file in a browser:

```bash
# Clone the repository
git clone https://github.com/Maralishashank/maralishashank.github.io.git

# Navigate into it
cd maralishashank.github.io

# Open directly in browser
open index.html
# or on Windows:
start index.html
```

Or use VS Code's **Live Server** extension for hot-reload during development.

---

## 📦 How to Deploy Changes

The site is hosted on **GitHub Pages** and deploys automatically on every push to `main`.

```bash
# Make your changes to index.html
# Then commit and push:

git add index.html
git commit -m "Update portfolio content"
git push origin main

# GitHub Pages will redeploy within ~60 seconds
# Live at: https://maralishashank.github.io
```

---

## 📬 Contact Form Setup

The contact form uses **Formspree** (endpoint `xjggkvag`). Messages are sent via AJAX — no page reload, no backend required.

To use your own Formspree endpoint:
1. Sign up at [formspree.io](https://formspree.io)
2. Create a new form and copy your endpoint ID
3. In `index.html`, find `action="https://formspree.io/f/xjggkvag"` and replace the ID

---

## 👤 About Me

**Marali Shashank** — Java Backend Developer, 2025 B.Tech IT Graduate, Hyderabad.

- 📧 [maralishashank@gmail.com](mailto:maralishashank@gmail.com)
- 📱 +91 6305516008
- 💼 [linkedin.com/in/maralishashank](https://www.linkedin.com/in/marali-shashank/)
- 🐙 [github.com/Maralishashank](https://github.com/Maralishashank)
- 🌐 [maralishashank.github.io](https://maralishashank.github.io)

---

## 📜 License

This project is open source under the [MIT License](LICENSE). Feel free to use it as inspiration for your own portfolio — just don't copy the content directly.

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:06b6d4,50:3b82f6,100:1e1b4b&height=100&section=footer&animation=twinkling"/>

**⭐ If you found this helpful, consider giving the repo a star!**

</div>
