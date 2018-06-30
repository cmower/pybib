# Pybib

Pybib provides a set of command line utilities (written in Python) to check, merge, sort, filter, and convert BibTeX files. Original code by [Peter Corke](http://petercorke.com/wordpress/) hosted at [CTAN](https://ctan.org/pkg/pybib?lang=en). This repository contains modified code by C. E. Mower, 2018.

## Original README by Peter Corke

BibEntry.py	a general class for a bibliographic entry

Bibliography.py	a general container class for bibliographic entries

BibTeX.py	a BibTeX specific superclass for BibEntry and Bibliography

bib2html	convert a bibfile to HTML

bibcat		concatenate bibfiles, parse and regenerate

bibdvi		convert a bibfile to dvi

bibfilter	find specific records by field, date, etc

bibgoogle	find references on Google scholar

bibkey		lookup by citekey

biblint		report missing fields in input files

biblist		list bibliography in non-BibTeX format

bibmerge	merge bibliographies and attempt to remove duplicate entries

bibsort		sort by date

bibsummary	summary of number of entries by type

bibnames	display author names and number of occurences


peter corke  2007.

## Description as appears on CTAN

Pybib provides a set of command line utilities (written in Python) to check, merge, sort, filter, and convert BibTeX files. Also include a tool to lookup references on Google scholar and insert the URL into the file.

The package builds on the author’s experience writing the earlier tkbibtex; it is hoped that this code is more readily maintainable.

## Setup

1. `$ git clone https://github.com/cmower/pybib.git`
1. On Linux/Mac add `export BIBPATH="/path/to/pybib"; export PATH=$PATH:$BIBPATH` to your `.bashrc`/`.bash_profile`. If you use Windows set the environment variables `BIBPATH` and update your `PATH` variable to contain `BIBPATH` (untested for Windows).
