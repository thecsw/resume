COMPILER = xelatex
NAME = ref
GARBAGE = $(NAME).aux $(NAME).log $(NAME).out
TEXFLAGS = -shell-escape

$(NAME):
	$(COMPILER) $(TEXFLAGS) $(NAME).tex
	$(COMPILER) $(TEXFLAGS) $(NAME).tex
clean:
	rm $(GARBAGE)
