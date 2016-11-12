bericht:
	pdflatex -synctex=1 -interaction=nonstopmode -halt-on-error -file-line-error "bericht".tex
	biber "bericht"
	pdflatex -synctex=1 -interaction=nonstopmode -halt-on-error -file-line-error "bericht".tex

clean:
	rm -f *.bbl *.blg *.log *.out *.synctex.gz *.toc *.aux *.bcf *.run.xml
	rm -rf auto/ */auto/

distclean:
	rm *.bbl *.blg *.log *.out *.synctex.gz *.toc *.aux bericht.pdf

pdf:
	pdflatex -synctex=1 -interaction=nonstopmode "bericht".tex
	bibtex "bericht".aux
	pdflatex -synctex=1 -interaction=nonstopmode "bericht".tex
	pdflatex -synctex=1 -interaction=nonstopmode "bericht".tex
	rm *.bbl *.blg *.log *.out *.synctex.gz *.toc *.aux

default: bericht
