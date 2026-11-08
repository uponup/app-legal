# app-legal

Public legal pages for Uponup indie iOS apps (privacy policies, terms later).

## Layout

```
apps/<app-slug>/privacy.html
```

Current:

- [Gramku Privacy Policy](https://uponup.github.io/app-legal/apps/gramku/privacy.html)
- [Pipe Offset Privacy Policy](https://uponup.github.io/app-legal/apps/pipe-offset/privacy.html)

## Deploy

GitHub Pages: Settings → Pages → Deploy from branch `main` / root (or `/docs` if you move files).

## Add another app

1. Copy `apps/gramku/` to `apps/<slug>/`
2. Edit the HTML for that product
3. Link it from `index.html`
