# Claude Fable 5 — project context for Claude Code

This repo is a **single-page static explainer** ("field note") about **Claude Fable 5**, Anthropic's first publicly available Mythos-class model (released 2026-06-09). Public, repo `GerardoRdz96/claude-fable-5`, published via **GitHub Pages** at https://gerardordz96.github.io/claude-fable-5/.

This file is authoritative project context. Verify claims against the files before acting; do not improvise.

---

## What this is (and what it is NOT)

- It **is** one hand-written HTML page plus images and a README. There is **no framework, no build step, no package manager, no tests.** Editing = editing `index.html` directly. Deploy = push to the Pages branch; GitHub Pages serves it.
- It is **not** an app. Do not add Next.js / a bundler / a static-site generator — that would defeat the point (a single, fast, dependency-free page). If it ever needs to grow, raise that with the owner first; don't scaffold a framework unasked.

## Files (6 tracked)

- **`index.html`** — the entire page (~425 lines; self-contained markup + inline styles). This is the only thing you edit for content or layout.
- `hero.png`, `glasswing.png`, `social.png` — page + social-preview images.
- `README.md` — what the page covers + the live link.
- `LICENSE` / git metadata.

---

## Standing rules

- **It's a fact-checked public explainer — keep it factual.** The page makes specific claims (release date, Mythos 5 / Project Glasswing lineage, the fallback-to-Opus-4.8 safety architecture, vendor-reported benchmarks, pricing vs Opus 4.8, availability and the free-window cliff). Benchmarks are **vendor-reported** — keep them labeled as such; never upgrade a vendor claim into an asserted fact. If a date or number changes, fix it here.
- **No employer / no private affiliation in the byline.** A prior commit deliberately removed an employer reference; keep the byline clean and personal.
- **Keep it dependency-free and fast.** Inline what you can; don't pull in external scripts/fonts/trackers beyond what's already there.
- **Edit `index.html`, deploy via Pages.** No build to run.

## Keeping this file honest

Re-read every turn — keep it accurate. If the page gains files or the deploy path changes, update this file in the same change.
