#
# Makefile for latex pdf generation.
#

NAME = slides

all: gen clean

gen: $(NAME).tex
	rubber --inplace --maxerr -1 --short --force --warn all --pdf $(NAME).tex

clean:
	rm -f *~ $(NAME).vrb $(NAME).aux $(NAME).log $(NAME).snm $(NAME).nav $(NAME).out $(NAME).toc

