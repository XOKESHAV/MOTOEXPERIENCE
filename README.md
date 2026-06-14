# Apex Velocity – Elite Hypercar Experience

A static multi-page site (Stitch design export) wired into a single navigable
website, ready for GitHub Pages.

## Pages

| File | Section |
|---|---|
| `index.html` | Home — "Start Your Engines" |
| `showroom.html` | The Showroom — hypercar collection |
| `bugatti.html` | Bugatti Chiron — The 300mph Legend |
| `rimac.html` | Rimac Nevera — The Electric Storm |
| `hall-of-fame.html` | Hall of Fame — World Records |
| `calculator.html` | "Can You Afford It?" calculator |
| `sound.html` | Sound Experience — Hear the Power |

The top/bottom navigation on every page (Showroom, Garage, Telemetry,
Pit Lane, Events) is wired between these pages, and the "APEX VELOCITY"
logo links back to `index.html`. Legal/footer links (Privacy, Terms,
Contact, Partnerships) remain placeholders (`#`) since those pages
weren't designed.

## Deploying to GitHub Pages

1. Add all files in this folder to the root of your repository (or to a
   `/docs` folder — just make sure `index.html` is the entry file).
2. Commit and push to GitHub.
3. In your repo, go to **Settings → Pages**.
4. Under "Build and deployment", set **Source** to "Deploy from a branch".
5. Choose the branch (e.g. `main`) and the folder (`/ (root)` or `/docs`),
   then click **Save**.
6. GitHub will give you a URL like
   `https://<username>.github.io/<repo-name>/` — it can take a minute or
   two to go live.

## Notes

- Images are hosted externally (Google `lh3.googleusercontent.com` and
  Unsplash links) — no local image assets needed.
- Built with Tailwind via CDN, so no build step is required.
