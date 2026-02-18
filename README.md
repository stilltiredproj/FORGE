# FORGE — Workout Tracker

AI-powered workout tracker. Log workouts, build plans, and get coaching from GPT-4.

## Deploy to GitHub Pages

1. Create a new GitHub repository (public)
2. Upload these files to the repo root:
   - `workout-tracker.html` → rename to `index.html`
   - `manifest.json`
   - `_config.yml`
3. Go to **Settings → Pages → Source → Deploy from branch → main → / (root)**
4. Your app will be live at `https://yourusername.github.io/your-repo/`

## Features

- 📋 **Plans** — Create workout programs with exercises, sets, reps, rest
- 📝 **Log** — Track sessions, load from plans, record weights
- 📊 **History** — Full workout journal with stats
- 🤖 **AI Coach** — GPT-4o-mini powered personal trainer (bring your own OpenAI key)
- 🌙 **Dark / Light / Auto** theme
- 📱 **PWA** — Add to Home Screen on iOS/Android

## Notes

- All data is stored locally in `localStorage` — no server needed
- OpenAI API key is stored in the browser and never sent anywhere except OpenAI's servers
- Works fully offline (except AI features)
