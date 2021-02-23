# 2021-park-ans-summer

This repository holds data and files for the "Multiphysics Benchmark Results
from Moltres" conference summary submitted to the 2021 ANS Annual Meeting.
The summary presents latest benchmarking results for coupled
neutronics/thermal-hydraulics simulations in Moltres.

### Instructions
1. Building the pdf file for the summary
- To build on a Linux machine run ``make``.
- To build on a Windows machine run
  - ``pdflatex main.tex``
  - ``bibtex main.tex``
  - ``pdflatex main.tex``
  - ``pdflatex main.tex``
2. To get rid of built files, ``make clean.``
