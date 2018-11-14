COMPILER = xelatex
NAME = academia
GARBAGE = $(OUTPUT_NAME).aux $(OUTPUT_NAME).log $(OUTPUT_NAME).out
TEXFLAGS = -shell-escape
OUTPUT_NAME = Sagindyk_cv

$(NAME):
	$(COMPILER) $(TEXFLAGS) -jobname=$(OUTPUT_NAME) $(NAME).tex
	$(COMPILER) $(TEXFLAGS) -jobname=$(OUTPUT_NAME) $(NAME).tex
clean:
	rm $(GARBAGE)
