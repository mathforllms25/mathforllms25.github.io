COURSE_YEAR = winter_2023

all:
	latexmk -pdf assignment2_soln
	python3 ../../stripsoln.py assignment2_soln.tex >assignment2.tex
	latexmk -pdf assignment2
	mv assignment2.pdf ../../../documents/assignments/$(COURSE_YEAR)/
	mv assignment2.tex ../../../documents/assignments/$(COURSE_YEAR)/
#	cp assignment2.pdf ~/Dropbox/RLTheoryCourse/
