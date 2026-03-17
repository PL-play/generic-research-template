# Generic Research Template

This directory is a simplified, school-neutral research writing template derived from the original thesis project.

## What was removed

- University-specific cover pages and logos
- Authorization and declaration pages
- Committee and review pages
- Resume and school-specific metadata

## What was kept

- Core chapter writing examples (`data/chap01` to `data/chap04`)
- Figure, table, algorithm, formula examples
- Bibliography dataset (`ref/refs.bib`)
- Appendix example (`data/appendix.tex`)

## Build

Run in this directory:

```bash
latexmk -xelatex main.tex
```

## Entry file

- `main.tex`: generic cover + front matter + chapters + bibliography
