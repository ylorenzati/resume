# This is my resume in latex

To build CV in PDF format :
```bash
$ pdflatex main.tex
```


To convert it to HTML using pdf2htmlEX container :
```bash
docker run -ti --rm -v `pwd`:/pdf bwits/pdf2htmlex pdf2htmlEX main.pdf
```

