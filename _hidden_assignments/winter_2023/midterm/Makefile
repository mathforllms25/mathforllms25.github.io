COURSE_YEAR = winter_2023

all:
	latexmk -pdf midterm_soln
	python3 ../../stripsoln.py midterm_soln.tex >midterm.tex
	latexmk -pdf midterm 
	mv midterm.pdf ../../../documents/assignments/$(COURSE_YEAR)/
	mv midterm.tex ../../../documents/assignments/$(COURSE_YEAR)/
#	cp midterm.pdf ~/Dropbox/RLTheoryCourse/
