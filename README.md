# Chaithra Gangadhar — E-Portfolio

A premium, single-page e-portfolio website for **Chaithra Gangadhar**, an AI & Machine Learning undergraduate at REVA University.

## 🚀 Features

- **Dark / Light Theme** — Toggle switch with preference saved in `localStorage`
- **Typing Animation** — Dynamic subtitle cycling through different role descriptions
- **Particle Canvas** — Interactive animated particle network background
- **Scroll Reveal Animations** — Sections fade-slide into view on scroll using IntersectionObserver
- **Skill Progress Bars** — Animated on-scroll bars showing proficiency levels
- **Education Timeline** — Structured academic history with cards
- **Project Cards** — Glassmorphic cards for featured AI/ML projects
- **Contact Form** — With mock submission flow and success feedback
- **Fully Responsive** — Mobile-first design with hamburger navigation

## 📁 File Structure

```
Portfolio/
├── index.html     ← Main HTML structure
├── style.css      ← All styling, theme variables, animations
├── script.js      ← Theme toggle, typing, particles, scroll observers
├── Profile.pdf    ← Source profile document
└── README.md      ← This file
```

## 🖥️ How to Preview

Simply open `index.html` in any modern web browser:

```
Right-click index.html → Open with → Your Browser
```

Or use any local server:

```bash
# Using Python 3
py -m http.server 8000
# Then visit http://localhost:8000
```

## 🎨 Design

- **Color Scheme**: Deep Indigo (`#6366f1`) + Teal (`#06b6d4`) on a dark `#0a0c10` background
- **Fonts**: Outfit (headings) + Inter (body) from Google Fonts
- **Style**: Glassmorphism cards with `backdrop-filter: blur`, gradient accents, subtle glow effects