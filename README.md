# Office

> Dokumente und Formulare des Chaos Computer Club Potsdam e. V.

## Erzeugen von PDFs

Um die LaTeX-Quellen in PDFs übersetzen zu können, werden XeLaTeX, eine aktuelle TeX-Live-Installation, [latexmk][latexmk] sowie die Schriftart [Barlow][barlow] benötigt.

In den jeweiligen Verzeichnissen befinden sich Makefiles, mit denen die Dokumente gebaut werden können:

```sh
# PDF erzeugen
make

# PDF bei jeder Änderung automatisch erzeugen
make watch
```

[barlow]: https://tribby.com/fonts/barlow/
[latexmk]: https://mg.readthedocs.io/latexmk.html
