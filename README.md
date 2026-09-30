# Lab Automation Pilot — Landing Page

Single-file static landing page for the Georgia Tech EMBA lab-automation robotics
research pilot. Captures interest via a short quiz and submits responses to a
Formspree endpoint (emails the team + logs every response in the Formspree
dashboard).

## Structure

- `index.html` — the entire page (HTML/CSS/JS, no build step, no dependencies).
- `assets/` — the hero video (`hero-loop.webm`, `hero-loop.mp4`) and its poster
  frame (`hero-poster.jpg`), served as normal static files and referenced by
  `index.html`.

## Deploying

This is a static site — any static host works. Deployed here via
[Vercel](https://vercel.com), connected directly to this GitHub repo for
automatic redeploys on every push to `main`.

## Editing

Open `index.html` in any editor. There's no build step — save your changes,
commit, and push; Vercel picks it up automatically.
