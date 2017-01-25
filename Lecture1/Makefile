OUTPUTDIR=build
FILENAME= ReadingNote_Troclet_Philippe.tex
PDF=$(FILENAME:.tex=.pdf)
all:
	test -d build || mkdir build
	pdflatex -output-directory ${OUTPUTDIR} -file-line-error ${FILENAME}
	mv ${OUTPUTDIR}/${PDF} .

clean:
	rm -r build ${PDF}
