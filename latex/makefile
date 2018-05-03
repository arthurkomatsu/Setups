all:
	make clean
	pdflatex main.tex
	pdflatex main.tex
	if ! pgrep evince; then (nohup evince main.pdf &> /dev/null &); fi
clean:
	rm -f *~ *.dvi *.ps *.backup *.aux *.log *.o
	rm -f *.lof *.lot *.bbl *.blg *.brf *.toc *.idx
	rm -f *.pdf *.out *.tex.bk *.fdb_latexmk *.fls


