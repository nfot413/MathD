PROJ = paper

all: $(PROJ).pdf

$(PROJ).pdf: $(PROJ).tex
	xelatex $(PROJ).tex
	bibtex $(PROJ)
	xelatex $(PROJ).tex
	xelatex $(PROJ).tex

clean:
	rm -f *.aux *.log *.out *.toc *.bbl *.blg *.lof *.lot *.pdf *.synctex.gz