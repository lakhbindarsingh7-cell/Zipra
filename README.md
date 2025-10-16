# Zipra Solutions Website

This repository contains the redesigned marketing site for Zipra Solutions, featuring refreshed branding, AI Research Lab storytelling, and interconnected solution subpages.

## Previewing the site locally

Because the project is a static site, you can preview it in any browser with a lightweight web server. Running a server prevents loader overlays from blocking the page and keeps relative asset paths working.

### Option 1: Python (recommended)

```bash
python3 -m http.server 8000
```

Then open your browser to [http://localhost:8000/index.html](http://localhost:8000/index.html).

### Option 2: Node.js

If you have Node installed, you can install `serve` globally and run it from the repository root:

```bash
npm install --global serve
serve .
```

Open the printed URL (for example `http://localhost:3000`) and navigate to `/index.html`.

## Key pages

- `index.html` – Homepage overview of Zipra Solutions
- `solutions.html` – Detailed breakdown of delivery offerings
- `ai-research.html` – AI Research Lab programs and POC accelerators
- `approach.html` – Delivery methodology and engagement model
- `projects.html` – Case studies and proof points
- `pricing.html` – Engagement models and investment tiers
- `contact-us.html` – Direct contact form and office information

All pages share a consistent navigation so you can explore the entire experience from any starting point.
