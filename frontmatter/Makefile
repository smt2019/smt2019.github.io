all : pc_review.pdf preface.pdf

%.pdf : %.tex
	xelatex $<
	xelatex $<

clean :
	rm -rf *.aux *.log *.out

dist-clean : clean
	rm -rf pc_review.pdf preface.pdf

.PHONY : all clean dist-clean
