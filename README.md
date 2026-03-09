# Interactive Resume Website

A beautiful, single-file interactive resume built with vanilla HTML, CSS, and JavaScript. No build tools or server required — just open `resume.html` in any browser.

## Features

- **Bubbly Modern Design** — Purple-to-blue gradients, glassmorphism cards, animated aurora background
- **Scroll Animations** — Powered by AOS (Animate On Scroll), fade-up/zoom-in/flip effects
- **Inline Editing** — Click the pencil FAB to enter edit mode; click any text to edit it live
- **Image Upload** — Click the profile photo or project images to replace them (canvas-resized, embedded as data URIs)
- **Persistent Storage** — All edits auto-save to `localStorage` and restore on page reload
- **One-Click Export** — Downloads a fully self-contained `resume.html` with all edits and images baked in
- **Responsive** — Works on desktop, tablet, and mobile

## Sections

1. Sticky glassmorphism navigation bar
2. Hero — animated gradient, profile photo, typing effect tagline
3. About Me
4. Work Experience — vertical timeline
5. Education
6. Certifications — gradient-border badge cards
7. Skills — animated progress bars + pill tag cloud
8. Projects — card grid with image placeholders
9. Contact / Footer

## Usage

1. Download or clone this repo
2. Open `resume.html` in your browser
3. Click the **pencil icon** (bottom-right) to enter edit mode
4. Click any text to edit it; click images to replace them
5. Click **Save** to persist to localStorage
6. Click **Export** to download your finished resume as a standalone file

## Tech Stack

- Vanilla HTML5 / CSS3 / JavaScript (ES6+)
- [AOS](https://michalsnik.github.io/aos/) 2.3.1 via CDN — scroll animations
- [Google Fonts — Poppins](https://fonts.google.com/specimen/Poppins) via CDN
- No frameworks, no build tools, no dependencies to install

## Live Preview

Open `resume.html` directly in your browser — it works offline after first load (fonts/AOS load from CDN on first visit).

---

*Built with Claude Code*
