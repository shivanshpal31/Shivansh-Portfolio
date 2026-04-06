# 🌐 Shivansh Pal — Personal Portfolio Website

A modern, responsive **personal portfolio website** built with **React 18** and **Tailwind CSS**, featuring smooth animations powered by **Framer Motion**. The site is live-deployed on **Vercel** and showcases projects, skills, experience, and contact information in a clean single-page application.

🔗 **Live Site:** [shivansh-chi.vercel.app](https://shivansh-chi.vercel.app)

---

## 📌 Table of Contents

- [Overview](#overview)
- [Tech Stack](#tech-stack)
- [Features](#features)
- [Project Structure](#project-structure)
- [Sections](#sections)
- [Dependencies](#dependencies)
- [Getting Started](#getting-started)
- [Available Scripts](#available-scripts)
- [Deployment](#deployment)
- [Author](#author)

---

## Overview

This is a fully responsive **single-page portfolio application** designed to present Shivansh Pal's profile as a developer. It uses component-based React architecture, utility-first Tailwind CSS styling, and Framer Motion animations to deliver a polished, professional user experience across all devices.

The site uses **React Scroll** for smooth in-page navigation, **React Vertical Timeline** for a structured experience/education layout, and **React Icons** for a comprehensive icon set throughout the UI.

---

## Tech Stack

| Category | Technology |
|----------|------------|
| Framework | React 18.2 |
| Styling | Tailwind CSS 3.4 |
| Animations | Framer Motion 12 |
| Routing | React Router DOM 7 |
| Scroll Navigation | React Scroll 1.9 |
| Icons | React Icons 5.4 |
| Timeline UI | React Vertical Timeline Component 3.5 |
| Build Tool | Create React App (react-scripts 5) |
| Deployment | Vercel |
| Language | JavaScript (92.5%), CSS (4.3%), HTML (3.2%) |

---

## Features

- **⚡ Smooth Animations** — Page elements animate in using Framer Motion for a fluid, modern feel
- **📱 Fully Responsive** — Mobile-first design with Tailwind CSS, adapts seamlessly to all screen sizes
- **🧭 Smooth Scroll Navigation** — Section-based navigation using React Scroll with no page reloads
- **🗂️ Project Showcase** — Dedicated section highlighting key projects with descriptions and links
- **🛠️ Skills Display** — Visual representation of technical skills and tools
- **📅 Timeline Layout** — Experience and education displayed on a vertical timeline for easy readability
- **📬 Contact Section** — Direct contact information and/or form for reaching out
- **🚀 Deployed on Vercel** — Fast, globally distributed hosting with zero-config CI/CD

---

## Project Structure

```
Shivansh-Portfolio/
├── public/
│   ├── index.html          # HTML entry point
│   └── ...                 # Static assets (favicon, manifest)
├── src/
│   ├── components/         # Reusable React components (Navbar, Hero, About, etc.)
│   ├── assets/             # Images, icons, and other static files
│   ├── App.js              # Root component — assembles all sections
│   ├── index.js            # React DOM entry point
│   └── index.css           # Global styles + Tailwind directives
├── .gitignore
├── package.json            # Dependencies and scripts
├── tailwind.config.js      # Tailwind CSS configuration
└── README.md
```

---

## Sections

The portfolio is structured as a single-page application with the following sections:

| Section | Description |
|---------|-------------|
| **Hero / Home** | Introduction with name, role, and CTA buttons |
| **About** | Brief bio and personal background |
| **Skills** | Technical skills and tools with visual indicators |
| **Experience** | Work / internship history on a vertical timeline |
| **Projects** | Highlighted projects with descriptions, tech used, and GitHub links |
| **Education** | Academic background on a vertical timeline |
| **Contact** | Contact details and/or form for direct outreach |

---

## Dependencies

### Production
```json
"react": "^18.2.0"                          — Core UI library
"react-dom": "^18.2.0"                      — DOM rendering
"react-router-dom": "^7.1.5"               — Client-side routing
"react-scroll": "^1.9.2"                   — Smooth scroll to sections
"framer-motion": "^12.0.3"                 — Animations and transitions
"react-icons": "^5.4.0"                    — Icon library (Font Awesome, etc.)
"react-vertical-timeline-component": "^3.5.3" — Timeline for experience/education
"react-scripts": "5.0.1"                   — CRA build toolchain
```

### Dev Dependencies
```json
"tailwindcss": "3.4.17"    — Utility-first CSS framework
"autoprefixer": "^10.4.20" — CSS vendor prefixing
"postcss": "^8.5.1"        — CSS processing pipeline
```

---

## Getting Started

### Prerequisites

| Requirement | Version |
|-------------|---------|
| Node.js | 16+ |
| npm | 8+ |

### 1. Clone the Repository

```bash
git clone https://github.com/shivanshpal31/Shivansh-Portfolio.git
cd Shivansh-Portfolio
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Start Development Server

```bash
npm start
```

The app will run at **`http://localhost:3000`** and hot-reload on any file changes.

---

## Available Scripts

| Command | Description |
|---------|-------------|
| `npm start` | Runs the app in development mode at `localhost:3000` |
| `npm run build` | Builds the optimized production bundle to `/build` |
| `npm test` | Launches the test runner in interactive watch mode |
| `npm run eject` | Ejects CRA config (irreversible — use with caution) |

---

## Deployment

This project is deployed on **Vercel** with automatic continuous deployment from the `main` branch.

### Deploy Your Own Fork

**Option 1 — Vercel (Recommended)**

1. Fork this repository
2. Go to [vercel.com](https://vercel.com) and import your fork
3. Vercel auto-detects Create React App — no configuration needed
4. Every push to `main` triggers an automatic redeploy

**Option 2 — Manual Build**

```bash
npm run build
```

This generates an optimized production build in the `/build` folder. The contents can be served from any static hosting provider (Netlify, GitHub Pages, Firebase Hosting, etc.).

---

## Author

**Shivansh Pal**

- 🌐 Portfolio: [shivansh-chi.vercel.app](https://shivansh-chi.vercel.app)
- 💻 GitHub: [@shivanshpal31](https://github.com/shivanshpal31)

---

> **Skills Showcased:** React.js · Tailwind CSS · Framer Motion · JavaScript (ES6+) · Component Architecture · Responsive Design · Vercel Deployment
