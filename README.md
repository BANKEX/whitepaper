# BankEx: The Smart White Paper

## Installing TeX + BibTeX

```bash
sudo apt update
sudo apt install texlive texlive-lang-cyrillic cm-super texlive-bibtex-extra biber
```

## Installing TeX Maker

```bash
sudo apt install texmaker
```

## TexMaker settings for QuickBuild

```
pdflatex %.tex|biber %|pdflatex %.tex|evince %.pdf
```