# TreadX website (static)

Plain HTML + CSS, no build step. Pages: index, about, programs, iso-45003, clients, media, contact.

## Deploy on Vercel
1. Push this folder to a Git repo (or run `vercel` inside it).
2. Framework preset: **Other**. Build command: none. Output directory: `.` (root).
3. `vercel.json` enables clean URLs (/about, /programs ...).

Local preview: `npx serve .` or `python3 -m http.server`.

## To finish before launch
- Add a contact email (contact.html) and real social URLs (footer).
- Newsletter and contact forms are visual only; connect a form service.
- Fonts load from Google Fonts (Barlow Condensed, Plus Jakarta Sans).
