# Wedding Invitation

A single-page wedding invitation with flip card (front, details, RSVP) and Formspree integration.

## Contents

- **index.html** – Full invitation (HTML, CSS, JS inline). Uses D3.js and Google Fonts from CDNs.
- **couple.jpg** – Main photo on the card front. Add this file to the project root (same folder as `index.html`). If missing, the card shows a placeholder.

## Deploy to Vercel

1. Push this folder to a **new GitHub repo** (see below).
2. Go to [vercel.com](https://vercel.com) → **Add New** → **Project**.
3. Import your GitHub repo. Vercel will detect it as a static site.
4. **Root Directory**: set to the repo root (or leave default if the repo contains only this project).
5. **Build**: leave empty (no build step). **Output**: static.
6. Deploy. Your site will be served at `https://your-project.vercel.app`.

## Add your photo

Place your couple photo in this folder as **couple.jpg**. It will appear on the front of the card.
