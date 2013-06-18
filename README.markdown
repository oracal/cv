This is my markdown cv inspired by [mwhite](https://github.com/mwhite) and his [resume template](https://github.com/mwhite/resume)
that can be used with [Pandoc](http://johnmacfarlane.net/pandoc/) to create PDF and HTML output.

Dependencies
------------

* Pandoc >= 1.9 (you can adjust the Makefile to use an earlier version -- the
  arguments format changed)
* A Tex installation with pdflatex and the latex opensans font, and some
  packages needed by pandoc.  On Ubuntu you can get this by installing
  `texlive`, `texlive-latex-extra`, and `texlive-fonts-extra`.

Usage
-----

Simply run `make` to generate PDF and HTML versions of each .md file in the directory.
