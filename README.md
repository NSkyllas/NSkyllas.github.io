# NSkyllas.github.io

Static portfolio/CV website for GitHub Pages.

## Site structure

Root pages:
- `index.html`
- `projects.html`
- `cv.html`
- `contact.html`

Project pages:
- `projects/flyway-model.html`
- `projects/arctic-climate.html`
- `projects/ecological-modelling.html`
- `projects/arctic-terns.html`

## Local editing

Open [index.html](/Users/nomikosskyllas/Documents/GIT/NSkyllas.github.io/index.html) in a browser, or run a small local server from this folder:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish on GitHub Pages

1. Push this repository to GitHub as `NSkyllas.github.io`.
2. In GitHub, open `Settings` -> `Pages`.
3. Under `Build and deployment`, set `Source` to `Deploy from a branch`.
4. Select branch `main` and folder `/ (root)`.
5. Save and wait for GitHub Pages to publish.

For a repository named `NSkyllas.github.io`, the site URL should be:

`https://nskyllas.github.io/`
