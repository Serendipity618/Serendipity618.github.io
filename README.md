# He Cheng – Academic Website

Source code for [He Cheng's academic website](https://serendipity618.github.io/), built with [Quarto](https://quarto.org/).

## Local development

Install Quarto 1.10.18 (the version pinned in CI), then run:

```bash
quarto preview
```

To regenerate the deployable site in `docs/`:

```bash
quarto render
```

Pushes to `main` are rendered and published by the GitHub Actions workflow in `.github/workflows/deploy.yml`.

## Repository maintenance

- Keep the root pages and the `projects/` and `publications/` detail pages: each renders to an existing public URL, even when not linked in the main navigation.
- `publications.yml`, `pub-listing.ejs`, and `pub-listing.css` generate the Papers listing. `bibtex-copy.html` and `back-to-top.html` provide shared interactions.
- `assets/` contains the portrait and locally hosted fonts; `files/` contains the linked CV. Preserve their URLs and font licenses.
- `docs/` is generated and ignored by Git. GitHub Actions runs `quarto render` on a clean checkout, then deploys `docs/` as a Pages artifact. Do not commit generated HTML, Quarto libraries, search data, or copied assets; edit their sources and rebuild instead.
- `.quarto/` and `_freeze/` are ignored local caches, not deployment inputs. The current site rebuilds without them.
- Retain both root license notices unless their attribution obligations have been established; a missing code reference does not make a license obsolete.

## Source structure

```text
.github/workflows/deploy.yml  # pinned Quarto build and Pages deployment
_quarto.yml                  # site, navigation, theme, and render configuration
*.qmd                        # six top-level pages
projects/*/index.qmd          # eight project routes
publications/*/index.qmd      # eight publication routes
publications.yml             # structured publication listing data
pub-listing.ejs               # listing markup
styles.css, pub-listing.css, homepage.css
back-to-top.html, bibtex-copy.html
assets/                      # portrait, six font faces, and font licenses
files/He-Cheng-CV.pdf
README.md, LICENSE.md, LICENSE-template.txt, .gitignore
```

The 22 page sources preserve existing routes. Quarto's framework libraries are supplied by the pinned build tool, not vendored in source control. The two small interaction includes remain separate because back-to-top is shared site-wide while citation copying is used on publication pages. No Node or Python package installation is required to build the site.
