# DevFlow Landing Page

## Project Overview

A static, responsive landing page for **DevFlow**, a fictional
developer-learning platform, built as Task 1 (Level 1) of the OASIS Infobyte
Web Development & Designing Internship.

## Objective

Design and build a professional, original, single-page website that
demonstrates a strong grasp of semantic HTML5 and modern CSS3 — without any
JavaScript, frameworks, or CSS libraries.

## Technologies Used

- HTML5 (semantic elements)
- CSS3 (Flexbox, CSS Grid, custom properties, media queries)
- Google Fonts (Inter, IBM Plex Mono) loaded via `<link>` in `index.html`
- No JavaScript, no frameworks, no CSS libraries

## Features

- Sticky navigation bar with a responsive mobile menu built on the native `<details>`/`<summary>` disclosure element (pure CSS, no JS), so the menu is keyboard-operable and its expanded/collapsed state is announced to screen readers automatically
- Hero section with a headline, subheadline, working CTA, and an inline SVG "flow graph" illustration
- Feature section with three cards (Learn / Build / Grow)
- "Why DevFlow" two-column section with a benefit list and an inline SVG progress chart
- "How It Works" three-step process section
- Bottom call-to-action band
- Multi-column footer with navigation, contact, and social placeholders
- Fully responsive from 375px up to 1920px, with no horizontal scrolling
- Visible keyboard focus states and a skip-to-content link for accessibility

## Project Structure

```
WebDev-L1-LandingPage/
├── index.html
├── style.css
├── assets/
│   └── favicon.svg
└── README.md
```

## How to Run

No build step or server is required.

1. Download or clone this folder.
2. Open `index.html` directly in any modern web browser.

## Internship Requirements Completed

- [x] Fixed/sticky navigation bar
- [x] 3+ navigation links, each linking to a real section
- [x] Hero section with headline, subheadline, and working CTA
- [x] 2+ distinct content sections (Features, Why DevFlow, How It Works, CTA)
- [x] Footer with contact and social placeholders
- [x] Consistent colour palette (ink / paper / signal green / amber highlight)
- [x] Responsive layout tested at 1920, 1440, 1024, 768, 480, 375px
- [x] No element overlap or horizontal scrolling at any breakpoint
- [x] Intentional, consistent padding and margins via CSS custom properties
- [x] `box-sizing: border-box` applied globally
- [x] Clean typography using two font families and a defined type scale
- [x] Built with HTML5 and CSS3 only, no JavaScript
- [x] CSS Grid and Flexbox used throughout
- [x] Verified on mobile and desktop viewport widths
- [x] README included

## Placeholders to Replace

Before publishing this project publicly, replace the following placeholder
content with real information:

- Footer email address (`hello@devflow.example`) and phone number
- Footer social links — currently set to fictional placeholder URLs
  (`github.com/devflow`, `x.com/devflow`, `linkedin.com/company/devflow`);
  replace with real accounts if this project is ever connected to a live brand

Hero section stats (12+ example learning paths, 60+ project ideas, 3 core
learning pillars) are intentionally illustrative and do not need to be
replaced — they describe the shape of the fictional platform's content
rather than claiming a real user base.

## Author

Built as part of the OASIS Infobyte Web Development & Designing Internship
(Level 1, Task 1).
