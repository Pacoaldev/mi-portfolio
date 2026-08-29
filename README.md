# Paco López Alarte — Personal Portfolio

**Backend Developer** with 14+ years across corporate IT, eCommerce and software engineering.  
Focused on **Python**, **Java**, **REST APIs**, distributed systems and infrastructure, with **AI-assisted development** (MCP, agents) as a complement.

**Live site:** [pacoal.dev](https://www.pacoal.dev)

Xirivella (Valencia), Spain · [pacoaldev@gmail.com](mailto:pacoaldev@gmail.com) · [+34 655 866 532](tel:+34655866532) · [LinkedIn](https://www.linkedin.com/in/fmlalinked) · [GitHub](https://github.com/Pacoaldev)

---

## About this repository

Static personal portfolio: single-page site with sections for About, Skills, Projects and Contact.  
Bilingual UI (ES/EN), theme color picker, GSAP animations, visit counter and EmailJS contact form.

| Layer | Stack |
|-------|--------|
| Markup & style | HTML5, CSS3, responsive layout |
| Scripts | JavaScript, jQuery, GSAP, Particles.js |
| i18n | `js/translations.js` (ES default) |
| Contact | [EmailJS](https://www.emailjs.com/) |
| Deploy | Nginx (Docker), Kubernetes manifests in `k8s/` |

---

## Professional experience

| Period | Role | Company |
|--------|------|---------|
| 2025 – 2026 | React / Design System Contributor | Stack & Flow |
| 2020 – 2024 | Ecommerce & IT Specialist | Lladró S.A. |
| 2010 – 2020 | IT Support Lead | Lladró S.A. |

---

## Featured projects

### [OpenCode Chat Panel](https://github.com/Pacoaldev/opencode-mcp)
VS Code extension with MCP server exposing OpenCode to Claude, Cursor and other assistants. Published on [Microsoft Marketplace](https://marketplace.visualstudio.com/items?itemName=Pacoaldev.opencode-mcp-vscode) and [Open VSX](https://open-vsx.org/extension/Pacoaldev/opencode-mcp-vscode).

### [Epsylon Control Center](https://github.com/Pacoaldev/Epsylon-show)
AI-powered professional training platform: interview copilot, mock interviews, knowledge base and job search automation.

### [Medusse IoT Platform](https://github.com/Pacoaldev/medusse-show)
End-to-end IoT platform for environmental monitoring — MQTT (EMQX), InfluxDB, Grafana, REST API, WebSockets and Docker microservices.

### [TrainerExpert](https://github.com/Pacoaldev/TrainerExpert)
Technical interview simulator with 8 scenarios. PWA with mobile microphone support, Node.js proxy for LLM APIs, MIT license.

### [ApplyDash](https://github.com/Pacoaldev/APPLYDASH)
Full-stack job application tracker with REST API, offer scraping and metrics dashboard.  
**Demo:** [applydash.vercel.app](https://applydash.vercel.app/)

### [Industrial Project Management System](https://github.com/Pacoaldev/Gestion-de-Proyectos-UP4)
Layered Java backend (Controller–Service–Repository) for industrial innovation projects over MySQL.

### [APIpnot](https://github.com/Pacoaldev/APIpnot)
Python data platform for scraping, processing and visualizing real estate prices across Spanish provinces (Pandas, Streamlit, Plotly).

### [Citabot](https://github.com/Pacoaldev/Citabot)
Flutter Android app with FastAPI backend, Firebase push notifications and scraping automation.  
**Store:** [Google Play](https://play.google.com/store/apps/details?id=com.paco.citabot)

### [TimeTracker](https://github.com/Pacoaldev/Timetracker)
Production web app (React + Vite, Supabase): live timers, Kanban board, roles, PDF/CSV export.

---

## Core tech stack

- **Languages:** Java, Python, TypeScript, Node.js
- **Backend:** REST APIs, WebSockets, microservices, MVC / layered architecture
- **AI:** LLMs, MCP, OpenCode, agentic workflows
- **Data:** MySQL, PostgreSQL, MongoDB, InfluxDB, Supabase
- **IoT:** MQTT, Grafana, Telegraf, Docker
- **DevOps:** Docker, Kubernetes, Jenkins, GitHub Actions, AWS, Linux
- **Frontend:** React, HTML, CSS, Tailwind, Flutter

---

## Local development

No build step required. Serve the project root as static files:

```bash
# Python
python -m http.server 8080

# Node (npx)
npx serve .
```

Open `http://localhost:8080`. Standalone preloader demo: `precarga.html`.

### Docker

```bash
docker build -t mi-portfolio .
docker run -p 8080:80 mi-portfolio
```

---

## Project structure

```
mi-portfolio/
├── index.html          # Main SPA
├── precarga.html       # Preloader standalone demo
├── css/                # Styles + color themes
├── js/                 # Logic, i18n, particles
├── images/             # Assets and project logos
└── k8s/                # Kubernetes deployment manifests
```

---

## Contact

Questions or opportunities? Reach out at [pacoaldev@gmail.com](mailto:pacoaldev@gmail.com) or via [LinkedIn](https://www.linkedin.com/in/fmlalinked).
