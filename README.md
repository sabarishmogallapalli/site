# 🌐 Sabarish Mogallapalli — Personal Portfolio Website

> A responsive, modern personal portfolio website built with React and GitHub Pages to showcase software engineering projects, machine learning experience, and technical leadership.

## 🛠️ Badges & Tech Stack

[![React](https://img.shields.io/badge/React-18.x-61DAFB?logo=react&logoColor=black)](https://react.dev/)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6%2B-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![CSS3](https://img.shields.io/badge/CSS3-Styling-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![GitHub Pages](https://img.shields.io/badge/Deployment-GitHub%20Pages-222222?logo=github&logoColor=white)](https://pages.github.io/)

* **Live Site:** [sabarishmogallapalli.github.io/site](https://sabarishmogallapalli.github.io/site/)
* **Base Template:** Inspired by [React Portfolio Template by Yuji Sato](https://yujisatojr.github.io/react-portfolio-template/)

## 💡 The Problem & Solution

**The Problem:** Recruiters, hiring managers, and prospective collaborators often need a clean, single-page platform to evaluate an engineer's technical background, machine learning projects, and professional timeline without navigating through cluttered resumes or scattered links.

**The Solution:** This repository houses a streamlined, interactive single-page portfolio application. Built on top of Yuji Sato's open-source React portfolio foundation and heavily customized, it provides an organized presentation of technical skills, featured engineering projects, professional experience, and direct contact channels in a mobile-responsive format.

## ⚙️ System Architecture & Data Flow

```
[ Local Development ] ──( npm run build )──► [ Production Static Bundle ]
                                                        │
                                                        ▼
                                           [ gh-pages Deployment ]
                                                        │
                                                        ▼
[ Visitor Browser ] ◄──( CDN Service )────── [ GitHub Pages Host ]
```

### Key Technical Highlights:

1. **Component Architecture:** Structured with modular React functional components (`Header`, `About`, `Projects`, `Skills`, `Experience`, `Footer`) to maintain clean separation of concerns.
2. **Centralized Data Layer:** Portfolio assets, project descriptions, skills listings, and social links are managed via unified configuration files, allowing rapid content updates without modifying UI rendering logic.
3. **Automated Continuous Deployment:** Integrated with `gh-pages` build pipeline scripts to compile optimized production assets and automatically host static files on GitHub Pages.

## 🚀 Local Setup Instructions

Follow these step-by-step terminal commands to run, modify, or deploy the portfolio website locally:

### 1. Prerequisites

Ensure you have **Node.js** (v16+) and **npm** installed on your system.

### 2. Clone the Repository

```bash
git clone https://github.com/sabarishmogallapalli/site.git
cd site
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Run Development Server

```bash
npm start
```

Open [http://localhost:3000](http://localhost:3000) to view the application live in your browser.

### 5. Build & Deploy to GitHub Pages

```bash
# Compile optimized static build and release to GitHub Pages
npm run deploy
```