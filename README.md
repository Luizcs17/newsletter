# Global Shapers DC Hub — Monthly Newsletter

Each month's newsletter lives in its own folder and is published by GitHub Pages.

Archive: https://luizcs17.github.io/newsletter/

## Folder structure

```
newsletter/
├── README.md          ← this guide
├── index.html         ← archive page listing every edition
├── assets/            ← shared files used every month (logo, Instagram and LinkedIn icons)
├── images/            ← October 2026 images (keep as-is: the October email links here)
├── 2026-11/           ← November 2026
│   ├── index.html     ← the newsletter
│   └── images/        ← that month's photos
└── 2026-12/           ← next month: same pattern (YYYY-MM)
```

Do not rename or delete old folders: emails that were already sent load their images from them.

## Making next month's newsletter

1. **Copy the last edition.** Create the new folder, e.g. `2026-12/`, with a copy of the previous `index.html` and an empty `images/` folder.
2. **Prepare the photos.** Name them in lowercase with hyphens, no spaces (e.g. `holiday-party.jpg`). Keep each one under ~300 KB and about 1000 px wide (photos beside text: ~400 px wide).
3. **Edit the text.** Open `index.html` in any text editor and replace the content. Each section is marked with an HTML comment (`<!-- BLOCK: ... -->`). To add a story, copy an existing block and change the text and the `src="images/..."` of the photo.
4. **Upload to GitHub.** In the repository: *Add file → Upload files*, drag the new folder in, then *Commit changes*.
5. **Add it to the archive.** Add a line for the new edition in the root `index.html`.
6. **Wait 1–3 minutes** for GitHub Pages to publish, then open `https://luizcs17.github.io/newsletter/2026-12/`.
7. **Send it.** On that page press Ctrl+A (Cmd+A on Mac), Ctrl+C, open a new message in Gmail and press Ctrl+V. Send a test to yourself first and check it on your phone.

## Reusable blocks in `index.html`

| Block | Use it for |
|---|---|
| Full-width photo story | Main highlights with a landscape photo |
| Photo beside text | Portrait photos; the text wraps under the photo |
| Two photos side by side | Two short items with portrait photos |
| Info box (light blue) | Deadlines, forms, calls to action |
| Event card (blue left border) | Upcoming events with date and RSVP button |
| Bookshelf cards | Book recommendations |

Search for `TBD` before sending to make sure nothing is left unfilled.
