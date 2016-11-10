bericht:
	pdflatex -synctex=1 -interaction=nonstopmode "bericht".tex
	bibtex "bericht".aux
	pdflatex -synctex=1 -interaction=nonstopmode "bericht".tex
	pdflatex -synctex=1 -interaction=nonstopmode "bericht".tex

clean:
	rm *.bbl *.blg *.log *.out *.synctex.gz *.toc *.aux

distclean:
	rm *.bbl *.blg *.log *.out *.synctex.gz *.toc *.aux bericht.pdf

pdf:
	pdflatex -synctex=1 -interaction=nonstopmode "bericht".tex
	bibtex "bericht".aux
	pdflatex -synctex=1 -interaction=nonstopmode "bericht".tex
	pdflatex -synctex=1 -interaction=nonstopmode "bericht".tex
	rm *.bbl *.blg *.log *.out *.synctex.gz *.toc *.aux

default: bericht
