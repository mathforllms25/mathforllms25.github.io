COURSE_YEAR = winter_2022

all:
	latexmk -pdf assignment3_soln
	python3 ../../stripsoln.py assignment3_soln.tex >assignment3.tex
	latexmk -pdf assignment3
	mv assignment3.pdf ../../../documents/assignments/$(COURSE_YEAR)/
	mv assignment3.tex ../../../documents/assignments/$(COURSE_YEAR)/
#	cp assignment3.pdf ~/Dropbox/RLTheoryCourse/
