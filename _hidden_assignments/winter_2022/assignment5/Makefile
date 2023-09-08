all:
	latexmk -pdf assignment5_soln
	python3 ../stripsoln.py assignment5_soln.tex >assignment5.tex
	latexmk -pdf assignment5
	mv assignment5.pdf ../../documents/assignments/
	mv assignment5.tex ../../documents/assignments/
#	cp assignment5.pdf ~/Dropbox/RLTheoryCourse/
