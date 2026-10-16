# pckp.net

Company site for PCKP Ltd, served by GitHub Pages from the root of `main` at [pckp.net](https://pckp.net/).

It's plain HTML and CSS, with no build step. It shares its fonts and colour tokens with [dashynms.pckp.net](https://dashynms.pckp.net/).

## Layout

| Path | What it is |
| --- | --- |
| `index.html` | The page |
| `404.html` | Shown by GitHub Pages for unknown URLs |
| `assets/css/style.css` | All styles; colours and fonts are tokens at the top |
| `assets/fonts/` | Self-hosted Sora, IBM Plex Sans and IBM Plex Mono (SIL OFL, Latin subset) |
| `assets/img/` | Logo, DashyNMS mark and screenshot |
| `CNAME` | Custom domain for GitHub Pages |
| `.nojekyll` | Serves files as-is instead of running Jekyll |

## Preview locally

Paths are root-relative, so use a local server rather than opening the file directly:

```sh
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Editing

- **DashyNMS screenshot:** replace `assets/img/dashynms-dashboard.webp`.

## Deploying

Push to `main`. GitHub Pages publishes the repository root.
