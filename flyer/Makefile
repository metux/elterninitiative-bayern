
A5=flyer-elterninitiative-2x-imprint.pdf
ALLDOC=$(A5)

all: $(ALLDOC)

%.pdf:	%.tex
	pdflatex $<

clean:
	rm -f $(ALLDOC) *.log *.aux

view:	$(A5)
	xdg-open $(A5)
