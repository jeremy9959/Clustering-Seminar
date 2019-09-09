all : 20190910.html 20190910.pdf 20190910.md

%.html : %.md
	pandoc -s --mathjax -t slidy $< -o $@

%.pdf : %.md
	pandoc -s --mathjax -t beamer $< -o $@
