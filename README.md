# What's the Best Clipse Album?

Static head‑to‑head voting toy: every unique pair of Clipse albums is shown once (round‑robin). Click the one you prefer each matchup; highest tally wins.

## Tech
Pure static HTML/CSS/JS (no build step). Leaderboard + canvas export for sharing.

## Local Preview
Open `index.html` directly or run a tiny server:

```bash
python -m http.server 8000
```

## Deploy to Netlify (UI)
1. Push repo to GitHub.
2. In Netlify: New Site > Import from Git.
3. Build command: leave blank. Publish directory: `.`
4. Deploy.

## Deploy via Netlify CLI
```bash
npm install -g netlify-cli
netlify init       # choose "No build command"
netlify deploy     # draft
netlify deploy --prod
```

## Future Ideas
- Persist votes (localStorage or serverless).
- Shareable winner link.
- Theme toggle.

## License
Personal / demo use. Album art from Wikipedia/Wikimedia under respective licenses.
