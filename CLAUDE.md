# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this is

The central **Quarto** documentation hub for the `ikddsystem` GitHub organisation,
intended to serve at https://ikddsystem.github.io. It links the pkgdown reference sites
of the R packages, renders the auto-generated data dictionary / DRS / CRF, and links the
private governance repo.

## Commands

```bash
quarto preview   # live preview
quarto render    # build to _site/ (gitignored)
```

Quarto is installed locally. No tests. CI (`.github/workflows/publish.yml`) renders and
deploys `_site/` to the `gh-pages` branch on push to `main`, on `workflow_dispatch`, and
on a `repository_dispatch` of type `docs-changed` sent by `ikdds-etl`'s regenerate-docs
workflow.

## Layout

| File | Role |
|---|---|
| `_quarto.yml` | Site config: navbar, docked sidebar, cosmo theme. Add new pages here. |
| `index.qmd` | Landing page with the eMed → ETL → REDCap → dashboard Mermaid flow and repo table. |
| `architecture.qmd` | Single-source-of-truth diagram and the six system layers. |
| `data-dictionary.qmd` | Explains the generated docs and lists forms with ETL status. |
| `reference/data-dictionary.md`, `reference/DRS.md`, `reference/CRF.md` | **Generated** by `ikdds::generate_markdown_docs()` and pushed here by ETL CI. Never hand-edit. To change them, change `ikdds-etl` (`data-raw/`, `R/markdown-docs.R`). |

Mermaid diagrams are native Quarto `{mermaid}` blocks; no extra tooling needed.

## Conventions

- Keep `_quarto.yml` sidebar entries pointing at repo URLs for anything not hosted here
  (pkgdown sites live at `https://ikddsystem.github.io/ikdds-etl/` and
  `.../ikdds-dashboard/`, published from each package's own `gh-pages`).
- The form table in `data-dictionary.qmd` (field counts, implemented vs stub) is
  hand-maintained and must be updated when the ETL implements a form or the dictionary
  changes. Cross-check against `reference/data-dictionary.md`.
- Don't add content copied from the private governance repo (staff names/emails). Link
  to it instead.
- No patient data, ever, including in example tables.

## Known state

- The repo is **private**, so GitHub Pages does not serve the site on the Free plan even
  though the workflow deploys to `gh-pages` successfully. Flip to public (after a
  secret/PII scan) or upgrade the plan to serve it.
- Automatic refresh of `reference/*.md` requires the org secret `DOCS_DISPATCH_TOKEN`;
  until it is set, copies must be refreshed manually from `ikdds-etl`.
