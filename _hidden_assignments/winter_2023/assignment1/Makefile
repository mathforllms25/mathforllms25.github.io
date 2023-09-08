COURSE_YEAR = winter_2023

all:
	latexmk -pdf assignment1_soln
	python3 ../../stripsoln.py assignment1_soln.tex >assignment1.tex
	latexmk -pdf assignment1
	mv assignment1.pdf ../../../documents/assignments/$(COURSE_YEAR)/
	mv assignment1.tex ../../../documents/assignments/$(COURSE_YEAR)/
#	cp assignment1.pdf ~/Dropbox/RLTheoryCourse/
