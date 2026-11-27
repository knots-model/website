# KNOTS website

One-page website for KNOTS, built by GitHub Pages (Jekyll) from Markdown.

| file | what to edit there |
|---|---|
| `index.md` | all the text: title, introduction, the three cards, footer |
| `assets/style.css` | colours, fonts, spacing (colours are at the top) |
| `assets/knots-logo.png` | the logo (transparent background); `knots-logo-white.png` is the same on white |
| `_layouts/default.html` | page frame (fonts, tab title); rarely needed |

## Publish

1. Put these files at the root of a repository (or in a `docs/` folder).
2. On GitHub: **Settings → Pages → Build and deployment → Deploy from a branch**, choose the branch and folder (`/ (root)` or `/docs`), **Save**.
3. After a minute the site is at `https://<user>.github.io/<repository>/`.

GitHub Pages on a private repository needs a paid plan; a separate public repository for the website avoids that.

## Editing tips

- Write normal Markdown. Keep the `<div class="card" markdown="1">` and `</div>` lines around each card.
- To add a card, copy one `<div class="card" ...> ... </div>` block. Three cards per row on wide screens, one on phones.
- `{: .subtitle}` under a line gives it a style from `style.css`.
