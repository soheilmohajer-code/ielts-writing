# IELTS Copy Test

Single-file IELTS writing practice app — open it and start typing. No build, no server.

**Live demo (after enabling GitHub Pages):** `https://<username>.github.io/<repo>/copy-test.html`

## Features

- Paste any passage, set paragraph count, exam timer with soft alert + sound
- Full-passage or paragraph-by-paragraph mode
- Copy mode or from-memory mode (passage hides while typing)
- High-precision scoring: missed / extra marks, per-paragraph report, weakest-paragraph retry
- Candidate profile (name + accuracy goal), local history & passage bank in the side panel
- Bilingual EN/FA with RTL, light/dark themes
- Everything stays in the browser (`localStorage`) — nothing is uploaded anywhere

## Run locally

Just double-click `copy-test.html`, or serve the folder:

```bash
python -m http.server 8000
# open http://localhost:8000/copy-test.html
```

## Enable GitHub Pages

Repo Settings → Pages → Deploy from a branch → `main` / `/ (root)` → Save.
