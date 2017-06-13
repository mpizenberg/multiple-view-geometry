# Multiple View Geometry

This repository holds the transcript of the introductory
[course provided by Daniel Cremers][youtube]
on multiple view geometry.

[youtube]: https://www.youtube.com/playlist?list=PLTBdjV_4f-EJn6udZ34tht9EVIW7lbeo4

It also served me as a reminder on how to write all 'maths things' in LaTeX.
I initially wanted to take only quick notes using dropbox paper.
However, the lack of support of advance maths (multiline, ...)
convinced me eventually to go come back to pure LaTeX.

## Compilation

You will need a full latex installation on your system.
Also, I love the semi-live preview update on save feature.
So install the lightweight mupdf reader or modify the reader
to use in the config file `.latexmkrc`.
Once set up, all you need is:
```sh
latexmk main.tex
```
