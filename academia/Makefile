COMPILER = xelatex
NAME = cv
GARBAGE = $(OUTPUT_NAME).aux $(OUTPUT_NAME).log $(OUTPUT_NAME).out
TEXFLAGS = -shell-escape
OUTPUT_NAME = Sagindyk_CV

$(NAME):
	$(COMPILER) $(TEXFLAGS) -jobname=$(OUTPUT_NAME) $(NAME).tex
	$(COMPILER) $(TEXFLAGS) $(NAME).tex
clean:
	rm $(GARBAGE)
