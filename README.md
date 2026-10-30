# wiesticized-solitaire-site

Public web pages for [Wiesticized Solitaire](https://cameroniup.github.io/wiesticized-solitaire-site/):
the landing page, privacy policy, and support page.

These URLs are referenced by the app's App Store Connect listing
(privacy policy URL and support URL fields).

The game's source code itself lives in a separate private repository.

## Layout

- `index.html` — landing page
- `privacy.html` — privacy policy (required by Apple)
- `support.html` — support contact + FAQ (required by Apple)
- `_shared.css` — shared styling, matching the in-app palette

## Deploying

Pushed to `main` → GitHub Pages serves it from the repo root at the
URL above. No build step.
