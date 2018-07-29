# Sourcefiles
MEXT=md
SRCS=$(wildcard *.$(MEXT))
PDFS=$(SRCS:.$(MEXT)=.pdf)
TEXS=$(SRCS:.$(MEXT)=.tex)

# Latexmk/pandoc options
LATEXMKOPT=-pdf -f -pvc-
LATEX=xelatex
LATEXOPT=--shell-escape
OUT=beamer
FLAG=--template=default.latex --biblatex --slide-level=2

all:	$(PDFS) $(TEXS)

%.tex: %.$(MEXT)
	@echo pandoc $<...
	@pandoc -t $(OUT) $< -o $@ -s $(FLAG)

%.pdf: %.tex
	@echo latexmk $<...
	@latexmk $(LATEXMKOPT) -pdflatex="$(LATEX) $(LATEXOPT) %O %S" $< --silent

watch: $(SRCS)
	@echo Watching for changes...
	@while true; do \
		inotifywait --event MODIFY -q -r $^; \
		make; \
	done

clean:
	@echo Cleaning...
	# @latexmk -c $(TEXS) -f
	@rm -rf *~ *.tmp
	@rm -f *.tex *.nav *.snm *.bcf *.bbl *.blg *.aux *.end *.fls *.log *.out *.fdb_latexmk *.xml *.gz *.vrb *.aux.copy *.auxlock *.for

debug:
	@echo Debugging...
	@latexmk $(LATEXMKOPT) -pdflatex="$(LATEX) $(LATEXOPT) %O %S" $<

.PHONY: all watch clean debug
