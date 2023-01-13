SHELL=/bin/bash
DOK=DSP_Toni

.SUFFIXES:
.SUFFIXES: .bib .pdf .tex
.PHONY: clean

run: $(DOK).pdf


$(DOK).pdf:  $(DOK).tex
	pdflatex -shell-escape $(DOK).tex -draftmode
	pdflatex -shell-escape $(DOK).tex 

clean:
	rm -f *.{aux,lof,log,lot,lol,bcf,toc,bbl,blg,run.xml,out}
	rm -fr ./_minted-*
