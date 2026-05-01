# Lemma Math Pitch

Standalone pitch website for the Alive Prize application.

## Run locally

```bash
pnpm run dev
```

Then open <http://localhost:3030>.

## Build

```bash
pnpm run build
```

The static output is written to `dist/`.

## Deploy To GitHub Pages

1. Push this repository to GitHub.
2. In the repository settings, set Pages source to `GitHub Actions`.
3. Push to `main` or run the `Deploy to GitHub Pages` workflow manually.

The workflow builds `dist/` and publishes it as the Pages site.
