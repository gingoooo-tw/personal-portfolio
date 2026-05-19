# ChihChi Kuo — Personal Portfolio

Personal portfolio website for **ChihChi Kuo**, AI Engineer & Data Scientist based in Taipei, Taiwan.

## Overview

A single-page portfolio built with vanilla HTML/CSS/JS, inspired by the minimal design of [emilkowal.ski](https://emilkowal.ski/). Features a clean single-column layout with light/dark mode support and full Chinese/English language toggle.

## Sections

- **Today** — bio and experience timeline
- **Work** — six projects with clickable detail modals
- **Demo** — AI Voice Agent video demo with architecture screenshots
- **Publications** — academic publications
- **More** — contact and links

## Features

- Chinese/English language toggle (預設中文)
- Light mode with system dark mode support (`prefers-color-scheme`)
- Project detail modals with bilingual content (overview, technical approach, metrics)
- Image lightbox for architecture diagrams and screenshots
- Video modal for YouTube embed
- SEO: JSON-LD structured data, sitemap, robots.txt

## Project Structure

```
personal-portfolio/
├── index.html        # Single-page site (HTML + inline CSS/JS)
├── images/
│   ├── voice-agent-1.png                 # Voice Agent architecture screenshot
│   ├── voice-agent-2.png                 # Voice Agent refactor result screenshot
│   └── project-Insurance-product-1.png  # Insurance Product AI Agent diagram
├── sitemap.xml
├── robots.txt
└── README.md
```

## Tech Stack

- Vanilla HTML / CSS / JavaScript — no frameworks or build tools
- Inter font via Google Fonts
- Hosted as a static site

## Local Development

Just open `index.html` in a browser — no build step required.

```bash
open index.html
```
