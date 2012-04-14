
# Andrew G. West - 9/13/2009
# Make-file for the CIS400/4001 Progress Report Specification

	# Filenames to be-used in compilation
MAIN=final_spec
TEX=final_spec.tex
DVI=final_spec.dvi
PS=final_spec.ps

	# Core compilation commands
CC=latex
BB=bibtex
BUILDPS=dvips -o $(PS) 
BUILDPDF=ps2pdf

all:$(TEX) $(BIB)
	$(CC) $(TEX)
	$(BB) $(MAIN)
	$(CC) $(TEX)
	$(CC) $(TEX)
	$(BUILDPS) $(DVI)
	$(BUILDPDF) $(PS)

clean:
	rm -rf $(DVI) $(PS) *.log *.aux *.bbl *.blg
