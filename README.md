# jackatstage.github.io

Portfolio site for Jack (Erfeng) Jiang, hosted on GitHub Pages: <https://jackatstage.github.io>

## Local development

Requires [Node.js](https://nodejs.org/) 18 or later.

```bash
npm install      # first time only: install the dev tools
npm run dev      # start a local server at http://localhost:3000 that reloads on save
```

## Commands

| Command            | What it does                                          |
| ------------------ | ----------------------------------------------------- |
| `npm run dev`      | Local preview with live reload                        |
| `npm run validate` | Check the HTML for errors                             |
| `npm run format`   | Format the code with Prettier                         |
| `npm run check`    | Pre-publish check (also runs on every push to GitHub) |

## Project layout

```
index.html            The whole site (HTML, CSS and JS in one file)
images/               Photos and other images
TODO.md               Sections still to write (not published)
_config.yml           GitHub Pages settings: keeps TODO.md, README.md, etc. off the site
.github/workflows/    Automatic checks
```

## Publishing

Merge changes into `main` and push. GitHub Pages updates the site within a minute or two.
