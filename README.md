# Project-N

This repository contains two web apps (React + Vite) for the course deliverable:

- **Brain Booster: Zoo Adventure** — https://pootanapat.github.io/Project-N/brain-web/
- **Little Brainiac: Hidden Object Zoo** — https://pootanapat.github.io/Project-N/little-web/

## Quick links
- Brain web: `docs/brain-web` (deployed to GitHub Pages)
- Little web: `docs/little-web` (deployed to GitHub Pages)

## Local setup (development)
Each app is independent (TypeScript + Vite). To run locally:

```bash
# Brain web
cd Project-N/brain-web
npm install
npm run dev

# Little web
cd Project-N/little-web
npm install
npm run dev
```

## Build (production)
```bash
# Build both
cd Project-N/brain-web && npm run build
cd Project-N/little-web && npm run build
```

## CI / Auto-deploy
This repository includes a GitHub Actions workflow (`.github/workflows/pages-deploy.yml`) which builds both apps on `push` to `main` and deploys the output to GitHub Pages at the subpaths:

- `/brain-web/`
- `/little-web/`

## Release / Submission
Releases are published with a tag and a zip artifact. See `releases/` for packaged deliverables.

## Team members
See `Member.md` for members and student IDs.

---

If you want me to attach a screenshot or add more details to `README.md`, tell me and I will update it.