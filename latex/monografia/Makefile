tex:
	latex monografia-rcaf.tex
	latex monografia-rcaf.tex

bib:
	bibtex monografia-rcaf.aux

view:
	dvipdfm monografia-rcaf.dvi
	gnome-open monografia-rcaf.pdf

# Usage:
#
# make tex
# make bib
# make tex
# make view
#
# I didn't make a rule that does all of it once, so I can read error messages in each separated step.
#

.PHONY: tex bib view

