# Happy Birthday, Dona

A single-file, midnight-blue birthday website for Sonali Priyadarshini (Dona),
from Soumyaranjan Jena (Manas). Loving each other since 2019.

Live site: https://jenam977-dot.github.io/dona-birthday/

## Deployment

- GitHub Pages, project site at `/dona-birthday/`
- Source: `main` branch, `/` (root) folder
- No build step, no backend, no API keys, no paid services
- All assets use relative paths (`index.html`, `photo1.jpg` … `photo5.jpg`),
  so the site works at the project path and locally when opened from the repo root

## Files

- `index.html` — the whole site: opening surprise, hero, letter, story,
  song section, wishes, gallery, countdown, interactive heart, dreams, finale
- `photo1.jpg` … `photo5.jpg` — gallery photos published for everyone

## Customise

- Text and captions: edit the text in `index.html` (letter, captions are
  `contenteditable` in the browser only — see below)
- Song: the "Listen to the Song" link in `index.html` points to the
  configured streaming source for "Agar Tum Mil Jao". No copyrighted audio
  is embedded in the repo, and no lyrics are reproduced.
- Photos: replace `photo1.jpg` … `photo5.jpg` in the repo and commit, then
  GitHub Pages redeploys automatically.

## Important: browser-local vs published changes

- Photos and captions changed with "Add a photo", "Replace photo", "Remove",
  or by typing in a caption **in the browser stay in that browser only**.
  They do **not** update GitHub Pages for Dona or anyone else.
- To publish a change for everyone, edit/commit the file in this repository.
- Do not commit private photographs or personal information by accident:
  anything committed here is public at the Pages URL above.
