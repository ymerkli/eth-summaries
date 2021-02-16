
NOTE  = !! change the next line to fit your filename; no spaces at file name end !!
FILE  = report

all:
	pdflatex $(FILE)
	bibtex $(FILE)
	pdflatex $(FILE)
	pdflatex $(FILE)

clean:
	rm -f *.dvi *.log *.aux *.bbl *.blg *.toc *.lof *.lot *.cb *.~ *.out *.fdb_latexmk *.fls