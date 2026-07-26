# nikolaimak.github.io

The landing page served at **https://nikolaimak.github.io/** — a catalog of my
projects, each of which is its own repository published as a GitHub Pages project
site at `https://nikolaimak.github.io/<repo>/`.

It is a single hand-written `index.html` with no build step, no dependencies and no
JavaScript. Committing to `main` publishes it.

## Adding a project

1. Make sure the project's own repo has Pages turned on
   (Settings → Pages → Deploy from a branch → `main` / `/`).
2. In `index.html`, copy one `<li class="card">…</li>` block and change five things:
   the emoji, the title, the `https://nikolaimak.github.io/<repo>/` link, the
   description, and the `Source` link.
3. Commit and push. The page is live within a minute or so.

## Checking it locally

```bash
python3 -m http.server 8080
# then open http://127.0.0.1:8080/
```

Opening `index.html` straight from disk works too — there are no modules or fetches.
