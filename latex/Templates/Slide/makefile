all:
	clear
	pdflatex slide.tex
	nohup evince *.pdf >/dev/null &
clean:
	rm -f *~ *.dvi *.ps *.backup *.aux *.log
	rm -f *.lof *.lot *.bbl *.blg *.brf *.toc *.idx *.fls *.nav *.out *.snm *.fdb_latexmk
	rm -f *.pdf
