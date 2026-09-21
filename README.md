# Student-facing profile page

Small Markdown-based GitHub Pages project for a one-page student-facing profile.

## Edit the content

Most page text lives in:

- `content/_index.en.md` for English
- `content/_index.de.md` for German

## Build locally

```bash
hugo server
```

For a production build:

```bash
hugo --minify
```

The generated site is written to `public/`.
