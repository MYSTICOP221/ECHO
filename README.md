# ECHO — Twitter-style Frontend Clone

ECHO is a Twitter-inspired frontend practice project built with **HTML, CSS, vanilla JavaScript, and Vite**. I built it to practice JavaScript modules, DOM updates, event delegation, and interactive UI behavior.

## Features

- Create new tweets (whitespace-only posts are rejected)
- Like and unlike tweets
- Retweet and undo retweets
- Show and hide replies
- Display profile pictures and seeded example tweets
- Generate unique IDs for new tweets using `crypto.randomUUID()`
- Escape dynamic text before rendering it as HTML

## Run locally

Requires Node.js 20.19+ or 22.12+.

```bash
npm ci
npm run dev
```

Open the local URL printed by Vite. To check the production build:

```bash
npm run build
npm run preview
```

## Project structure

- `index.html` — page layout
- `index.css` — styles
- `index.js` — feed rendering and interaction handlers
- `data.js` — starter tweets and replies
- `images/` — profile pictures (add your image assets here)

## Limitations

This is a frontend-only learning project, not a production social network. Tweets and interaction state reset when the page refreshes; there is no authentication, backend, or database.

## Built for practice

I built ECHO as a hands-on exercise to strengthen my frontend JavaScript skills.
