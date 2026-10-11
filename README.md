# IELTS Practice

IELTS practice app for all 4 skills — no build, no server. Just open `index.html` and start.

**Live demo (after enabling GitHub Pages):** `https://soheilmohajer-code.github.io/ielts-writing/`

## Pages

| Page | Skill | What it does |
|------|-------|--------------|
| `index.html` | Home | Choose a practice section (Listening / Reading / Writing / Speaking) |
| `listening.html` | Listening | Exam mode (audio plays once, text hidden) + Dictation mode (type sentence-by-sentence, see missed/extra) |
| `reading.html` | Reading | Read your own passage, tap any word/sentence for Persian translation, or translate all |
| `copy-test.html` | Writing | Copy test: type a passage exactly against the clock, per-paragraph report + weakest-paragraph retry |
| `speaking.html` | Speaking | Speaking chunks, American-voice read-aloud, Persian translation + flashcards |

Shared across pages: bilingual EN/FA with RTL, light/dark theme (`ielts-lang` / `ielts-theme` in `localStorage`), same IELTS test-centre header with Home link.

## Writing details (`copy-test.html`)

- Paste any passage, set paragraph count, exam timer with soft alert + sound
- Full-passage or paragraph-by-paragraph mode
- Copy mode or from-memory mode (passage hides while typing)
- High-precision scoring: missed / extra marks, per-paragraph report, weakest-paragraph retry
- Candidate profile (name + accuracy goal), local history & passage bank in the side panel
- Everything stays in the browser (`localStorage`) — nothing is uploaded anywhere

## Run locally

Just double-click `index.html`, or serve the folder:

```bash
python -m http.server 8000
# open http://localhost:8000/index.html
```

## Enable GitHub Pages

Repo Settings → Pages → Deploy from a branch → `main` / `/ (root)` → Save.
Then open the root URL above — `index.html` loads automatically.
