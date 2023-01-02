SHELL=/bin/bash
DOK=DSV_Toni

.SUFFIXES:
.SUFFIXES: .bib .pdf .tex
.PHONY: clean

run: $(DOK).pdf


$(DOK).pdf:  $(DOK).tex
	pdflatex $(DOK).tex -draftmode
	pdflatex $(DOK).tex 

clean:
	rm -f *.{aux,lof,log,lot,lol,,bcf,toc,bbl,blg,run.xml,out}
