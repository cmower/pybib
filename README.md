# Pybib

Pybib provides a set of command line utilities (written in Python 2) to check,
merge, sort, filter, and convert BibTeX files. Also include a tool to lookup
references on Google scholar and insert the URL into the file.

Original author: [Peter Corke](http://petercorke.com/wordpress/), 2007. See also
[CTAN](https://ctan.org/pkg/pybib?lang=en).

## Scripts

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

bibsort		sort by date, or key

bibsummary	summary of number of entries by type

bibnames	display author names and number of occurrences

bibclean    Clean bib entries.

## Setup

1. `$ git clone https://github.com/cmower/pybib.git`
1. Add `/path/to/pybib` to your path.
1. `$ pip2 install doi2bib`
