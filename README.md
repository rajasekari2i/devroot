# Software Engineering Foundation

An interactive, self-paced web course that explains how real web and mobile software is built, from the basics of the SDLC to AI-driven development.

## What's inside

- **5 phases, 24 sessions**, shown as a metro-style course map
  1. Software Engineering Fundamentals
  2. SDLC, Requirements & Design
  3. Web & Mobile Application Development
  4. Quality, Security, DevOps & Production
  5. AI-Driven & Agentic Development
- Every session includes:
  - "In simple words" explanations with everyday analogies
  - Diagrams and flow diagrams with icons (click any diagram to enlarge)
  - Sub-topics with deep dives, code examples and comparison tables
  - An animated "How it works" flow
  - Common mistakes, a hands-on exercise and a quick quiz
- One running case study: a food-ordering platform

## Features

- Light and dark mode
- Presenter view for classroom use (larger text, no sidebar)
- Keyboard navigation: `←` / `→` to move between sessions, `P` for presenter view, `Esc` to exit
- Progress tracking ("Mark as covered"), saved in the learner's browser
- Works on desktop, tablet and mobile

## How to run

No installation or build step is needed. The whole course is a single HTML file.

- **Locally:** open `index.html` in any modern browser.
- **On a server:** upload `index.html` to any static host.

## Deployment options

| Option | How |
|---|---|
| Netlify / Vercel / Cloudflare Pages | Drag and drop the file, or connect a Git repository |
| GitHub Pages | Push `index.html` to a repository and enable Pages |
| AWS S3 + CloudFront | Upload to an S3 bucket configured for static hosting |
| Azure Static Web Apps | Deploy the folder containing `index.html` |
| Internal web server (Nginx / IIS) | Copy `index.html` into the web root |

## Notes

- Fonts are loaded from Google Fonts. If that is blocked on your network, the page falls back to system fonts automatically.
- Progress and theme settings are stored per browser (local storage); no data is sent to a server.

## Project structure

```
.
├── index.html   # the complete course (content, styles, diagrams and scripts)
└── README.md    # this file
```

## Updating the content

The course content is stored as structured data inside `index.html`. For larger changes, edit the source content and rebuild the single file, then redeploy it to your host.
