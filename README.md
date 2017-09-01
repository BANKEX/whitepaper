```bash
sudo apt install biber
```

TexMaker settings for QuickBuild

```
pdflatex %.tex|biber %|pdflatex %.tex|evince %.pdf
```