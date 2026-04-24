# Templates LaTeX minimalistes

Ce depot contient trois templates simples et autonomes, chacun en francais et en anglais :

- `beamer/presentation_fr.tex` : presentation Beamer en francais
- `beamer/presentation_eng.tex` : Beamer presentation in English
- `article/article_fr.tex` : article scientifique en francais
- `article/article_eng.tex` : scientific article in English
- `these/manuscript_fr.tex` : manuscrit de these en francais
- `these/manuscript_eng.tex` : thesis manuscript in English

Compilation :

```sh
latexmk -cd -pdf beamer/presentation_fr.tex
latexmk -cd -pdf beamer/presentation_eng.tex
latexmk -cd -pdf article/article_fr.tex
latexmk -cd -pdf article/article_eng.tex
latexmk -cd -pdf these/manuscript_fr.tex
latexmk -cd -pdf these/manuscript_eng.tex
```

Ou, si `latexmk` n'est pas disponible :

```sh
pdflatex beamer/presentation_fr.tex
pdflatex beamer/presentation_eng.tex
pdflatex article/article_fr.tex
pdflatex article/article_eng.tex
pdflatex these/manuscript_fr.tex
pdflatex these/manuscript_eng.tex
```
