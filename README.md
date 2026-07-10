# hiola-pages

Marketing landing page for **Hiola — Chat in Every Language**, an iOS app.

This is a plain static site: hand-written HTML with no build step, framework, or
dependencies.

## Contents

| File | Purpose |
|------|---------|
| `index.html` | Landing page |
| `privacy.html` | Privacy policy |
| `terms.html` | Terms of service |

## Live site

https://elenazobak.github.io/hiola-pages/

That is the canonical URL declared in `index.html`. The repo has no `CNAME`
file, so the site is served on the default GitHub Pages domain (no custom
domain configured).

## Hosting / deploy

Served via **GitHub Pages** from this repo. There is no CI workflow in the
repo, so Pages is configured through the repository settings (Settings →
Pages), most likely building from the `main` branch root. Pushing to `main`
publishes the changes.

To confirm the exact source branch/folder, check **Settings → Pages** on GitHub.

## Preview locally

No build required — open the file directly, or serve the folder so relative
links behave like production:

```sh
python3 -m http.server 8000
# then open http://localhost:8000
```

## Related

- Hiola on the App Store: https://apps.apple.com/app/id6759498003
