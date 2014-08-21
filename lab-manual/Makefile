# Short Makefile primer:
#   $* -- basename of matching file (i.e. the % in a pattern)
#   $< -- first dependency in a rule
#   $@ -- name of target

SOURCES := $(wildcard lab*.md)
GENERATED := $(SOURCES:.md=.pdf)
GEN_DIR := 'generated'
DROPBOX := '/Users/mcraig/Dropbox/MSUM/Classes/PHYS160L'

%.pdf: %.md copyright_info.tex
	# Generate a timestamp for inclusion in the header.
	$(shell echo '\\rfoot{\\footnotesize generated '$(shell date "+%m/%d/%Y %H:%M")'}' >> timestamp.tex)
	pandoc -o $*.tex -H copyright_info.tex -H timestamp.tex $<
	# Put output in a temporary directory to reduce clutter
	mkdir -p tmp
	mkdir -p $(GEN_DIR)
	pdflatex -output-directory=tmp $*.tex
	pdflatex -output-directory=tmp $*.tex
	pdflatex -output-directory=tmp $*.tex
	# Automatically pre-pend the number of this lab in the sequence
	# it is in this semester.
	$(eval LABNUM := $(shell grep -n $< index.md | cut -f1 -d: | xargs printf "%02d"))
	echo $(LABNUM)
	mv tmp/$@ $(GEN_DIR)/$(LABNUM)-$@
	# Remove the clutter.
	rm -rf tmp $*.tex timestamp.tex

manual: index.md
	$(shell echo '\eject' > eject.md)
	pandoc --toc --toc-depth=1 -o manual.pdf eject.md $(shell cat index.md)
	rm eject.md

all: $(GENERATED)

publish:
	cp $(GEN_DIR)/* $(DROPBOX)
