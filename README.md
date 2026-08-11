# He Cheng – Academic Website

Source code for [He Cheng's academic website](https://serendipity618.github.io/), built with [Quarto](https://quarto.org/).

## Local development

Install Quarto 1.10.18 or newer, then run:

```bash
quarto preview
```

To regenerate the deployable site in `docs/`:

```bash
quarto render
```

Pushes to `main` are rendered and published by the GitHub Actions workflow in `.github/workflows/deploy.yml`.
