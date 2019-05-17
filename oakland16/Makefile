main.pdf : *.tex
	pdflatex -shell-escape main

full: *.tex
	pdflatex -shell-escape main
	bibtex main
	pdflatex -shell-escape main
	pdflatex -shell-escape main


clean: 
	rm -f *.aux *.dep *.dpth *.log *.blg *.bbl  *.auxlock *.out main*.pdf

