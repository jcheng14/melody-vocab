# Melody's Vocabulary Trainer

A self-contained, single-file vocabulary practice site built around the SSAT/ISEE 真题核心词汇 word list (~2,140 words) and Lesson 1 spotlight words.

## Live site

After setting up GitHub Pages (see below), the URL will be:

`https://YOUR_USERNAME.github.io/REPO_NAME/`

## Features

- **Multiple-choice cloze**: read a sentence with one word blanked out, pick from four similar words. Wrong picks are auto-flagged as "still learning" and surface more often.
- **Smart-random navigation**: words you mark as "still learning" come back 4× more often than ones you mark "known".
- **Cloze recall mode**: hide the choices when she's confident.
- **Definition cloze fallback**: words without a hand-written sentence still work — the English definition becomes the context.
- **List filtering**: jump to a specific list (Lesson 1 spotlight, or any of core lists 1-214).
- **Progress saved in the browser** via localStorage. No accounts, no servers.
- **Works offline** once loaded.

## Files

- `index.html` — the trainer (also available as `melody_vocab.html`).
- The `.pdf` files are the source vocabulary lists. Not needed at runtime.

## How to enable GitHub Pages

1. Push this repo to GitHub (public).
2. Repo → **Settings** → **Pages** in the left sidebar.
3. Under "Build and deployment," set Source to **Deploy from a branch**, branch to **main** (folder `/ (root)`), and save.
4. Wait ~1 minute, then visit `https://YOUR_USERNAME.github.io/REPO_NAME/`.
