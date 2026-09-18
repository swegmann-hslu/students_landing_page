# Student-facing profile page

Small Markdown-based GitLab Pages project for a one-page student-facing profile.

## Edit the content

Most page text lives in:

- `content/_index.en.md` for English
- `content/_index.de.md` for German

Useful next edits:

- Replace placeholder links with module descriptions.
- Add the final GitLab Pages URL once the project exists in GitLab.
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

## Publish on GitLab Pages

Push this repository to GitLab. The included `.gitlab-ci.yml` builds the Hugo site with GitLab's Pages URL and publishes the `public/` artifact from the default branch.
