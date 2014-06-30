My PhD thesis
==================

Compiled on a Mac OS using [LatexTools](https://github.com/SublimeText/LaTeXTools) (Cmd+b shortcut) in [Sublime text editor](http://www.sublimetext.com/).

cleanup.sh script is then used to delete all extra files after compilation.

__List of abbreviations is not included in the final output file!!!__: this is still related to a compilation process. In the past I used this sequence of steps to include/update the list of abbreviations:

1. Run LaTeX 2 times then
2. ```bash
	makeindex thesis.nlo  -s nomencl.ist -o thesis.nls
	```
3. followed by running LaTeX once again.

Link to Edinburgh Research Archive: https://www.era.lib.ed.ac.uk/handle/1842/5751

TO DO: find out an exact sequence of compilation commands for both Mac and Linux
