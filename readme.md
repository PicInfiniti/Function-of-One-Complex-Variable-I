# Function of One Complex Variable I

This repository collects my work while studying complex analysis, mainly from
John B. Conway's *Functions of One Complex Variable I* and past complex analysis
qualifying exams.

## Contents

- `Exercise/complex.tex` contains solutions to selected exercises from Conway's
  book. The compiled PDF is `Exercise/complex.pdf`.
- `Qualifying Exam/main.tex` contains qualifying exam material. August 2018
  includes solved problems; August 2020, August 2024, and January 2025 currently
  include problem statements prepared from the original exam PDFs.

## Build

Compile either document with `latexmk`:

```bash
cd Exercise
latexmk -pdf complex.tex
```

```bash
cd "Qualifying Exam"
latexmk -pdf main.tex
```

To remove LaTeX build artifacts:

```bash
latexmk -c
```

## Notes

The documents are written as working study notes. Some solutions may be revised
over time for clarity, correctness, or style.
