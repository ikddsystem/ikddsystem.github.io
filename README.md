# ikddsystem.github.io

Central documentation hub for the [IKDDS](https://github.com/ikddsystem) organisation,
built with [Quarto](https://quarto.org) and published to GitHub Pages at
**https://ikddsystem.github.io**.

It links each repository's auto-generated `pkgdown` reference and the generated
specifications. The ETL data dictionary is the single source of truth.

## Build locally

```bash
quarto preview   # live preview
quarto render    # build to _site/
```

CI (`.github/workflows/publish.yml`) renders and deploys on push to `main`, and on a
`docs-changed` repository_dispatch from `ikdds-etl`.
