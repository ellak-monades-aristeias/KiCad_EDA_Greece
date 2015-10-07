TEX  = /usr/bin/latexmk
ECHO = /bin/echo

OUTDIR = tmp

TEXOPTS = -xelatex -silent -outdir=$(OUTDIR)

# all .tex files will be considered as "sources"
SOURCES = $(wildcard *.tex)

# all .pdf files with same base name as the sources 
# will be potential "targets"
TARGETS = $(SOURCES:.tex=.pdf)

# mark all targets as phony so that they are rebuilt
# every time we run make
.PHONY	: all clean $(TARGETS)

# a plain make will build all targets
all 	: $(TARGETS)

# static pattern rule for generating pdf from tex
$(TARGETS): %.pdf: %.tex
	@$(ECHO) -e "\n\033[34m\033[1m-> Considering file $<\033[0m"
	@$(TEX) $(TEXOPTS) $<

clean	:
	@$(TEX) $(TEXOPTS) -C
	@/bin/rm -rf $(OUTDIR)

