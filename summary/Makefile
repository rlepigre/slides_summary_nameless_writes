#
# Makefile for latex pdf generation.
#

NAME = summary

all: gen clean

gen: $(NAME).tex
	pdflatex $(NAME).tex

clean:
	rm -f *~ $(NAME).aux $(NAME).log $(NAME).toc $(NAME).bbl $(NAME).blg

distclean: clean
	rm -f $(NAME).pdf
