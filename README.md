# DevConf 2026 — Landing Page

A responsive-ready landing page for a fictional developer conference, **DevConf 2026**, built with plain HTML5 and CSS3 (no JavaScript, no CSS frameworks).

🔗 **Live Site:** [Add your GitHub Pages link here]
📦 **Repository:** [Add your repo link here]

---

## 📋 Overview

This project was built as part of a front-end assignment, following a Figma design reference. It includes a fully static, single-page conference site with the sections below.

## 🧩 Sections

- **Navbar** — Logo left, nav links centered, "Register Now" button right
- **Hero** — Full-width dark background image with overlay, bold heading with italic emphasis, centered CTA
- **Meet the Speakers** — 2×2 grid of speaker cards with photo, category tag, name, and designation
- **Secure Your Spot (Pricing)** — Three pricing tiers (Standard / Pro / Team), with the Pro plan visually highlighted
- **Frequently Asked Questions** — AI-assisted placeholder section (see [PROMPTS.md](./PROMPTS.md)) using native `<details>`/`<summary>` accordions, no JS
- **Footer** — Logo, social links, divider, copyright

## 🛠️ Tech Stack

- HTML5
- CSS3 (Flexbox & Grid)
- [Font Awesome](https://fontawesome.com/) — social icons
- [Google Fonts – Inter](https://fonts.google.com/specimen/Inter) — typography
- No JavaScript, no CSS frameworks

## 📁 Project Structure

```
├── index.html
├── style.css
├── assets/          # images, logos, icons
├── PROMPTS.md        # AI prompts used for the FAQ section
└── README.md
```

## 🎨 Design Reference

Layout and structure follow the assignment's Figma design, with a navy (#0D1B2A) and blue-accent (#1D4ED8) color palette suited to a tech-conference theme.

## 🤖 AI Usage

Google Gemini was used only for the placeholder "Something Missing?" section, which became the FAQ section. Full prompt and chat link documented in [PROMPTS.md](./PROMPTS.md).

## 🚀 Running Locally

No build step required — just clone and open `index.html` in a browser:

```bash
git clone https://github.com/Ashik756/Dev-Conference.git
cd dev-conference
open index.html or double-click the file
```

## 📄 License

Built for educational purposes as part of a front-end development assignment.