# CRM Onboarding Redesign

Interactive HTML prototypes for a redesigned CRM onboarding flow: choosing how to start, selecting an industry, and reviewing the modules configured for it.

## Screens

| Screen | File |
| --- | --- |
| Full onboarding flow | `Onboarding Flow.dc.html` |
| Start choice | `Start Choice.dc.html` |
| Industry select | `Industry Select.dc.html` |
| Module setup (original, v2–v5) | `Module Setup*.dc.html` |

`index.html` links to every screen. `uploads/` holds reference screenshots.

## Run locally

The pages load `support.js`, which pulls React 18 and Babel from unpkg, so serve the folder over HTTP rather than opening files directly:

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Hosting on GitHub Pages

In the repository, go to **Settings → Pages**, set **Source** to *Deploy from a branch*, and choose `main` / `(root)`. The site will be available at `https://<user>.github.io/<repo>/`.
