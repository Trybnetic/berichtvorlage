default: bericht

bericht:
	pdflatex -synctex=1 -interaction=nonstopmode -halt-on-error -file-line-error "bericht".tex
	biber "bericht"
	pdflatex -synctex=1 -interaction=nonstopmode -halt-on-error -file-line-error "bericht".tex

clean:
	rm -f *.bbl *.blg *.log *.out *.synctex.gz *.toc *.aux *.bcf *.run.xml

distclean: clean
	rm bericht.pdf

pdf: bericht clean
