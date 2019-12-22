PDF=pdflatex
OBJS=*.aux *.log *.out *.pdf *.bbl *.blg

.PHONY: cv clean

all: cv

clean:
	rm -rf $(OBJS)

cv:
	$(PDF) cv.tex
	cp cv.pdf ../static/propson_cv.pdf