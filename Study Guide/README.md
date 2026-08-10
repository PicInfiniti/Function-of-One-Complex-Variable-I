# LaTeX study guide

This directory contains the book-style LaTeX study guide. Its parts, chapters,
sections, theorem environments, table of contents, and indexes are native
LaTeX. Individual results use the appropriate `theorem`, `definition`,
`lemma`, `corollary`, `proposition`, `remark`, `formula`, or `exercise`
environment instead of becoming document subdivisions. Practice problems use
numbered LaTeX exercise environments rather than HTML-style checkboxes. The
complete book---design and mathematical content---is contained in one
self-contained LaTeX source file.

Build from this directory:

```sh
latexmk -pdf main.tex
```

Edit `main.tex` directly when changing either the content or the design.
