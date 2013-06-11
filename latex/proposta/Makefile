tex:
	latex proposta-rcaf.tex
	latex proposta-rcaf.tex

bib:
	bibtex proposta-rcaf.aux

view:
	dvipdfm proposta-rcaf.dvi
	gnome-open proposta-rcaf.pdf

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

