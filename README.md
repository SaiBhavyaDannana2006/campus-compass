# 🧭 Campus Compass: The Ultimate Amrita Amaravati Fresher's Guide

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![FontAwesome](https://img.shields.io/badge/Font_Awesome-337ab7?style=for-the-badge&logo=font-awesome&logoColor=white)](https://fontawesome.com/)

An architectural, responsive multi-page student handbook designed for incoming freshers joining **Amrita Vishwa Vidyapeetham, Amaravati** for the **July 2026 batch**. Written from an authentic "senior-to-junior" perspective, this platform bridges the gap between high school and rigorous university engineering streams.

---

## 🌟 Key Features & Architecture

The application is engineered as a clean, modular multi-page system rather than a standard monolithic single-page scroll. It consists of **6 dedicated entry modules**:

1. **🏡 Core Dashboard (`index.html`)** – An empathetic landing gateway presenting welcoming context and a dashboard router navigating to technical subsets.
2. **📚 Academic Blueprint (`academics.html`)** – Practical syllabus structural guidelines covering continuous evaluation patterns (P1, P2, Lab metrics) and a clear alert infrastructure regarding the non-negotiable **75% minimum attendance threshold**.
3. **🤝 Campus Ecology (`clubs.html`)** – A balanced 2-column directory sorting technical production hubs from cultural/sports societies, including precise timeline mappings for annual recruitment cycles.
4. **🏢 Residential Lifecycles (`hostel.html`)** – Detailed chronological daily schedules, dining breakdowns, and an essential physical deployment packing checklist.
5. **🛡️ Senior Survival Matrix (`survival.html`)** – A modular side-by-side behavioral matrix tracking high-yield operational "Do's" against severe academic "Don'ts" (such as plagiarism penalties and curfew boundaries).
6. **🔥 The Curated Sandbox (`tools.html`)** – A premium, high-fidelity resource directory containing specialized, field-vetted toolkits for **CSE, AI, Data Science, and CCE** freshers, mimicking modern premium software directories.

---

## 🎨 UI/UX Design System

The application features a tailored design token system implemented natively through utility classes:

| Token Type | Value / Hex Code | Application Target |
| :--- | :--- | :--- |
| **Primary Brand** | `Amrita Maroon (#800020)` | Header accents, title typography, primary buttons |
| **Accent Glow** | `Warm Gold (#D4AF37)` | Badges, callouts, micro-interactions, metrics |
| **Layout Layer** | `Light Blue-Tint (#F9FAFB)` | Global viewport layout canvas backgrounds |
| **Component Layer**| `Pure White (#FFFFFF)` | Large rounded layout cards (`rounded-3xl`) |

### Specialized Row-Based Layout
Inspired by premium SaaS design concepts, the tool directory avoids blocky grids. Instead, it relies on structured vertical lists wrapped inside micro-elevated containers. Each item handles horizontal distribution smoothly, highlighting custom link-out circular action buttons that scale fluidly via CSS transition matrices (`transition-all duration-300 transform hover:scale-105`).

---

## 📁 Repository Tree

```text
├── index.html          # Core Gateway & Dashboard Directory
├── academics.html      # Academic Evaluation & Attendance Warning Modules
├── clubs.html          # Technical & Cultural Club Matrix
├── hostel.html         # Timelines, Amenities, and Packing Checklists
├── survival.html       # Risk Mitigation Matrix (Do's & Don'ts)
└── tools.html          # Field-Specific Premium Tool Sandbox (CSE/AI/DS/CCE)

