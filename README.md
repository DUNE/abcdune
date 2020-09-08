# ABC DUNE

## Purpose
Python script that converts the DUNE LaTeX glossary into HTML.
The automatically created webpage has all DUNE words listed, with cross-references done via HTML links. A horizontal menu with all letters of the alphabet allows for a quick access.

Demo [here](https://dune.github.io/abcdune/).

## Usage
The script `abcdune.py` converts the LaTeX glossary (input file) that contains also custom LaTeX commands (in `defs.tex`) into HTML. It outputs the index page:
```sh
python3 abcdune.py -i glossary.tex -d defs.tex -o docs/index.html
```
## Test LaTeX

A small `test-all.tex` file may be used to build a PDF document with a just a glossary that includes all entries.

```sh
pdflatex test-all
makeglossaries test-all
pdflatex test-all
```

## Contribute
Feel free to contribute if you want to add, correct information or simply ask a question.
More information [here](https://dune.github.io/abcdune/help.html).
<!--- Tested with [glossary.tex](https://github.com/DUNE/dune-tdr/blob/master/common/glossary.tex) (last edit: May 7, 2020) 

## Updates
- More information on how to request a new acronym or correct one can be found in the associated wiki page [here](https://wiki.dunescience.org/wiki/ABC_DUNE).-->
