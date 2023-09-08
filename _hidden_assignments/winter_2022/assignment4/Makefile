COURSE_YEAR = winter_2022

all:
	latexmk -pdf assignment4_soln
	python3 ../../stripsoln.py assignment4_soln.tex >assignment4.tex
	latexmk -pdf assignment4
	mv assignment4.pdf ../../../documents/assignments/$(COURSE_YEAR)/
	mv assignment4.tex ../../../documents/assignments/$(COURSE_YEAR)/
#	cp assignment4.pdf ~/Dropbox/RLTheoryCourse/
