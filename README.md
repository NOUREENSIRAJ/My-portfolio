# Noureen Siraj — Portfolio

Personal portfolio site built with React, Vite and TypeScript.

**Live projects:** every project card links to its source on
[github.com/NOUREENSIRAJ](https://github.com/NOUREENSIRAJ).

## Running locally

Requires [Node.js](https://nodejs.org) 20 or newer.

```bash
npm install
npm run dev
```

The site opens at 

## Building for production

```bash
npm run build
```

The finished site lands in the `dist` folder — that folder is what you
deploy to Netlify, Vercel or GitHub Pages.

## Project structure

```
index.html                     page shell
public/Noureen-Siraj-CV.pdf    CV served by the Download CV button
src/main.tsx                   React entry point
src/App.tsx                    the whole site
src/index.css                  fonts, colours and animations
```

## Editing content

Everything is data-driven from the top of `src/App.tsx`:

- `projects` — project cards (title, description, tags, GitHub link, live link)
- `skillGroups` — the tech stack section
- `timeline` — experience and education
- `certifications` — certification cards
- `highlights`, `sqaStats`, `sqaCards` — about and QA sections

To swap the CV, replace `public/Noureen-Siraj-CV.pdf` keeping the same filename.
