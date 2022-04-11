NAME = proj3
LOGIN = xvacla32

default: pdf clean

pdf:$(NAME).tex
	latex $(NAME).tex
	latex $(NAME).tex
	dvips  -t a4 $(NAME).dvi
	ps2pdf $(NAME).ps

archive:
	tar -cvzf $(LOGIN)-fit.tar.gz $(NAME).tex Makefile

clean:
	rm -f $(NAME).aux $(NAME).dvi $(NAME).log $(NAME).out $(NAME).ps