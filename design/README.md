# Game Design Document

## Setup

To compile this LaTeX document yourself, follow these steps:

1. Install [TeX Live](https://www.tug.org/texlive/)
2. Install packages:
   ```sh
   $ tlmgr install footmisc siunitx paralist wrapfig minted acronym xstring bigfoot csquotes din1505
   ```
3. Run pdfLaTeX twice:
   ```sh
   $ pdflatex main.tex && pdflatex main.tex
   ```
