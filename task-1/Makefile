.PHONY: pdf wordcount check clean

pdf:
	latexmk -lualatex -halt-on-error main.tex

wordcount:
	texcount -total -utf8 kursinis.tex

check:
	chktex kursinis.tex

clean:
	git clean -dfX
