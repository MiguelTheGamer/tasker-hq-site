# Tasker HQ — landing page & legal pages

Static site for the **Tasker HQ** Chrome extension, which tracks real hourly earnings
across AI gig platforms. Served via GitHub Pages at
<https://miguelthegamer.github.io/tasker-hq-site/>.

The extension is published on the Chrome Web Store and the Microsoft Edge Add-ons store.

## Contents

| Path | Purpose |
|---|---|
| `index.html`  | Landing page |
| `privacy.html`| Privacy policy (required for Chrome Web Store listing) |
| `terms.html`  | Terms of service |
| `site.css`    | Styles |
| `download/`   | Distribution files |
| `images/`, `icon.png` | Assets |

## Local preview

No build step — it's plain HTML/CSS. Serve the directory and open it:

```bash
python -m http.server 8000
```

Then visit <http://localhost:8000>.
