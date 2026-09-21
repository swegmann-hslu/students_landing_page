# Student-facing profile page

Small Markdown-based GitHub Pages project for a one-page student-facing profile.

## Edit the content

Most page text lives in:

- `content/_index.en.md` for English
- `content/_index.de.md` for German

Useful next edits:

- Replace placeholder links with module descriptions.
- Add the final GitHub Pages URL once the project exists on GitHub.
- Add a preferred contact route, office-hour note, or booking link.

## Build locally

```bash
hugo server
```

On this machine, Hugo is available at `C:\sw\hugo\hugo.exe`.

For a production build:

```bash
hugo --minify
```

The generated site is written to `public/`.

## Publish on GitHub Pages

Push this repository to GitHub and configure Pages to use GitHub Actions as its source. The included `.github/workflows/pages.yml` builds the Hugo site and deploys the generated `public/` artifact to GitHub Pages on pushes to `main`.
