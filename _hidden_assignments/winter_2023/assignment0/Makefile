COURSE_YEAR = winter_2023

all:
	latexmk -pdf assignment0_soln
	python3 ../../stripsoln.py assignment0_soln.tex >assignment0.tex
	latexmk -pdf assignment0
	mv assignment0.pdf ../../../documents/assignments/$(COURSE_YEAR)/
	mv assignment0.tex ../../../documents/assignments/$(COURSE_YEAR)/
#	cp assignment0.pdf ~/Dropbox/RLTheoryCourse/
