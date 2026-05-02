# nicholasvest.com

Personal academic website for Nicholas A. Vest, Postdoctoral Research Scientist at the University of Florida.

## Overview

A single-page static site built with plain HTML and CSS — no frameworks, no build tools, no dependencies beyond a Google Fonts import. Hosted on GitHub Pages at [n-vest.github.io](https://n-vest.github.io) and served at [nicholasvest.com](https://nicholasvest.com).

## Structure

```
/
├── index.html       # Main site — all HTML, CSS, and JS in one file
├── vest.png         # Headshot
├── CNAME            # Custom domain config for GitHub Pages
└── README.md
```

## Features

- Aura-style radial gradient background
- Frosted glass content panel
- Animated name on load with typewriter cursor
- Expandable project cards with smooth accordion animation
- Shimmer animation on key phrases in the bio
- Active nav highlighting via IntersectionObserver
- Staggered section entrance animations
- Responsive layout

## Updating Content

Everything lives in `index.html`. The main sections to edit:

- **Bio** — search for `hero-body` in the HTML
- **Projects** — each `project-card` div contains a title, summary, detail paragraphs, and selected works
- **Education / Interests** — inside the `hero-meta` div
- **Footer links** — bottom of the file in `footer-links`

## Deployment

Push to the `main` branch. GitHub Pages deploys automatically within a minute or two.

## Contact

[vestnicholas@gmail.com](mailto:vestnicholas@gmail.com)
