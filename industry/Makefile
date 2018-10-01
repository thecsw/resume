COMPILER = xelatex
NAME = industry
GARBAGE = $(OUTPUT_NAME).aux $(OUTPUT_NAME).log $(OUTPUT_NAME).out
TEXFLAGS = -shell-escape
OUTPUT_NAME = Sagindyk_resume

$(NAME):
	$(COMPILER) $(TEXFLAGS) -jobname=$(OUTPUT_NAME) $(NAME).tex
	$(COMPILER) $(TEXFLAGS) $(NAME).tex
clean:
	rm $(GARBAGE)
