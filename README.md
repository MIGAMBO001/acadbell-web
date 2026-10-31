# ACADBELL — website

Landing / download page for the ACADBELL Android app.

Static HTML + CSS, zero build step, zero dependencies. Deploys to Vercel as a plain static site.

## Deploy

```bash
npm i -g vercel
vercel --prod
```

Project name must be **`acadbell`** to get the `acadbell.vercel.app` domain
(Vercel derives the domain from the project name, not the repo name).

Or import this repo at <https://vercel.com/new> — no build command, no output directory needed.

## Local preview

```bash
npx serve .
```

## Links used

- App source: <https://github.com/MIGAMBO001/ACADBELL>
- Releases: <https://github.com/MIGAMBO001/ACADBELL/releases>
- APK: `releases/download/v1.0.0/ACADBELL-v1.0.0-release.apk`

Bump the version in `index.html` and `vercel.json` when a new release ships.
