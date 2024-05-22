A simple LaTeX document that allows you to create work sheets to practice
conjugation verbs in Bulgarian.

To generate a PDF, you need to install the [Linux Libertine
Font](https://en.wikipedia.org/wiki/Linux_Libertine) and you will need a LaTex
engine that supports UTF-8, e.g. `xelatex`:

    xelatex worksheet.tex

or using `latexmk`:

    latexmk -xelatex worksheet.tex
