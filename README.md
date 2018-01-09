# A Friendly Introduction to Software Testing
Bill Laboon

_for AKS and CKN_

## Compiling this e-book

This textbook is comprised of a series of Markdown files, compiled into PDF
format via PDF\LaTeX.  Required dependencies, available through most package
managers, include:

* [`pandoc`](http://johnmacfarlane.net/pandoc/)
* [`pdflatex`](http://www.tug.org/applications/pdftex/)
* `xelatex` --- available in [TeX Live](http://tug.org/texlive/)

With the above packages installed and added to your `PATH`, simply run `make`
to compile this document.  The output is a PDF file named
`software-testing-laboon-ebook.pdf`.

## Compiling on Ubuntu 

**Tested on 16.04 LTS**

* `sudo apt install texlive-latex-recommended pandoc texlive-xetex`
* `make`