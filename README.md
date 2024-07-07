# dajmcdon latex files

## `paper/dajmcdon.bib`

1. The file is sorted by cite key.
2. The cite key is McDonaldBien2021 (last names of the first 2 authors in
camel case followed by the 4 digit year).
3. If the cite key exists, add a lower case letter to disambiguate.
4. You should be able to add a reference anywhere in the file, then run
``` bash
bibtool -s dajmcdon.bib -o dajmcdon.bib
```
to sort and correctly generate the cite key. (If you need to install `bibtool`,
you can use Homebrew on a Mac `brew install bib-tool`.)
5. Try to avoid duplicates.


## `paper/dajmcdon.tex`


