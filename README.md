# portfolio.in

Interactive terminal-style developer portfolio for [RathnamS089](https://github.com/RathnamS089), built as a single-page static `index.html` app and deployed on Vercel.

## Live Portfolio

- https://portfolio-in-one.vercel.app/

## What this project is

This repository contains one self-contained HTML file with embedded CSS and JavaScript. It renders a terminal UI where visitors can run portfolio commands such as:

- `help`
- `about`
- `skills`
- `projects`
- `contact`
- `clear`

## Key features

- Terminal-inspired command interface
- Keyboard-friendly input with history and autocomplete
- Responsive layout for desktop and mobile
- Accessible roles/labels for interactive elements
- Project, skills, and contact content sourced from the GitHub profile work

## Run locally

Because this is a static app, no build step is required.

### Option 1: Open directly

Open `index.html` in a browser.

### Option 2: Serve locally

From the repository root:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deployment notes

- Current deployment target: **Vercel**
- Live URL: **https://portfolio-in-one.vercel.app/**
- Since the site is static, deployment can publish `index.html` as-is without a build pipeline.

## Repository layout

- `index.html` — complete UI, styling, and command logic
- `README.md` — project overview and usage notes
