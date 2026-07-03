# Spanish Journal Dashboard

A minimalist, high-performance, and multi-language operational tracking dashboard for **George Freedom**'s Spanish language journey. 

Built as a personal system combining tactical planning with gamified learning mechanics. Features zero-backend architecture, client-side Markdown execution, zero tracking, and complete data ownership. Designed to document weekly learning sprints and store "Survival Vocabulary Kit".

## Tech Stack

- **HTML5** (Semantic layout and SPA structure)
- **Pico CSS** (Minimalist, lightweight classless CSS framework)
- **Custom CSS** (Tactile journal theme, typography lock, and layout engine)
- **Marked.js** (Lightweight, client-side asynchronous Markdown compilation)
- **GitHub Pages** (Production hosting and deployment via global CDN)

## Key Features

* **Gamified Framework:** Built-in milestone roadmap (A1 to B2 Fluency) with tracked conditions and custom reward triggers.
* **Asynchronous Client-Side Architecture:** Zero database overhead. Live journal entries and vocabulary nodes are fetched asynchronously and compiled on the fly using vanilla JS and `marked.js`.
* **Zero Bloat:** No servers, no tracking scripts, no cookie-consent banners. Pure client-side execution that works completely offline.
* **Tactile Aesthetics:** Styled to mimic an analog field journal/typewriter logbook while preserving sharp, engineering-grade monospace layout for tables and data points.
* **Multi-Language Architecture:** Native, isolated support for English (default root) and Czech (`/cz`) locales.

## Architecture

This repository uses a clean, single-repo, subdirectory layout to handle language variations efficiently while keeping shared assets unified.

```text
├── index.html          # Main English dashboard (SPA Entry Point)
│
├── en/
│   └── en_content/
│      ├── vocabulary   # Asynchronous vocabulary markdown files
│      └── weeks        # Weekly sprint log markdown files
│
├── cz/
│   ├── index.html      # Czech localized dashboard (SPA Entry Point)
│   └── cz_content/
│      ├── vocabulary   # Asynchronous vocabulary markdown files
│      └── weeks        # Weekly sprint log markdown files
│
├── static/             # Shared production assets
│   ├── css/
│   │   ├── custom.css  # Custom CSS designs & typography
│   │   └── pico.min.css
│   ├── js/
│   │   └── marked.min.js
│   └── img/
│       
│
├── LICENSE.md          # License documentation
└── README.md           # System documentation
```

## 🔗 Let's Connect:

* Visit my website: **[https://GeorgeFreedom.com](https://GeorgeFreedom.com)**
* Connect on LinkedIn: **[https://www.linkedin.com/in/georgefreedom/](https://www.linkedin.com/in/georgefreedom/)**
* Let's talk: **[https://cal.com/georgefreedom](https://cal.com/georgefreedom)**


## 📜 License:

Copyright (c) 2026 Jiří Svoboda (George Freedom) / George Freedom Tech

This project is licensed under:
* Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License

---

We build for the Future!

