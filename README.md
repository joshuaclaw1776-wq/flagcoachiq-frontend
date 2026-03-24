# Flag Coach IQ — Frontend

Single-page HTML/Tailwind prototype for the Flag Coach IQ coaching OS. This is the static asset we deploy to Render Static Sites and serve at https://flagcoachiq.app.

## Development

- Edit `index.html` directly (it contains inline CSS/JS, similar to our other prototypes).
- Use a simple static server for previews, e.g. `npx http-server` or `python -m http.server`.
- Target backend URL is `https://audible-backend-cbaz.onrender.com` (see `AUDIBLE_BACKEND` constant near the bottom of the file).

## Deployment

Render Static Site picks up the `main` branch on every push and redeploys automatically. The publish directory is the repo root.
