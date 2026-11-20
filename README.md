# philippzimmer — personal website

A single static page: no build step, no framework.

```
index.html     the whole site (HTML, CSS and a few lines of JS)
portrait.jpg   profile photo
papers/        PDFs linked from "Research projects"
.nojekyll      tells GitHub Pages to serve files as-is
```

## Edit

Open `index.html` in any editor, change the text, commit, push. GitHub Pages redeploys in about a minute.

- Add a talk: copy one `<li class="talk">…</li>` line inside the right year.
- Add a PDF: drop it in `papers/` and link it as `papers/<file>.pdf`.
- Accent colour: change `--accent` at the top of the `<style>` block.

## Custom domain (optional)

Create a file called `CNAME` containing just the domain (e.g. `philippzimmer.com`), then point the domain's DNS at GitHub Pages and set the domain under Settings → Pages.
