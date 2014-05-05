memoir-thesis-cornell
=====================

LaTeX "memoir" template for Cornell University dissertation.  The generated
document should (hopefully) comply with the university requirements for a
dissertation while being more attractive than the university-provided templates.
Use of the `memoir` package provides great flexibility when customizing the
style and structure.

Requirements
------------

* TeX Live 2013 (or later), or equivalent

Usage
-----

1. Modify the title, author, and date in the preamble
2. Modify the year on the copyright and abstract pages
3. Add references to BibTeX database
4. Replace placeholder text with the contents of your thesis
5. Compile with `latexmk -pdf <filename>`

Notes
-----

* The default font is Palatino, which is Cornell's primary typeface and is
  freely available.  Unfortunately, Cornell's secondary typeface, Frutiger, is
  not available for free.  The default sans-serif font is currently Helvetica,
  but others (like Myriad) may be more appropriate.
* The default bibliography style is `apsrev4-1`, which is a concise style used
  by the American Physical Society's "Physical Review" journals.  While it may
  not be ideally suited for a dissertation's bibliography, it does make good use
  of the `doi` and arXiv-related fields.
* No thesis using this template has yet been submitted, so I cannot guarantee
  that it meets all of the formatting requirements at this time.
